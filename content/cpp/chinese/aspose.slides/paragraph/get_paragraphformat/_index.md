---
title: get_ParagraphFormat()
second_title: Aspose.Slides for C++ API 参考
description: 返回此段落的格式对象。只读 IParagraphFormat.
type: docs
weight: 14
url: /zh/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() 方法

返回此段落的格式对象。只读 [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## 备注

格式对象仅包含为当前段落定义的格式参数，未应用继承的数据。

为了获取包括继承在内的有效值，请使用 [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) 方法。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IParagraphFormat](../../iparagraphformat/)
* 类 [Paragraph](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)