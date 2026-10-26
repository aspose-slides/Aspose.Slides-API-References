---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.
type: docs
weight: 352
url: /de/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) Methode

Bestimmt, ob [Aspose.Slides](../../) beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Hinweise

Die Typen der eingebetteten Binärobjekte:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Schreiben **bool**. 

Standard ist **false**. 

Das folgende Beispiel zeigt, wie die Präsentation ohne irgendwelche eingebetteten Binärobjekte geladen wird. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Siehe Auch

* Klasse [ILoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)