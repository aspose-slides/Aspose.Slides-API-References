---
title: LastIndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer index för den sista förekomsten av det angivna elementet i ett intervall av element i arrayen som specificeras av startindexet och antalet element i intervallet.
type: docs
weight: 703
url: /sv/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metod

Bestämmer index för den sista förekomsten av det angivna elementet i ett intervall av element i arrayen som specificeras av startindexet och antalet element i intervallet.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av elementet att söka efter i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) för att söka det specificerade elementet i |
| value | const [ValueType](../valuetype/)\& | Index för elementet vars position ska bestämmas |
| startIndex | int | [Index](../../index/) vid vilken sökningen startas |
| count | int | Antal element i intervallet att söka i |

### Returvärde

[Index](../../index/) för den sista förekomsten av det specificerade elementet om elementet hittas, annars -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metod

Bestämmer index för den sista förekomsten av det angivna elementet i arrayen med start från det angivna indexet.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av elementet att söka efter i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) för att söka det specificerade elementet i |
| value | const [ValueType](../valuetype/)\& | Index för elementet vars position ska bestämmas |
| startIndex | int | [Index](../../index/) vid vilken sökningen startas |

### Returvärde

[Index](../../index/) för den sista förekomsten av det specificerade elementet om elementet hittas, annars -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metod

Bestämmer index för den sista förekomsten av det angivna elementet i arrayen.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av elementet att söka efter i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) för att söka det specificerade elementet i |
| value | const [ValueType](../valuetype/)\& | Index för elementet vars position ska bestämmas |

### Returvärde

[Index](../../index/) för den sista förekomsten av det specificerade elementet om elementet hittas, annars -1

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)