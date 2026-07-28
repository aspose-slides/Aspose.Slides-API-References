---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides dla C++ – referencja API
description: Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.
type: docs
weight: 352
url: /pl/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metoda


Określa, czy [Aspose.Slides](../../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Uwagi


Rodzaje osadzonych obiektów binarnych:

* Projekt VBA [IPresentation::VbaProject](../)
* Dane osadzone obiektu OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) dane binarne [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Zapisz **bool**. 

Domyślnie **false**. 

Poniższy przykład pokazuje, jak załadować prezentację bez żadnych osadzonych obiektów binarnych. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Zobacz też

* Klasa [ILoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)