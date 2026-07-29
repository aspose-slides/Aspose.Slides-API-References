---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer indexet för den första förekomsten av det specificerade objektet i arrayen.
type: docs
weight: 131
url: /sv/system/array/indexof/
---
## Array::IndexOf(const T\&) const metod


Bestämmer indexet för den första förekomsten av det specificerade objektet i arrayen.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Index för det objekt som ska bestämmas |

### Returvärde

[Index](../../index/) av den första förekomsten av det specificerade objektet om objektet hittas, annars -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metod


Bestämmer indexet för den första förekomsten av det specificerade objektet i arrayen.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av objektet att söka efter i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) för att söka efter det specificerade objektet i |
| value | const [ValueType](../valuetype/)\& | Index för det objekt som ska bestämmas |

### Returvärde

[Index](../../index/) av den första förekomsten av det specificerade objektet om objektet hittas, annars -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metod


Bestämmer indexet för den första förekomsten av det specificerade objektet i arrayen med början från det angivna indexet.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av objektet att söka efter i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) för att söka efter det specificerade objektet i |
| value | const [ValueType](../valuetype/)\& | Index för det objekt som ska bestämmas |
| startIndex | int | [Index](../../index/) vid vilken sökningen startas |

### Returvärde

[Index](../../index/) av den första förekomsten av det specificerade objektet om objektet hittas, annars -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metod


Bestämmer indexet för den första förekomsten av det specificerade objektet i ett intervall av objekt i arrayen som specificeras av startindexet och antalet element i intervallet.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av objektet att söka efter i arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) för att söka efter det specificerade objektet i |
| value | const [ValueType](../valuetype/)\& | Index för det objekt som ska bestämmas |
| startIndex | int | [Index](../../index/) vid vilken sökningen startas |
| count | int | Antal element i intervallet att söka i |

### Returvärde

[Index](../../index/) av den första förekomsten av det specificerade objektet om objektet hittas, annars -1

## Se också

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)