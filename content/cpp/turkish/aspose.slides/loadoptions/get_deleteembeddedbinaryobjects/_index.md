---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides için C++ API Referansı
description: Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.
type: docs
weight: 339
url: /tr/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metod


[Aspose.Slides](../../), sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Açıklamalar


Gömülü ikili nesnelerin türleri:

* VBA Proje [IPresentation::VbaProject](../)
* OLE Object gömülü veri [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) ikili veri [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Okunur **bool**. 

Varsayılan **false**'dur. 

Aşağıdaki örnek, sunumu gömülü ikili nesneler olmadan nasıl yükleneceğini gösterir. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## İlgili

* Sınıf [LoadOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)