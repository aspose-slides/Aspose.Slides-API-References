---
title: GetProductInfoLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der ProductInfoHeaderValue Klasse.
type: docs
weight: 105
url: /de/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) Methode


Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der [ProductInfoHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein zu parsender String. |
| startIndex | **int32_t** | Eine Startposition für das Parsen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | Eine Instanz, in die das geparste Objekt zugewiesen wird. |

### Rückgabewert

Gibt die Länge eines geparsten Teilstrings zurück, andernfalls 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ProductInfoHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)