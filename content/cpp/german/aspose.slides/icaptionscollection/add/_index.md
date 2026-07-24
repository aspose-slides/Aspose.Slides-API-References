---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Sammlung geschlossene WebVTT-Untertitel am Ende hinzu.
type: docs
weight: 27
url: /de/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) Methode

Fügt der Sammlung WebVTT-Untertitel am Ende hinzu.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Das Label der geschlossenen Untertitel. |
| filePath | [System::String](../../../system/string/) | Der Pfad zur WebVTT-Datei. |

### Rückgabewert

Die hinzugefügte [ICaptions](../../icaptions/)-Instanz.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) Methode

Fügt der Sammlung WebVTT-Untertitel von einem Stream am Ende hinzu.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Das Label der geschlossenen Untertitel. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der Eingabestream, der Daten im WebVTT-Format enthält. |

### Rückgabewert

Die hinzugefügte [ICaptions](../../icaptions/)-Instanz.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptions](../../icaptions/)
* Klasse [String](../../../system/string/)
* Klasse [ICaptionsCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)