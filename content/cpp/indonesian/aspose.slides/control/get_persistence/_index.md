---
title: get_Persistence()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan metode yang digunakan untuk menyimpan properti kontrol ActiveX. Hanya baca PersistenceType.
type: docs
weight: 1
url: /id/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() method

Mendapatkan metode yang digunakan untuk menyimpan properti kontrol ActiveX. Hanya baca [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Catatan

Contoh berikut menunjukkan penggunaan properti Persistence untuk memeriksa apakah properti objek ActiveX dapat diubah sebagai properti ActiveX berbasis XML: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Gunakan metode Anda sendiri untuk mengelola properti ActiveX yang disimpan dalam file biner-nya
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Lihat Juga

* Enum [PersistenceType](../../persistencetype/)
* Kelas [Control](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)