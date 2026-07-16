---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute la signature à la fin de la collection.
type: docs
weight: 53
url: /fr/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) méthode


Ajoute la signature à la fin de la collection.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Signature à ajouter. |
## Remarques



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDigitalSignature](../../idigitalsignature/)
* Classe [DigitalSignatureCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)