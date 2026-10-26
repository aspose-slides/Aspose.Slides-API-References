---
title: operator&=()
second_title: Aspose.Slides för C++ API-referens
description: Tillämpa operator&=() på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidigt argument.
type: docs
weight: 274
url: /sv/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) metod

Tillämpar [operator&=()](./) på värdet som representeras av det nuvarande objektet med det angivna värdet som ett högersidigt argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Mallparametern för att få SFINAE att fungera. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | **bool** | Ett booleskt värde som används som ett högersidigt värde av [operator&=()](./) som tillämpas på värdet som representeras av det nuvarande objektet. |

### Returvärde

En referens till sig själv.

## Se även

* Klass [Nullable](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)