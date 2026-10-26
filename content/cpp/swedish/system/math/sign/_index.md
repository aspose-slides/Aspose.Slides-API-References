---
title: Sign()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer tecknet för det angivna signerade heltalsvärdet.
type: docs
weight: 274
url: /sv/system/math/sign/
---
## Math::Sign(T) metod


Bestämmer tecknet för det angivna signerade heltalsvärdet.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
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

## Math::Sign(T) metod


Bestämmer tecknet för det angivna flyttalsvärdet.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
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

## Math::Sign(const Decimal\&) metod


Bestämmer tecknet för det angivna decimalvärdet.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Värdet vars tecken ska bestämmas |

### Returvärde

- 1 om **value** är mindre än 0; 0 om **value** är lika med 0; 1 om **value** är större än 0

## Se även

* Klass [Decimal](../../decimal/)
* Struktur [Math](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)