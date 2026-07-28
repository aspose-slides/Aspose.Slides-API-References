---
title: operator=()
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 92
url: /hu/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) metódus




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) metódus


Széttöri az objektumot ebbe az értéktupába.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Az objektum, amelyet szét kell bontani |

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [ValueTuple](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)