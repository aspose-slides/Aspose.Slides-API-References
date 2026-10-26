---
title: AddVideo()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan salinan file video dari presentasi lain.
type: docs
weight: 53
url: /id/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metode

Menambahkan salinan file video dari presentasi lain.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Video sumber. |

### Nilai Kembalian

Video ditambahkan.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metode

Membuat dan menambahkan video ke presentasi dari aliran.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran untuk menambahkan file video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Perilaku yang akan diterapkan pada aliran. |

### Nilai Kembalian

Ditambahkan [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metode

Membuat dan menambahkan video ke presentasi dari array byte.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) byte. |

### Nilai Kembalian

Video ditambahkan.

## Lihat Juga

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IVideo](../../ivideo/)
* Kelas [VideoCollection](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)