---
title: Box()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zabaluje typy hodnot pro převod na Object. Implementace pro výčtové typy.
type: docs
weight: 40
url: /cs/system/objectext/box/
---
## ObjectExt::Box(const T\&) metoda

Zabaluje typy hodnot pro převod na [Object](../../object/). Implementace pro výčtové typy.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) hodnota k zabalení. |

### Návratová hodnota

Inteligentní ukazatel na objekt uchovávající zabalenou hodnotu.

## ObjectExt::Box(const T\&) metoda

Zabaluje typy hodnot pro převod na [Object](../../object/). Implementace pro ne-výčtové typy.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Value type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Návratová hodnota

Inteligentní ukazatel na objekt uchovávající zabalenou hodnotu.

## ObjectExt::Box(const T\&) metoda

Zabaluje typy [Nullable](../../nullable/) pro převod na [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Value type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Návratová hodnota

Inteligentní ukazatel na objekt uchovávající zabalenou hodnotu.

## ObjectExt::Box(const String\&) metoda

Zabaluje řetězcové hodnoty.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Value to box. |

### Návratová hodnota

Zabalená hodnota nebo null, pokud je zdrojový řetězec null.

## Viz také

* Třída [SmartPtr](../../smartptr/)
* Třída [Object](../../object/)
* Třída [ObjectExt](../)
* Třída [String](../../string/)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)