---
title: get_SignTime()
second_title: Aspose.Slides لـ C++ مرجع API
description: "الوقت الذي تم توقيع المستند فيه. للقراءة فقط System::DateTime."
type: docs
weight: 27
url: /ar/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() طريقة


الوقت الذي تم توقيع المستند فيه. للقراءة فقط [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## انظر أيضًا

* الفئة [DateTime](../../../system/datetime/)
* الفئة [IDigitalSignature](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)