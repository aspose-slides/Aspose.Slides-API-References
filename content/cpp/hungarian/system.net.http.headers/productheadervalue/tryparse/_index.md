---
title: TryParse()
second_title: Aspose.Slides C++ API referencia
description: Megpróbálja a megadott karakterláncot a ProductHeaderValue osztály egy példányává konvertálni.
type: docs
weight: 92
url: /hu/system.net.http.headers/productheadervalue/tryparse/
---
## ProductHeaderValue::TryParse(String, System::SharedPtr\<ProductHeaderValue\>\&) metódus

Megpróbálja átalakítani a megadott karakterláncot a [ProductHeaderValue](../) osztály egy példányává.

```cpp
static bool System::Net::Http::Headers::ProductHeaderValue::TryParse(String input, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | Egy feldolgozandó karakterlánc. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Egy példány, amelybe a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

Igaz, ha a feldolgozás sikeresen befejeződött, egyébként hamis.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ProductHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)