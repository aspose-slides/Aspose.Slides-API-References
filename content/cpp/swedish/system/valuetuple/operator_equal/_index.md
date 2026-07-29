---
title: operator=()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 92
url: /sv/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) metod




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) metod


Avkonstruerar objektet till detta värdetuple.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Ett objekt att avkonstrera |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [ValueTuple](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)