---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge la firma alla fine della collezione.
type: docs
weight: 53
url: /it/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) metodo


Aggiunge la firma alla fine della collezione.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Firma da aggiungere. |
## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDigitalSignature](../../idigitalsignature/)
* Classe [DigitalSignatureCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)