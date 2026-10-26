---
title: Add()
second_title: Aspose.Slides لمرجع API لـ C++
description: يضيف التوقيع في نهاية المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) طريقة

يضيف التوقيع في نهاية المجموعة.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | التوقيع للإضافة. |
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
* فئة [IDigitalSignatureCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)