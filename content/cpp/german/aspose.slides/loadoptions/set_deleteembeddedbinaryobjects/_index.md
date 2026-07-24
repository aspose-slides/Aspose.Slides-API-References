---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.
type: docs
weight: 352
url: /de/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) Methode


Bestimmt, ob [Aspose.Slides](../../) beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Hinweise


Die Arten der eingebetteten Binärobjekte:

* VBA-Projekt [IPresentation::VbaProject](../)
* OLE-Objekt eingebettete Daten [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) Binärdaten [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Schreiben **bool**. 

Standardwert ist **false**. 

Das folgende Beispiel zeigt, wie man die Präsentation ohne eingebettete Binärobjekte lädt. 
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