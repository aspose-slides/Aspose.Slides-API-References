---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer likheten för det angivna värdet med hjälp av operator==().
type: docs
weight: 66
url: /sv/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) funktion

Bestämmer likheten för det angivna värdet med hjälp av [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Den | typ av värdena som jämförs |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value1 | T | Den första jämförelsetermen |
| value2 | T | Den andra jämförelsetermen |

### Returvärde

Sant om det angivna värdet är lika enligt [operator==()](../../system/operator_equal_equal/), annars - falskt

## System::BoxedValueDetail::Equals(T, T) funktion

Bestämmer likheten för det angivna värdet med hjälp av metod [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Den | typ av värdena som jämförs |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value1 | T | Den första jämförelsetermen |
| value2 | T | Den andra jämförelsetermen |

### Returvärde

Sant om det angivna värdet är lika enligt metod [Equals()](./), annars - falskt

## Se även

* Namnrymd [System::BoxedValueDetail](../)
* Bibliotek [Aspose.Slides](../../)