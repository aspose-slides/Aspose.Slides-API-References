---
title: operator=()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 92
url: /id/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) metode




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) metode


Mendeconstruct objek menjadi tuple nilai ini.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Objek yang akan dideconstruct |

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Class [ValueTuple](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)