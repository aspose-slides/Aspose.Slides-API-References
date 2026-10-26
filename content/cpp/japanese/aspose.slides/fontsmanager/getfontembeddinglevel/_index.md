---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides for C++ API リファレンス
description: フォントのバイト配列とフォント名から埋め込みレベルを決定します。
type: docs
weight: 144
url: /ja/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) メソッド

指定されたバイト配列とフォント名からフォントの埋め込みレベルを決定します。

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | フォントデータを含むバイト配列。 |
| fontName | [System::String](../../../system/string/) | フォントの名前。 |

### 戻り値

指定されたフォントの埋め込みレベル。

## 備考

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## 参照

* 列挙型 [EmbeddingLevel](../../embeddinglevel/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [FontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)