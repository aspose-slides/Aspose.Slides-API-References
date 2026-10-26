---
title: With()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkloning rekaman referensi dan menerapkan funktor inisialisasi padanya.
type: docs
weight: 2614
url: /id/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) function

Mengkloning rekaman referensi dan menerapkan funktor inisialisasi padanya.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe rekaman untuk dikloning. |
| A | Tipe funktor inisialisasi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Pointer bersama ke objek yang akan dikloning dan diinisialisasi. |
| initializer | const A\& | Funktor inisialisasi yang diterapkan pada klon rekaman. |

### Nilai Kembalian

Pointer bersama ke rekaman yang dikloning.

## System::With(const T\&, const A\&) function

Menyalin rekaman struct dan menerapkan funktor inisialisasi padanya.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe rekaman untuk disalin. |
| A | Tipe funktor inisialisasi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| record | const T\& | Rekaman untuk disalin dan diinisialisasi. |
| initializer | const A\& | Funktor inisialisasi yang diterapkan pada salinan rekaman. |

### Nilai Kembalian

Rekaman yang disalin.

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)