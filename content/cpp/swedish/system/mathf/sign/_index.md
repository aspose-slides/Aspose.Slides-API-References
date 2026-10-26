---
title: Sign()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer tecknet för det angivna signerade heltalvärdet.
type: docs
weight: 274
url: /sv/system/mathf/sign/
---
## MathF::Sign(T) metod


Bestämmer tecknet på det angivna signerade heltalvärdet.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Den signerade heltalstypen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T | Värdet vars tecken ska bestämmas |

### Returvärde

- 1 om **value** är mindre än 0; 0 om **value** är lika med 0; 1 om **value** är större än 0

## MathF::Sign(T) metod


Bestämmer tecknet på det angivna flyttalvärdet.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Flyttalstypen för argumentet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T | Värdet vars tecken ska bestämmas |

### Returvärde

- 1 om **value** är mindre än 0; 0 om **value** är lika med 0; 1 om **value** är större än 0

## Se även

* Struktur [MathF](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)