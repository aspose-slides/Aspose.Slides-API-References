---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides için C++ API Referansı
description: Sunum yüklenirken Aspose.Slides'in tüm gömülü ikili nesneleri silip silmeyeceğini belirler.
type: docs
weight: 352
url: /tr/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) method

Sunum yüklenirken [Aspose.Slides](../../) tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Remarks

Gömülü ikili nesnelerin türleri:

* VBA Projesi [IPresentation::VbaProject](../)
* OLE Nesnesi gömülü veri [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) ikili veri [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Yazın **bool**.

Varsayılan **false**.

Aşağıdaki örnek, sunumu herhangi bir gömülü ikili nesne olmadan nasıl yükleyeceğinizi gösterir.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Bakınız

* Sınıf [ILoadOptions](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)