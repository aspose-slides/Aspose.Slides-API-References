---
title: operator=()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: 
type: docs
weight: 92
url: /cs/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) method




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) method


Rozbalí objekt do této hodnotové n-tice.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Objekt k rozbalení |

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [ValueTuple](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)