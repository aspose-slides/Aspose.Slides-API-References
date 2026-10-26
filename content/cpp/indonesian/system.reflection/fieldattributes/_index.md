---
title: FieldAttributes
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut bidang yang terpantulkan.
type: docs
weight: 170
url: /id/system.reflection/fieldattributes/
---
## FieldAttributes enum


Atribut bidang yang terpantulkan.

```cpp
enum class FieldAttributes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| FieldAccessMask | 7 | Masker akses anggota. Gunakan masker ini untuk mengambil informasi aksesibilitas. |
| PrivateScope | 0 | Anggota yang tidak dapat dirujuk. |
| Private | 1 | Anggota privat. |
| FamANDAssem | 2 | Anggota privat dan berskala assembly. |
| Assembly | 3 | Anggota berskala assembly. |
| Family | 4 | Anggota yang dapat diakses oleh tipe dan subtipe. |
| FamORAssem | 5 | Anggota yang dapat diakses oleh tipe, subtipe, dan assembly. |
| Public | 6 | Anggota yang dapat diakses oleh siapa saja. |
| Static | 16 | Anggota statis sebagai lawan dari anggota instance. |
| InitOnly | 32 | Anggota konstan yang hanya dapat diinisialisasi tetapi tidak dapat diubah. |
| Literal | 64 | Anggota konstan waktu kompilasi. |
| NotSerialized | 128 | Anggota yang tidak diserialkan. |
| SpecialName | 512 | Bidang khusus dengan salah satu nama di bawah ini. |
| PinvokeImpl | 8192 | Implementasi interop yang diteruskan. |
| ReservedMask | 38144 | Flag yang disimpan untuk penggunaan runtime saja. |
| RTSpecialName | 1024 | Runtime harus memeriksa enkoding nama. |
| HasFieldMarshal | 4096 | Informasi marshalling ada. |
| HasDefault | 32768 | Nilai default ada. |
| HasFieldRVA | 256 | RVA ada. |

## Lihat Juga

* Ruang Nama [System::Reflection](../)
* Perpustakaan [Aspose.Slides](../../)