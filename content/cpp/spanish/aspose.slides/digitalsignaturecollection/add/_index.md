---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade la firma al final de la colección.
type: docs
weight: 53
url: /es/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) método


Añade la firma al final de la colección.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Firma a añadir. |
## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDigitalSignature](../../idigitalsignature/)
* Clase [DigitalSignatureCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)