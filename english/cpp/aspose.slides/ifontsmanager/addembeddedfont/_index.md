---
title: AddEmbeddedFont()
second_title: Aspose.Slides for C++ API Reference
description: Adds the embedded font.
type: docs
weight: 105
url: /cpp/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) method


Adds the embedded font.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font data object [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## Remarks


Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine.


## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) method


Adds the embedded font

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## Remarks


Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine.


## See Also

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)