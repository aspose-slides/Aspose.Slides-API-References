---
title: IsDefined()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om det angivna värdet är en medlem av uppräkningstyp E.
type: docs
weight: 27
url: /sv/system/enum/isdefined/
---
## Enum::IsDefined(E) metod

Bestämmer om det angivna värdet är en medlem av uppräkningstyp **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | E | Värdet att kontrollera |

### Returvärde

Sant om **value** är en medlem av uppräkning **E**, annars - falskt

## Enum::IsDefined(T) metod

Bestämmer om det angivna värdet är en medlem av uppräkningstyp **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T | Värdet att kontrollera |

### Returvärde

Sant om **value** är en medlem av uppräkning **T**, annars - falskt

## Enum::IsDefined(const String\&) metod

Bestämmer om värdet med det angivna namnet finns bland medlemmar i enum **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../string/)\& | Namnet att kontrollera |

### Returvärde

Sant om en medlem av enum **E** med det angivna namnet finns.

## Se även

* Typedef [UnderlyingType](../underlyingtype/)
* Klass [String](../../string/)
* Struktur [Enum](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)