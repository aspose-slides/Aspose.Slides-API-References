---
title: Create()
second_title: Aspose.Slides C++ API referencia
description: Kultúra-specifikus összehasonlítót hoz létre.
type: docs
weight: 79
url: /hu/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) metódus


Kultúra-specifikus összehasonlítót hoz létre.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | A kultúra, amelyhez az összehasonlítót létrehozzuk. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlító figyelmen kívül hagyja-e a kis- és nagybetűket. |

### Visszatérési érték

Mutató az újonnan létrehozott összehasonlító objektumra.

## Lásd még

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [StringComparer](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)