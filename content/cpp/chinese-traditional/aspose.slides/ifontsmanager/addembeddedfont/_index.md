---
title: AddEmbeddedFont()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 新增嵌入式字型。
type: docs
weight: 105
url: /zh-hant/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) 方法


新增嵌入式字型。

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 字型資料物件 [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | 嵌入式字型規則 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## 備註


請記住，在複製任何字型時，大多數字型受到版權保護。請先確認字型的授權，並確保可以自由轉移至其他機器。


## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) 方法


新增嵌入式字型

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 字型資料 **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | 嵌入式字型規則 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## 備註


請記住，在新增任何字型時，大多數字型受到版權保護。請先確認字型的授權，並確保可以自由轉移至其他機器。


## 另請參閱

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [IFontData](../../ifontdata/)
* 類別 [IFontsManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)