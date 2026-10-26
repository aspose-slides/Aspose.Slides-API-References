---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف التوقيع في نهاية المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) طريقة

يضيف التوقيع في نهاية المجموعة.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### المعلمات

| معلمة | نوع | الوصف |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | التوقيع للإضافة. |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IDigitalSignature](../../idigitalsignature/)
* فئة [DigitalSignatureCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)