---
title: SetLicense()
second_title: Referensi API Aspose.Slides untuk C++
description: Memberi lisensi pada komponen.
type: docs
weight: 1
url: /id/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metode


Memberi lisensi pada komponen.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Dapat berupa nama file lengkap atau pendek atau nama sumber daya tersemat. Gunakan string kosong untuk beralih ke mode evaluasi. |
## Keterangan



Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.
2. Folder dari assembly komponen.
3. Folder dari assembly pemanggil klien.
4. Folder dari entry assembly.
5. Sumber daya tersemat di assembly pemanggil klien.

**Catatan:** Pada .NET Compact Framework, mencoba menemukan lisensi hanya di lokasi berikut:

1. Jalur eksplisit.
2. Sumber daya tersemat di assembly pemanggil klien.

Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder entry assembly, dan kemudian di sumber daya tersemat dari assembly pemanggil.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metode


Memberi lisensi pada komponen.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran yang berisi lisensi. |
## Keterangan



Gunakan metode ini untuk memuat lisensi dari aliran.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [ILicense](../)
* Kelas [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)