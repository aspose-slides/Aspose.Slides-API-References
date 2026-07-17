---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides for C++ API 参考
description: 确定给定字节数组和字体名称的字体嵌入级别。
type: docs
weight: 144
url: /zh/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) 方法


确定给定字节数组和字体名称的字体嵌入级别。

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含字体数据的字节数组。 |
| fontName | [System::String](../../../system/string/) | 字体的名称。 |

### 返回值

指定字体的嵌入级别。
## 备注




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## 另请参见

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)