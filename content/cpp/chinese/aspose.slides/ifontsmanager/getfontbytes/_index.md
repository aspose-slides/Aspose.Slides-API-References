---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API 参考
description: 检索表示指定字体样式和字体数据的字节数组。
type: docs
weight: 131
url: /zh/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) 方法

检索表示指定字体样式和字体数据的字节数组。

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 包含关于字体[IFontData](../../ifontdata/)信息的字体数据对象。 |
| fontStyle | [FontStyleType](../../fontstyletype/) | 要检索数据的字体样式[FontStyleType](../../fontstyletype/)。 |

### 返回值

包含指定字体样式的字体数据的字节数组。如果未找到字体数据或样式，则返回 null。

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## 另见

* 枚举 [FontStyleType](../../fontstyletype/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IFontData](../../ifontdata/)
* 类 [IFontsManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)