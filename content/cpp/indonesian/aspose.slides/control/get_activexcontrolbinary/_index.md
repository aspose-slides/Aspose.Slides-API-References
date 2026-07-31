---
title: get_ActiveXControlBinary()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan keberlanjutan kontrol ActiveX ketika metode yang digunakan untuk menyimpan adalah PersistStream, PersistStreamInit, atau PersistStorage.
type: docs
weight: 118
url: /id/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() metode

Menentukan keberlanjutan kontrol ActiveX ketika metode yang digunakan untuk menyimpan adalah PersistStream, PersistStreamInit, atau PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Keterangan

Contoh berikut menunjukkan penggunaan properti ActiveXControlBinary untuk mengubah properti ActiveX:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Gunakan metode Anda sendiri untuk mengelola properti ActiveX yang disimpan dalam file biner
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Control](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)