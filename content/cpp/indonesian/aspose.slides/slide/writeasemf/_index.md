---
title: WriteAsEmf()
second_title: Referensi API Aspose.Slides for C++
description: Menyimpan konten slide sebagai file EMF.
type: docs
weight: 170
url: /id/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metode


Menyimpan konten slide sebagai file EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran target |
## Keterangan



Contoh kode berikut menunjukkan cara mengonversi slide pertama dari presentasi PowerPoint menjadi metafile. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Menyimpan slide pertama sebagai metafile
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [Slide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)