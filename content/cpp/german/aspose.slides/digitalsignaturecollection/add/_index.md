---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt die Signatur am Ende der Sammlung hinzu.
type: docs
weight: 53
url: /de/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) Methode


Fügt die Signatur am Ende der Sammlung hinzu.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Zu hinzufügende Signatur. |
## Bemerkungen



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDigitalSignature](../../idigitalsignature/)
* Klasse [DigitalSignatureCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)