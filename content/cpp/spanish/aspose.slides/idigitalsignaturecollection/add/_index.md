---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega la firma al final de la colección.
type: docs
weight: 14
url: /es/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) método


Agrega la firma al final de la colección.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Firma a agregar. |
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
* Clase [IDigitalSignatureCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)