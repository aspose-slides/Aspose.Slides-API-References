---
title: get_IsValid()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، فستكون هذه القيمة true. قراءة فقط bool.
type: docs
weight: 14
url: /ar/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() طريقة


إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، فستكون هذه القيمة true. قراءة فقط **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

* الفئة [DigitalSignature](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)