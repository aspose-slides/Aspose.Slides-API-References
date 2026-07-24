---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: İmzayı koleksiyonun sonuna ekler.
type: docs
weight: 53
url: /tr/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) metot

İmzayı koleksiyonun sonuna ekler.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Eklenecek imza. |
## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDigitalSignature](../../idigitalsignature/)
* Sınıf [DigitalSignatureCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)