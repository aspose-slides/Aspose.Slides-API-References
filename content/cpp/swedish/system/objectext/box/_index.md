---
title: Box()
second_title: Aspose.Slides för C++ API-referens
description: Packar värdetyper för konvertering till Object. Implementering för uppräkningstyper.
type: docs
weight: 40
url: /sv/system/objectext/box/
---
## ObjectExt::Box(const T&) metod

Packar värdetyper för konvertering till [Object](../../object/). Implementering för uppräkningstyper.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) värde att packa. |

### Returvärde

Smartpekare till objekt som behåller det inkapslade värdet.

## ObjectExt::Box(const T&) metod

Packar värdetyper för konvertering till [Object](../../object/). Implementering för icke-uppräkningstyper.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | Värde att packa. |

### Returvärde

Smartpekare till objekt som behåller det inkapslade värdet.

## ObjectExt::Box(const T&) metod

Packar [Nullable](../../nullable/) typer för konvertering till [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | Värde att packa. |

### Returvärde

Smartpekare till objekt som behåller det inkapslade värdet.

## ObjectExt::Box(const String&) metod

Packar strängvärden.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Värde att packa. |

### Returvärde

Inkapslat värde eller null, om källsträngen är null.

## Se även

* Klass [SmartPtr](../../smartptr/)
* Klass [Object](../../object/)
* Klass [ObjectExt](../)
* Klass [String](../../string/)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)