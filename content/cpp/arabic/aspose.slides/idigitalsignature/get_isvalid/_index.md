---
title: get_IsValid()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، فستكون هذه القيمة صحيحة. قراءة فقط bool.
type: docs
weight: 14
url: /ar/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() طريقة


إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، فستكون هذه القيمة صحيحة. قراءة فقط **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## انظر أيضًا

* فئة [IDigitalSignature](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)