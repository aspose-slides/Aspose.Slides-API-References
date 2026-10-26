---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute la signature à la fin de la collection.
type: docs
weight: 14
url: /fr/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) méthode


Ajoute la signature à la fin de la collection.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Signature à ajouter. |
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
* Classe [IDigitalSignatureCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)