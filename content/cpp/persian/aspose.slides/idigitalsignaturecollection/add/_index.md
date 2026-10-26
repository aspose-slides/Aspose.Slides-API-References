---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: امضا را در انتهای مجموعه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) متد

امضا را در انتهای مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | امضای افزودنی. |

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## مراجعه

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDigitalSignature](../../idigitalsignature/)
* کلاس [IDigitalSignatureCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)