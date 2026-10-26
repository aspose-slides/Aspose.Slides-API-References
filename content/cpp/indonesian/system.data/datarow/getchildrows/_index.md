---
title: GetChildRows()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan baris yang dianggap anak melalui relasi yang ditentukan.
type: docs
weight: 27
url: /id/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) metode

Mendapatkan baris yang dianggap sebagai anak melalui relasi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argument

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Objek relasi untuk menentukan hubungan baris induk - baris anak. |

## Nilai Kembalian

[Array](../../../system/array/) dari baris anak yang diambil.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [DataRow](../)
* Kelas [DataRelation](../../datarelation/)
* Ruang nama [System::Data](../../)
* Library [Aspose.Slides](../../../)