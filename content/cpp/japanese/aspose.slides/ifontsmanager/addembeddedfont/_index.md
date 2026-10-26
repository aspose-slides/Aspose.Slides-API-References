---
title: AddEmbeddedFont()
second_title: Aspose.Slides for C++ API リファレンス
description: 埋め込みフォントを追加します。
type: docs
weight: 105
url: /ja/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) メソッド

埋め込みフォントを追加します。

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font data object [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## 備考

フォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに留意してください。事前にフォントのライセンスを確認し、別のマシンに自由に転送できるかどうかを検証してください。

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) メソッド

埋め込みフォントを追加します。

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## 備考

フォントを追加する際は、ほとんどのフォントが著作権で保護されていることに留意してください。事前にフォントのライセンスを確認し、別のマシンに自由に転送できるかどうかを検証してください。

## 関連項目

* 列挙型 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IFontData](../../ifontdata/)
* クラス [IFontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)