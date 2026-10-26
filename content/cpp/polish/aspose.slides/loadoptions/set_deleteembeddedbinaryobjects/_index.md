---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.
type: docs
weight: 352
url: /pl/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metoda


Określa, czy [Aspose.Slides](../../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Uwagi


Typy osadzonych obiektów binarnych:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Zapisz **bool**. 

Domyślnie **false**. 

Poniższy przykład pokazuje, jak załadować prezentację bez jakichkolwiek osadzonych obiektów binarnych. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Zobacz także

* Klasa [LoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)