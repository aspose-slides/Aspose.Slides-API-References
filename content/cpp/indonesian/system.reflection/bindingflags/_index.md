---
title: BindingFlags
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan anggota dan mode pencarian tipe serta pengikatan.
type: docs
weight: 157
url: /id/system.reflection/bindingflags/
---
## BindingFlags enum

Mendefinisikan anggota dan mode pencarian tipe serta pengikatan.

```cpp
enum class BindingFlags
```

### Values

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | 0 | Tidak ada opsi khusus. |
| IgnoreCase | 1 | Mengabaikan huruf besar/kecil nama saat mencari item. |
| DeclaredOnly | 2 | Hanya mencari anggota yang dideklarasikan dalam tipe dan bukan dalam tipe dasar. |
| Instance | 4 | Mencari melalui anggota instance. |
| Static | 8 | Mencari melalui anggota statis. |
| Public | 16 | Mencari melalui anggota publik. |
| NonPublic | 32 | Mencari melalui anggota non-publik. |
| FlattenHierarchy | 64 | Mencari melalui anggota statis publik dan protected pada tipe dasar. |
| InvokeMethod | 256 | Memanggil metode. |
| CreateInstance | 512 | Membuat instance tipe yang direfleksikan. |
| GetField | 1024 | Mendapatkan nilai field. |
| SetField | 2048 | Menetapkan nilai field. |
| GetProperty | 4096 | Mendapatkan nilai properti. |
| SetProperty | 8192 | Menetapkan nilai properti. |
| PutDispProperty | 16384 | Menetapkan properti COM. |
| PutRefDispProperty | 32768 | Menetapkan properti referensi COM. |
| ExactBinding | 65536 | Pengikatan tipe harus tepat, tanpa perubahan tipe apa pun. |
| SuppressChangeType | 131072 | Tidak didukung. |
| OptionalParamBinding | 262144 | Memilih overload berdasarkan jumlah argumen. |
| IgnoreReturn | 16777216 | Mengabaikan nilai kembali interop COM. |

## Lihat Juga

* Namespace [System::Reflection](../)
* Library [Aspose.Slides](../../)