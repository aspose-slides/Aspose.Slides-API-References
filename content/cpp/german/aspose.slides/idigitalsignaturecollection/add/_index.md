---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt die Signatur am Ende der Sammlung hinzu.
type: docs
weight: 14
url: /de/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) Methode


Fügt die Signatur am Ende der Sammlung hinzu.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Signatur zum Hinzufügen. |
## Anmerkungen



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IDigitalSignature](../../idigitalsignature/)
* Klasse [IDigitalSignatureCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)