---
title: FieldAttributes
second_title: Aspose.Slides C++ API referencia
description: Visszatükrözött mezőattribútumok.
type: docs
weight: 170
url: /hu/system.reflection/fieldattributes/
---
## FieldAttributes enum

Visszatükrözött mezőattribútumok.

```cpp
enum class FieldAttributes
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| FieldAccessMask | 7 | A tag hozzáférési maszkja. Használja ezt a maszkot a hozzáférhetőségi információk lekéréséhez. |
| PrivateScope | 0 | Nem hivatkozható tagok. |
| Private | 1 | Privát tagok. |
| FamANDAssem | 2 | Privát és assembly-hez kötött tagok. |
| Assembly | 3 | Assembly-hez kötött tagok. |
| Family | 4 | A típus és al-típusok által elérhető tagok. |
| FamORAssem | 5 | A típus, al-típusok és assembly által elérhető tagok. |
| Public | 6 | Bárki által elérhető tagok. |
| Static | 16 | Statikus tagok, ellentétben a példánytagokkal. |
| InitOnly | 32 | Konstans tagok, amelyek csak inicializálhatók, nem módosíthatók. |
| Literal | 64 | Fordítási időben állandó tagok. |
| NotSerialized | 128 | Nem sorosított tagok. |
| SpecialName | 512 | Speciális mező az alábbi nevek egyikével. |
| PinvokeImpl | 8192 | Interop által továbbított megvalósítás. |
| ReservedMask | 38144 | Csak futásidőben használható fenntartott jelzők. |
| RTSpecialName | 1024 | A futásidőnek ellenőriznie kell a névkódolást. |
| HasFieldMarshal | 4096 | Marshalling információ elérhető. |
| HasDefault | 32768 | Alapértelmezett érték jelen van. |
| HasFieldRVA | 256 | RVA jelen van. |

## Lásd még

* Névtér [System::Reflection](../)
* Könyvtár [Aspose.Slides](../../)