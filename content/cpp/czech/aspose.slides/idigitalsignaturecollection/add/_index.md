---
title: Add()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá podpis na konec kolekce.
type: docs
weight: 14
url: /cs/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) metoda

Přidá podpis na konec kolekce.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Podpis k přidání. |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDigitalSignature](../../idigitalsignature/)
* Třída [IDigitalSignatureCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)