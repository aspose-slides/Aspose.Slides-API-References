---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.
type: docs
weight: 339
url: /pl/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metoda


Określa, czy [Aspose.Slides](../../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Uwagi


Typy osadzonych obiektów binarnych:

* Projekt VBA [IPresentation::VbaProject](../)
* Dane osadzonego obiektu OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) dane binarne [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Odczyt **bool**. 

Domyślna wartość to **false**. 

Poniższy przykład pokazuje, jak wczytać prezentację bez żadnych osadzonych obiektów binarnych. 
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