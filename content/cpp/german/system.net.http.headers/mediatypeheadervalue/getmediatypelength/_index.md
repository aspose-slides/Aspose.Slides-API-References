---
title: GetMediaTypeLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der MediaTypeHeaderValue Klasse.
type: docs
weight: 144
url: /de/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) Methode


Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der [MediaTypeHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein String zum Parsen. |
| startIndex | **int32_t** | Eine Startposition für das Parsen. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Der Delegat, der verwendet wird, um Instanzen der [MediaTypeHeaderValue](../) Klasse zu erstellen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Eine Instanz, in der ein geparstes Objekt zugewiesen wird. |

### Rückgabewert

Gibt die Länge eines geparsten Teilstrings zurück, sonst 0.

## Siehe auch

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [MediaTypeHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)