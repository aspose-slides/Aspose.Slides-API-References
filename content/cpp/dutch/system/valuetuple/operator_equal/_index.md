---
title: operator=()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 92
url: /nl/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) methode




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) methode

Deconstrueert object naar deze value tuple.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Een object om te deconstrueren |

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [ValueTuple](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)