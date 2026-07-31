---
title: StringFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru dari kelas StringFormat.
type: docs
weight: 1
url: /id/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() konstruktor


Membuat instance baru dari kelas [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) konstruktor


Membuat instance baru dari kelas [StringFormat](../) dengan flag format yang ditentukan dan bahasa.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Kombinasi bitwise dari nilai enum StringFormatFlags yang menentukan format string yang akan direpresentasikan oleh objek yang dibuat |
| language | **int32_t** | Bahasa teks |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) konstruktor


Konstruktor penyalinan.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Objek [StringFormat](../) untuk disalin dari |

## Lihat Juga

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [StringFormat](../)
* RuangNama [System::Drawing](../../)
* Perpustakaan [Aspose.Slides](../../../)