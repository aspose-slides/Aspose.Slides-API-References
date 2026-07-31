---
title: IsBoxable
second_title: Referensi API Aspose.Slides untuk C++
description: Predikat templat yang memeriksa apakah boxing dari tipe yang ditentukan didukung.
type: docs
weight: 1665
url: /id/system/isboxable/
---
## IsBoxable struct


Predikat templat yang memeriksa apakah boxing dari tipe yang ditentukan didukung.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang akan diperiksa |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)