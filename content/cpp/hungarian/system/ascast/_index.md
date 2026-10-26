---
title: AsCast()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a forrástípust a cél típusra az 'as' operátorral. Egyszerű, konstruktor-szerű átalakításra van szükség.
type: docs
weight: 2640
url: /hu/system/ascast/
---
## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Egyszerű, konstruktorhoz hasonló átalakításra van szükség.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Akkor használható, amikor a forrás- és a cél típusok megegyeznek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Kivételburkolókhoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye. Nullptr-t ad vissza, ha nincs konverzió.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Kivételbe való objektum átalakításhoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye. Nullptr-t ad vissza, ha nincs konverzió.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Akkor használható, ha a forrás és a cél egyaránt okos mutatók.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye. Nullptr-t ad vissza, ha nincs konverzió.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Akkor használható, ha a forrás és a cél egyaránt okos mutatók (a cél típusban explicite SmartPtr<...> van).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye. Nullptr-t ad vissza, ha nincs konverzió.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Nullable objektum kibontásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye. Üres nullable-t ad vissza, ha nincs konverzió.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Érvénytelen kibontás nem-objektum típusra.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Mindig null értéket ad vissza.

## System::AsCast(const Source\&) function

Érvénytelen kibontás nem-objektum típusra.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Mindig null értéket ad vissza.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Nullable objektum befoglalásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Általános objektum befoglalásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Általános objektum befoglalásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Karakterlánc kibontásához használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. nullptr esetén használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye.

## System::AsCast(const Source\&) function

Átalakítja a forrástípust a cél típusra az 'as' operátorral. Tömbök közötti átalakításhoz használható.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | A cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) a konvertáláshoz. |

### Visszatérési érték

Az átalakítás eredménye. Nullptr-t ad vissza, ha nincs konverzió egyetlen tömb elemre sem.

## Lásd még

* Typedef [Exception](../exception/)
* Struktúra [CastResult](../castresult/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)