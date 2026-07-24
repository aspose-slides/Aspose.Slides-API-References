---
title: GetNameValueListLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen übergebenen String ab dem angegebenen Index in die Sammlung der NameValueHeaderValue-Klasseninstanzen und gibt die Länge einer geparsten Teilzeichenkette zurück.
type: docs
weight: 131
url: /de/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) Methode

Konvertiert einen übergebenen String ab dem angegebenen Index in die Sammlung der NameValueHeaderValue-Klasseninstanzen und gibt die Länge einer geparsten Teilzeichenkette zurück.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein String zum Analysieren. |
| startIndex | **int32_t** | Eine Startposition für die Analyse. |
| delimiter | char16_t | Ein String, der verwendet wird, um Elemente im angegebenen String zu trennen. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Der Ausgangsparameter, dem eine geparste Sammlung zugewiesen wird. |

### Rückgabewert

Die Länge einer geparsten Teilzeichenkette.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ObjectCollection](../../objectcollection/)
* Klasse [NameValueHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)