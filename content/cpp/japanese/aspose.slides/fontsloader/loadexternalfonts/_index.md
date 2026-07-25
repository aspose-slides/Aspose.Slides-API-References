---
title: LoadExternalFonts()
second_title: Aspose.Slides for C++ API リファレンス
description: フォントを検索するために追加のフォルダーを追加します。
type: docs
weight: 1
url: /ja/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) メソッド

フォントを検索するための追加フォルダーを追加します。

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 追加フォントを読み込むディレクトリです。 |
## 備考

以下の例は、.TTF からカスタムフォントをロードする方法を示しています。 
```cpp
// ドキュメントディレクトリへのパス。
System::String dataDir = u"C:\\";

// フォントを検索するフォルダー
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// カスタムフォントディレクトリのフォントをロード
FontsLoader::LoadExternalFonts(folders);

// 作業を行い、プレゼンテーション/スライドのレンダリングを実行
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// フォントキャッシュをクリア
FontsLoader::ClearCache();
```

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [FontsLoader](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)