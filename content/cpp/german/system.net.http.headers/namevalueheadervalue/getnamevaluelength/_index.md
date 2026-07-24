---
title: GetNameValueLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der NameValueHeaderValue Klasse.
type: docs
weight: 118
url: /de/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) method


Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der [NameValueHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Eine zu parsende Zeichenkette. |
| startIndex | **int32_t** | Eine Startposition für das Parsen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Eine Instanz, in der ein geparstes Objekt zugewiesen wird. |

### Rückgabewert

Gibt die Länge eines geparsten Teilstrings zurück, sonst 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) method


Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der [NameValueHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Eine zu parsende Zeichenkette. |
| startIndex | **int32_t** | Eine Startposition für das Parsen. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Eine Funktion, die verwendet wird, um neue Instanzen der [NameValueHeaderValue](../) Klasse zu erzeugen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Eine Instanz, in der ein geparstes Objekt zugewiesen wird. |

### Rückgabewert

Gibt die Länge eines geparsten Teilstrings zurück, sonst 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)