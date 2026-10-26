---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides için C++ API Referansı
description: Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.
type: docs
weight: 352
url: /tr/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metod

[Aspose.Slides](../../) sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Açıklamalar

Gömülü ikili nesnelerin türleri:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) ikili veri [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Yaz **bool**.

Varsayılan **false**.

Aşağıdaki örnek, sunumu herhangi bir gömülü ikili nesne olmadan nasıl yükleyeceğinizi gösterir.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## İlgili

* Sınıf [LoadOptions](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)