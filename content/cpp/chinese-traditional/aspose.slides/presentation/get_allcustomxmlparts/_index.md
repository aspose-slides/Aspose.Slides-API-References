---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回簡報中的所有自訂資料部件。唯讀 ICustomXmlPart[].
type: docs
weight: 287
url: /zh-hant/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() 方法

返回簡報中的所有自訂資料部件。唯讀 [ICustomXmlPart](../../icustomxmlpart/)[]。

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## 備註

以下範例說明如何從 PowerPoint [Presentation](../) 中清除所有自訂 XML 部件。
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ICustomXmlPart](../../icustomxmlpart/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)