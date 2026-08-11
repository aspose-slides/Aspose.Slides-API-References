---
title: get_DigitalSignatures()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. للقراءة فقط IDigitalSignatureCollection.
type: docs
weight: 261
url: /ar/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() طريقة

يعيد مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. للقراءة فقط [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;

    System::Console::WriteLine(u"Signatures used to sign the presentation: ");

    for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
    {
        auto signature = pres->get_DigitalSignatures()->idx_get(i);
        System::Console::WriteLine(u"{0}, {1} --- {2}",
            signature->get_Certificate()->get_SubjectName()->get_Name(),
            signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm"),
            (signature->get_IsValid() ? u"VALID" : u"INVALID")
        );
        allSignaturesAreValid &= signature->get_IsValid();
    }
}
@verbatim 
if (allSignaturesAreValid)
    System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
else
    System::Console::WriteLine(u"Presentation has been modified since signing.");
@endverbatim }
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* فئة [Presentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)