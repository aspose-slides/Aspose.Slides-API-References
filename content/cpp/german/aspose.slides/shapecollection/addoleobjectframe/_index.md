---
title: AddOleObjectFrame()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.
type: docs
weight: 183
url: /de/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) Methode

Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen OLE-Rahmens in Punkten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Die Informationen über die eingebetteten OLE-Daten ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Rückgabewert

Der neu erstellte [IOleObjectFrame](../../ioleobjectframe/).

## Bemerkungen

Das folgende Beispiel zeigt, wie OLE-Objektrahmen zu [Slides](../../) von PowerPoint [Presentation](../../presentation/) hinzugefügt werden.

```cpp
auto pres = System::MakeObject<Presentation>();

// Greift auf die erste Folie zu
auto slide = pres->get_Slides()->idx_get(0);
// Lädt eine Excel-Datei in einen Stream
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Erstellt ein Datenobjekt zum Einbetten
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Fügt ein Ole-Objektrahmen-Shape hinzu
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Schreibt die PPTX-Datei auf die Festplatte
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) Methode

Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen OLE-rahmens in Punkten. |
| className | [System::String](../../../system/string/) | Der Klassenname des OLE-Objekts. |
| path | [System::String](../../../system/string/) | Der Pfad zur verknüpften Datei. |

### Rückgabewert

Der neu erstellte [IOleObjectFrame](../../ioleobjectframe/).

## Bemerkungen

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wenn ein relativer Pfad angegeben wird, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)