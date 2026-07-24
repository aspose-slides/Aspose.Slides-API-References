---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löschen wird.
type: docs
weight: 339
url: /de/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() Methode

Bestimmt, ob [Aspose.Slides](../../) beim Laden der Präsentation alle eingebetteten Binärobjekte löschen wird.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Hinweise

Die Arten der eingebetteten Binärobjekte:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Lese **bool**. 

Standardwert ist **false**. 

Das folgende Beispiel zeigt, wie die Präsentation ohne eingebettete Binärobjekte geladen wird. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Siehe auch

* Klasse [ILoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)