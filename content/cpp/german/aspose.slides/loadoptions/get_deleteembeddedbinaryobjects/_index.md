---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.
type: docs
weight: 339
url: /de/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() Methode

Bestimmt, ob [Aspose.Slides](../../) beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Hinweise

Die Typen der eingebetteten Binärobjekte:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Lese **bool**. 

Standard ist **false**. 

Das folgende Beispiel zeigt, wie die Präsentation ohne eingebettete Binärobjekte geladen wird. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Siehe auch

* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)