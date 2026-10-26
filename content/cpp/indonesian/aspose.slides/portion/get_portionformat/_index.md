---
title: get_PortionFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek pemformatan yang berisi properti pemformatan yang ditetapkan secara eksplisit pada bagian teks tanpa penerapan pewarisan. Hanya-baca IPortionFormat.
type: docs
weight: 1
url: /id/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() metode

Mengembalikan objek pemformatan yang berisi properti pemformatan yang ditetapkan secara eksplisit pada bagian teks tanpa menerapkan pewarisan. Hanya-baca [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Catatan

Objek pemformatan berisi parameter pemformatan yang didefinisikan hanya untuk bagian saat ini, data yang diwariskan tidak diterapkan.

Untuk mendapatkan nilai efektif termasuk yang diwariskan, gunakan metode [PortionFormat::GetEffective](../../portionformat/geteffective/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPortionFormat](../../iportionformat/)
* Kelas [Portion](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)