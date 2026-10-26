---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API 参考
description: 检索表示指定字体样式和字体数据的字体数据的字节数组。
type: docs
weight: 131
url: /zh/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) 方法

检索表示指定字体样式和字体数据的字体数据的字节数组。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 包含关于字体 [IFontData](../../ifontdata/) 信息的字体数据对象。 |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | 要检索其数据的字体样式 [FontStyleType](../../fontstyletype/)。 |

### 返回值

一个包含指定字体样式的字体数据的字节数组。如果未找到字体数据或样式，则返回 null。

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## 另见

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)