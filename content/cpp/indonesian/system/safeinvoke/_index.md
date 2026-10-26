---
title: SafeInvoke()
second_title: Referensi API Aspose.Slides untuk C++
description: Implementasi terjemahan operator '?.'.
type: docs
weight: 2653
url: /id/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) fungsi


Implementasi terjemahan operator '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T0 | tipe ekspresi. |
| T1 | Tipe lambda yang membungkus ekspresi 'WhenTrue'. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expr | T0\&& | nilai ekspresi. |
| func | T1\&& | 'WhenTrue' ekspresi terikat ke funktor. |

### Nilai Kembali

Jika nilai expr tidak null, mengembalikan func yang dipanggil dengan nilainya sebagai argumen pertama, jika tidak mengembalikan null.

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)