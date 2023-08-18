---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the signature at the end of collection.
type: docs
weight: 14
url: /aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) method


Adds the signature at the end of collection.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Signature to add. |
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDigitalSignature](../../idigitalsignature/)
* Class [IDigitalSignatureCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)