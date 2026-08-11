---
title: get_SignTime()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "الوقت الذي تم توقيع المستند فيه. قراءة فقط System::DateTime."
type: docs
weight: 27
url: /ar/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() طريقة


الوقت الذي تم توقيع المستند فيه. قراءة فقط [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## انظر أيضًا

* فئة [DateTime](../../../system/datetime/)
* فئة [DigitalSignature](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)