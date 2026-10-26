---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah objek yang merepresentasikan nilai konstanta enumerasi dari tipe enumerasi yang ditentukan dengan nama yang ditentukan.
type: docs
weight: 27
url: /id/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) metode


Mengembalikan sebuah objek yang merepresentasikan nilai konstanta enumerasi dari tipe enumerasi yang ditentukan dengan nama yang ditentukan.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Objek [TypeInfo](../../typeinfo/) yang merepresentasikan tipe nilai enumerasi yang akan dikembalikan |
| str | const [String](../../string/)\& | Nama konstanta enum |
| ignoreCase | **bool** | Menentukan apakah huruf besar/kecil harus diabaikan saat menginterpretasikan nama konstanta enum |

### Nilai Kembalian

Sebuah objek yang merepresentasikan nilai dari konstanta enum yang namanya ditentukan dalam **str**.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Object](../../object/)
* Kelas [TypeInfo](../../typeinfo/)
* Kelas [String](../../string/)
* Kelas [EnumValuesBase](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)