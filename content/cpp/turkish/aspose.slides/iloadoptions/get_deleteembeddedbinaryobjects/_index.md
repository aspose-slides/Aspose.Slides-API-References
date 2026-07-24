---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API Referansı
description: Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.
type: docs
weight: 339
url: /tr/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() metodu

[Aspose.Slides](../../), sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Açıklamalar

Gömülü ikili nesnelerin türleri:

* VBA Projesi [IPresentation::VbaProject](../)
* OLE Nesnesi gömülü veri [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) ikili veri [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Oku **bool**. 

Varsayılan **false**. 

Aşağıdaki örnek, sunumu herhangi bir gömülü ikili nesne olmadan nasıl yükleneceğini gösterir. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Bakınız

* Sınıf [ILoadOptions](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)