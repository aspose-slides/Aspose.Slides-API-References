---
title: OperatingSystem
second_title: "Referensi API Aspose.Slides untuk C++"
description: "Mewakili sistem operasi tertentu dan menyediakan informasi tentangnya. Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 1171
url: /id/system/operatingsystem/
---
## OperatingSystem kelas


Mewakili sistem operasi tertentu dan menyediakan informasi tentangnya. Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat instance dari tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class OperatingSystem
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Mengembalikan pengenal platform dari sistem operasi yang direpresentasikan oleh objek saat ini. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Mengembalikan nama service pack dari sistem operasi yang direpresentasikan oleh objek saat ini. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Mengembalikan referensi konstan ke objek [Version](../version/) yang merepresentasikan versi sistem operasi yang direpresentasikan oleh objek saat ini. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Mengembalikan representasi string dari versi sistem operasi yang direpresentasikan oleh objek saat ini. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Menunjukkan apakah aplikasi saat ini berjalan di FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Menunjukkan apakah aplikasi saat ini berjalan di Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Menunjukkan apakah aplikasi saat ini berjalan di MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Menunjukkan apakah aplikasi saat ini berjalan di platform yang ditentukan. |
| static **bool** [IsWindows](./iswindows/)() | Menunjukkan apakah aplikasi saat ini berjalan di [Windows](../../system.windows/). |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Membuat sebuah instance yang merepresentasikan sistem operasi yang ditentukan sebagai ID platform tertentu dan versi. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Membuat sebuah instance yang merepresentasikan sistem operasi yang ditentukan sebagai ID platform tertentu, versi, dan service pack. |
| [String](../string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari versi sistem operasi yang direpresentasikan oleh objek saat ini. |
## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)