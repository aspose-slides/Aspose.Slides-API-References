---
title: CastEnumerableTo()
second_title: Aspose.Slides C++ API-referencia
description: Végrehajtja a megadott enumerálható objektum elemeinek explicit átkonvertálását más típusra.
type: docs
weight: 2965
url: /hu/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) függvény


Explicit módon átkonvertálja a megadott enumerálható objektum elemeit más típusra.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| To | A típus, amelyre statikusan átkastolja az enumerálható objektum elemeit |
| From | Az enumerálható objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| enumerable | const From\& | Az elemeket tartalmazó enumerálható objektum, amelyet át kell konvertálni |

### Visszatérési érték

Egy új gyűjteményre mutató pointer, amely **To** típusú elemeket tartalmaz, amelyek egyenértékűek a **enumerable** elemeivel.

## System::CastEnumerableTo(const From\&) függvény


Explicit módon átkonvertálja a megadott enumerálható objektum elemeit más típusra.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| To | A típus, amelyre statikusan átkastolja az enumerálható objektum elemeit |
| From | Az enumerálható objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| enumerable | const From\& | is inheritor of Enumerable object with defined get_Count method and containing the elements to cast |

### Visszatérési érték

Egy új gyűjteményre mutató pointer, amely **To** típusú elemeket tartalmaz, amelyek egyenértékűek a **enumerable** elemeivel.

## Lásd még

* Osztály [ListPtr](../../system.collections.generic/listptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)