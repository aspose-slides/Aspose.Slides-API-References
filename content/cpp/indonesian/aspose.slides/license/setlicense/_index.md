---
title: SetLicense()
second_title: Aspose.Slides untuk Referensi API C++
description: Memberi lisensi pada komponen.
type: docs
weight: 14
url: /id/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metode


Memberi lisensi pada komponen.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Dapat berupa nama file lengkap atau singkat atau nama sumber daya tersemat. Gunakan string kosong untuk beralih ke mode evaluasi. |
## Catatan



Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder assembly komponen.

3. Folder assembly pemanggil klien.

4. Folder assembly entri.

5. Sumber daya tersemat di assembly pemanggil klien.

**Catatan:**Pada .NET Compact Framework, mencoba menemukan lisensi hanya di lokasi berikut:

1. Jalur eksplisit.

2. Sumber daya tersemat di assembly pemanggil klien.

Dalam contoh ini, akan dicoba mencari file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metode


Memberi lisensi pada komponen.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran yang berisi lisensi. |
## Catatan



Gunakan metode ini untuk memuat lisensi dari aliran.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [License](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)