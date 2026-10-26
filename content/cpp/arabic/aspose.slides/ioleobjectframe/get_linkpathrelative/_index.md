---
title: get_LinkPathRelative()
second_title: مرجع API Aspose.Slides للغة C++
description: "يرجع المسار النسبي إلى ملف مرتبط إذا كان موجودًا، وإلا يرجع سلسلة فارغة. Readonly System::String."
type: docs
weight: 118
url: /ar/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() طريقة


يرجع المسار النسبي إلى ملف مرتبط إذا كان موجودًا، وإلا يرجع سلسلة فارغة. للقراءة فقط [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## ملاحظات


في عروض Ppt التقديمية، قد تحتوي بعض روابط كائنات Ole على تمثيل نسبي.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [IOleObjectFrame](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)