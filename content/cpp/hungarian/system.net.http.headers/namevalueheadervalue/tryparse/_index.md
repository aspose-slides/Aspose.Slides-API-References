---
title: TryParse()
second_title: Aspose.Slides C++ API Referenciája
description: Megpróbálja a megadott karakterláncot a NameValueHeaderValue osztály egy példányává konvertálni.
type: docs
weight: 105
url: /hu/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) metódus


Megpróbál egy átadott karakterláncot átalakítani a [NameValueHeaderValue](../) osztály egy példányává.

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Egy példány, amelybe a feldolgozott objektum kerül hozzárendelésre. |

### Visszatérési érték

Igaz, ha a feldolgozás sikeresen befejeződött, ellenkező esetben hamis.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [NameValueHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)