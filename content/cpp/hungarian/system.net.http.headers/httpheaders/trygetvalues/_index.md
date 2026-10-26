---
title: TryGetValues()
second_title: Aspose.Slides for C++ API referencia
description: Megpróbálja lekérni a megadott névhez tartozó értékeket.
type: docs
weight: 66
url: /hu/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) method

Megpróbálja lekérni a megfelelő értékeket a megadott név alapján.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A fejléc neve. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Egy példány, amelyhez a megfelelő értékek lesznek hozzárendelve. |

### Visszatérési érték

Igaz, ha a fejlécértékek megtalálhatók a megadott név alapján, egyébként hamis.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [HttpHeaders](../)
* Névterület [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)