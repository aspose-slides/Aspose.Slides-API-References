---
title: get_LinkPathRelative()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يُرجِع المسار النسبي إلى ملف مرتبط إذا كان موجودًا، وإلا يُرجِع سلسلة فارغة. للقراءة فقط System::String."
type: docs
weight: 131
url: /ar/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() طريقة

تُرجِع المسار النسبي إلى ملف مرتبط إذا كان موجودًا، وإلا تُرجِع سلسلة فارغة. للقراءة فقط [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## ملاحظات

في عروض Ppt التقديمية، قد تحتوي بعض روابط كائن Ole على تمثيل نسبي. 

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
* فئة [OleObjectFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)