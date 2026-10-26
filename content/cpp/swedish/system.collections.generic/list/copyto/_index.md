---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar listans element till befintliga arrayelement.
type: docs
weight: 209
url: /sv/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metod

Kopierar listans element till befintliga arrayelement.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Målarray. |
| arrayIndex | int | Startindex för målarray. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metod

Kopierar alla element till befintliga arrayelement.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) för att kopiera element till. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metod

Kopierar element som börjar från det angivna indexet till befintliga arrayelement.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Ett nollbaserat index för elementet i listan som representeras av det aktuella objektet, varifrån kopieringen ska börja. |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) för att kopiera element till. |
| arrayIndex | int | Startposition i målarray. |
| count | int | Antal element att kopiera. |

## Se även

* Typdef [ArrayPtr](../../../system/arrayptr/)
* Klass [List](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)