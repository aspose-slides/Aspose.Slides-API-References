---
title: GetDescription()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama konstanta enumerasi yang memiliki nilai yang ditentukan.
type: docs
weight: 53
url: /id/system/enum/getdescription/
---
## Enum::GetDescription(T) metode

Mengembalikan nama dari konstanta enumerasi yang memiliki nilai yang ditentukan.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai dari konstanta enum yang namanya akan dikembalikan |

### Nilai Kembali

Nama dari konstanta enum yang ditentukan

## Lihat Juga

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)