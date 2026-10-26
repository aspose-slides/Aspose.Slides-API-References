---
title: BindingFlags
second_title: Aspose.Slides for C++ API referenciája
description: Meghatározza a tagok és típusok keresési módjait és kötéseit.
type: docs
weight: 157
url: /hu/system.reflection/bindingflags/
---
## BindingFlags enum

Tagok és típusok keresési módjainak és kötéseinek meghatározása.

```cpp
enum class BindingFlags
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Default | 0 | Nincsenek speciális opciók. |
| IgnoreCase | 1 | Figyelmen kívül hagyja a név kis- és nagybetűit elem keresésekor. |
| DeclaredOnly | 2 | Csak az adott típusban deklarált tagokat keresi, az ős típusokban nem lévőket. |
| Instance | 4 | Az példánytagokon keresztül néz. |
| Static | 8 | A statikus tagokon keresztül néz. |
| Public | 16 | A nyilvános tagokon keresztül néz. |
| NonPublic | 32 | A nem nyilvános tagokon keresztül néz. |
| FlattenHierarchy | 64 | Az ős típus nyilvános és védett statikus tagjainak keresése. |
| InvokeMethod | 256 | Metódust hív meg. |
| CreateInstance | 512 | Létrehozza a visszatükrözött típus példányát. |
| GetField | 1024 | Mezőértéket kér le. |
| SetField | 2048 | Mezőértéket állít be. |
| GetProperty | 4096 | Tulajdonságértéket kér le. |
| SetProperty | 8192 | Tulajdonságértéket állít be. |
| PutDispProperty | 16384 | COM tulajdonságot állít be. |
| PutRefDispProperty | 32768 | COM referencia tulajdonságot állít be. |
| ExactBinding | 65536 | A típuskötésnek pontosnak kell lennie, típusváltoztatás nélkül. |
| SuppressChangeType | 131072 | Nem támogatott. |
| OptionalParamBinding | 262144 | A paraméterek száma alapján választja ki a túlterhelést. |
| IgnoreReturn | 16777216 | Figyelmen kívül hagyja a COM interop visszatérési értéket. |

## Lásd még

* Névtér [System::Reflection](../)
* Könyvtár [Aspose.Slides](../../)