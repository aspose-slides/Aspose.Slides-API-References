---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt geschlossene WebVTT-Untertitel am Ende der Sammlung hinzu.
type: docs
weight: 27
url: /de/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) Methode

Fügt geschlossene WebVTT-Untertitel am Ende der Sammlung hinzu.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Das label der geschlossenen Untertitel. |
| filePath | [System::String](../../../system/string/) | Der Pfad zur WebVTT-Datei. |

### Rückgabewert

Die hinzugefügte [ICaptions](../../icaptions/) Instanz.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) Methode

Fügt geschlossene WebVTT-Untertitel am Ende der Sammlung aus einem Stream hinzu.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Das label der geschlossenen Untertitel. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der Eingabestream, der Daten im WebVTT-Format enthält. |

### Rückgabewert

Die hinzugefügte [ICaptions](../../icaptions/) Instanz.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptions](../../icaptions/)
* Klasse [String](../../../system/string/)
* Klasse [CaptionsCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)