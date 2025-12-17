---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the signature at the end of collection.
type: docs
weight: 53
url: /aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) method


Adds the signature at the end of collection.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Signature to add. |
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDigitalSignature](../../idigitalsignature/)
* Class [DigitalSignatureCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)