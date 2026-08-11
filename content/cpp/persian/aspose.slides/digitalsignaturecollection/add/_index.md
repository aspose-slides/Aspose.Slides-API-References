---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: امضا را در انتهای مجموعه اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) متد

امضا را در انتهای مجموعه اضافه می‌کند.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | امضا برای افزودن. |
## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDigitalSignature](../../idigitalsignature/)
* کلاس [DigitalSignatureCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)