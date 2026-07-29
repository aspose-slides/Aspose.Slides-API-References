---
title: UnknownIsNull()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett objekt av okänd typ är nullptr. Överlagring för icke-skalära typer.
type: docs
weight: 144
url: /sv/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metod

Kontrollerar om ett objekt av okänd typ är nullptr. Överlagring för icke-skalära typer.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | [Object](../../object/) att kontrollera. |

### Returvärde

Sant om 'obj == nullptr' är sant, annars falskt.

## ObjectExt::UnknownIsNull(T) metod

Kontrollerar om ett objekt av okänd typ är nullptr. Överlagring för skalära typer.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | [Object](../../object/) att kontrollera. |

### Returvärde

Returnerar alltid falskt.

## Se också

* Klass [ObjectExt](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)