---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides C++ API 参考
description: 返回演示文稿中的所有自定义数据部件。只读 ICustomXmlPart[].
type: docs
weight: 287
url: /zh/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() 方法

返回演示文稿中的所有自定义数据部件。只读 [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## 备注

以下示例展示如何从 PowerPoint [Presentation](../) 中清除所有自定义 XML 部件。

```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICustomXmlPart](../../icustomxmlpart/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)