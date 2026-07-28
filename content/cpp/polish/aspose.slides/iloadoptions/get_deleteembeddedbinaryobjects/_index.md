---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.
type: docs
weight: 339
url: /pl/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() metoda

Określa, czy [Aspose.Slides](../../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Uwagi

Typy osadzonych obiektów binarnych:

* Projekt VBA [IPresentation::VbaProject](../)
* Dane osadzone obiektu OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) dane binarne [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Odczyt **bool**. 

Domyślnie jest **false**. 

Poniższy przykład pokazuje, jak załadować prezentację bez żadnych osadzonych obiektów binarnych. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Zobacz także

* Klasa [ILoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)