---
title: IsDefined()
second_title: Referencja API Aspose.Slides dla C++
description: Określa, czy podana wartość jest członkiem typu wyliczeniowego E.
type: docs
weight: 27
url: /pl/system/enum/isdefined/
---
## Enum::IsDefined(E) metoda

Określa, czy podana wartość jest członkiem typu wyliczeniowego **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | E | Wartość do sprawdzenia |

### Wartość zwracana

Prawda, jeśli **value** jest członkiem wyliczenia **E**, w przeciwnym razie - fałsz

## Enum::IsDefined(T) metoda

Określa, czy podana wartość jest członkiem typu wyliczeniowego **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T | Wartość do sprawdzenia |

### Wartość zwracana

Prawda, jeśli **value** jest członkiem wyliczenia **T**, w przeciwnym razie - fałsz

## Enum::IsDefined(const String\&) metoda

Określa, czy wartość o podanej nazwie znajduje się wśród członków wyliczenia **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../string/)\& | Nazwa do sprawdzenia |

### Wartość zwracana

Prawda, jeśli istnieje członek wyliczenia **E** o podanej nazwie.

## Zobacz także

* Typedef [UnderlyingType](../underlyingtype/)
* Klasa [String](../../string/)
* Struktura [Enum](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)