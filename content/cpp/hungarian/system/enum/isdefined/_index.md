---
title: IsDefined()
second_title: Aspose.Slides for C++ API Referenciája
description: Megállapítja, hogy a megadott érték az E enumeráció típus tagja-e.
type: docs
weight: 27
url: /hu/system/enum/isdefined/
---
## Enum::IsDefined(E) metódus

Megállapítja, hogy a megadott érték az **E** enumeráció típus tagja-e.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | E | Az ellenőrizendő érték |

### Visszatérési érték

Igaz, ha **value** az **E** enumeráció tagja, egyébként - hamis

## Enum::IsDefined(T) metódus

Megállapítja, hogy a megadott érték az **T** enumeráció típus tagja-e.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az ellenőrizendő érték |

### Visszatérési érték

Igaz, ha **value** az **T** enumeráció tagja, egyébként - hamis

## Enum::IsDefined(const String\&) metódus

Megállapítja, hogy a megadott névvel rendelkező érték szerepel-e az **E** enum tagjai között.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../string/)\& | Az ellenőrizendő név |

### Visszatérési érték

Igaz, ha létezik az **E** enum megadott névvel rendelkező tagja.

## Lásd még

* Typedef [UnderlyingType](../underlyingtype/)
* Osztály [String](../../string/)
* Struktúra [Enum](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)