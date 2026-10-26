---
title: TryParse()
second_title: Aspose.Slides C++ API referenciája
description: Megpróbálja a megadott karakterláncot az AuthenticationHeaderValue osztály példányává konvertálni.
type: docs
weight: 105
url: /hu/system.net.http.headers/authenticationheadervalue/tryparse/
---
## AuthenticationHeaderValue::TryParse(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) method


Megpróbálja a megadott karakterláncot a [AuthenticationHeaderValue](../) osztály egy példányává konvertálni.

```cpp
static bool System::Net::Http::Headers::AuthenticationHeaderValue::TryParse(String input, System::SharedPtr<AuthenticationHeaderValue> &parsedValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[AuthenticationHeaderValue](../)\>\& | Egy példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

True, ha a feldolgozás sikeresen befejeződik, egyébként false.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [AuthenticationHeaderValue](../)
* Névtér [System::Net::Http::Headers](../../)
* Könyvtár [Aspose.Slides](../../../)