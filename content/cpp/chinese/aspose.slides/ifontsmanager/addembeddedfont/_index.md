---
title: AddEmbeddedFont()
second_title: Aspose.Slides for C++ API 参考
description: 添加嵌入的字体。
type: docs
weight: 105
url: /zh/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) 方法

添加嵌入的字体。

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 字体数据对象 [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | 嵌入字体规则 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## 备注

在复制任何字体时请记住，大多数字体受版权保护。请事先查找字体的许可证，并确认它们可以自由转移到另一台机器。

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) 方法

添加嵌入的字体

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 字体数据 **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | 嵌入字体规则 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## 备注

在添加任何字体时请记住，大多数字体受版权保护。请事先查找字体的许可证，并确认它们可以自由转移到另一台机器。

## 另请参见

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)