---
title: ExplicitCast()
second_title: Aspose.Slides C++ API Referenciája
description: Az explicit típusátalakítással a forrástípust az eredménytípusra konvertálja. Akkor használható, amikor a forrás és az eredménytípusok megegyeznek.
type: docs
weight: 2627
url: /hu/system/explicitcast/
---
## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Akkor használható, amikor a forrás- és eredménytípusok megegyeznek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Akkor használható, amikor egyszerű, konstruktor-szerű átalakításra van szükség.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Kivételburkolókhoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Objektum kivételre konvertálásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Akkor használható, amikor a forrás és az eredmény is okos mutató (a result típusban nincs explicit SmartPtr<...>).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(Source) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Nyers mutató okos mutatóvá konvertálásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | Source | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Akkor használható, amikor a forrás és az eredmény is okos mutató (az eredménytípusban explicit SmartPtr<...> van).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Nullable értékre történő objektum kicsomagolásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Nullable érték dobozolásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Nullable objektum kicsomagolásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Enum dobozoláshoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Értéktípusok halomra másolásához használható, amikor az értéktípust okos mutatóként kell hivatkozni (generikusoknál, amelyek interfész típusra vannak korlátozva, de a struktúra implementálja ezt az interfészt).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Értéktípusokból interfészek lekéréséhez használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Általános dobozoláshoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. A [System::String](../string/) dobozoláshoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Interfészek kicsomagolásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Általános kicsomagoláshoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. nullptr konvertálásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## System::ExplicitCast(const Source\&) függvény


Az explicit típuskonverzióval a forrástípust a eredménytípusra konvertálja. Tömbök közötti konvertáláshoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredménytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) átkonvertálandó. |

### Visszatérési érték

A konvertálás eredménye.

## Lásd még

* Typedef [Exception](../exception/)
* Osztály [SmartPtr](../smartptr/)
* Osztály [BoxedValueBase](../boxedvaluebase/)
* Struktúra [CastResult](../castresult/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)