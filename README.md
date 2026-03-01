# WinFormsBlazorHybrid

Windows Forms で Blazor Hybrid を構築すると、公式ドキュメントの手順ではプロジェクト構成が煩雑になりがちです。
本リポジトリでは、標準的な Blazor アプリの構成に準拠する形で再構築しています。

## プロジェクト構成
```text
WinFormsBlazorHybrid/
├─wwwroot/
│  ├─css/
│  └─index.html
├─Components/
│  ├─Layout/
│  ├─Pages/
│  ├─_Imports.razor
│  └─Routes.razor
├─MainForm.cs
└─Program.cs
```

## 実行方法

### 前提条件
- .NET 10 SDK

### 実行手順
```bash
# リポジトリをクリーン
git clone https://github.com/monakacode/WinFormsBlazorHybrid.git
cd WinFormsBlazorHybrid

# ビルド
dotnet build

# 実行
dotnet run --project WinFormsBlazorHybrid
```

## 参考文献
- [Windows フォームの Blazor アプリを構築する](https://learn.microsoft.com/ja-jp/aspnet/core/blazor/hybrid/tutorials/windows-forms?view=aspnetcore-10.0)

## ライセンス
MIT License
