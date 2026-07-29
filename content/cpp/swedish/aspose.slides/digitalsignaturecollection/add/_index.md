---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till signaturen i slutet av samlingen.
type: docs
weight: 53
url: /sv/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) metod

Lägger till signaturen i slutet av samlingen.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Signatur att lägga till. |
## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDigitalSignature](../../idigitalsignature/)
* Klass [DigitalSignatureCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)