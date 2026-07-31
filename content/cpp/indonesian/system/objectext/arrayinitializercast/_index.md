---
title: ArrayInitializerCast()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai fundamental array (yang dilakukan secara implisit oleh C# tetapi tampaknya tidak dilakukan oleh C++).
type: docs
weight: 209
url: /id/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metode

Mengonversi nilai fundamental array (yang dilakukan secara implisit oleh C# tetapi tampaknya tidak dilakukan oleh C++).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| To | Tipe target. |
| From | Tipe sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | From ... | Nilai untuk dikonversi dan dimasukkan ke array target. |

### Nilai Kembali

[Array](../../array/) yang berisi salinan yang telah dikonversi dari semua argumen dalam urutan yang sama.

## Lihat Juga

* Kelas [ObjectExt](../)
* Ruang nama [System](../../)
* Pustaka [Aspose.Slides](../../../)