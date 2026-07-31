---
title: GetName()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama konstanta enumerasi yang memiliki nilai tertentu.
type: docs
weight: 40
url: /id/system/enum/getname/
---
## Enum::GetName(T) metode

Mengembalikan nama konstanta enumerasi yang memiliki nilai tertentu.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai konstanta enum yang namanya akan dikembalikan |

### Nilai Kembalian

Nama konstanta enum yang ditentukan

## Lihat Juga

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)