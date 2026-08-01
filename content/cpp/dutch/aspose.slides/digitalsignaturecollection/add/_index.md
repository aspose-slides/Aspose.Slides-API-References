---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt de handtekening toe aan het einde van de collectie.
type: docs
weight: 53
url: /nl/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) methode

Voegt de handtekening toe aan het einde van de collectie.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Handtekening om toe te voegen. |
## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDigitalSignature](../../idigitalsignature/)
* Klasse [DigitalSignatureCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)