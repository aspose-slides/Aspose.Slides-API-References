---
title: AddOleObjectFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 66
url: /id/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metode

Membuat sebuah bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | **float** | Lebar bingkai OLE baru, dalam poin. |
| height | **float** | Tinggi bingkai OLE baru, dalam poin. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informasi data OLE tersemat ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Nilai Kembali

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metode

Membuat sebuah bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | **float** | Lebar bingkai OLE baru, dalam poin. |
| height | **float** | Tinggi bingkai OLE baru, dalam poin. |
| className | [System::String](../../../system/string/) | Nama kelas dari objek OLE. |
| path | [System::String](../../../system/string/) | Jalur ke file yang ditautkan. |

### Nilai Kembali

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## Catatan

Jalur ini disimpan persis dalam presentasi. Jika jalur relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOleObjectFrame](../../ioleobjectframe/)
* Kelas [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Kelas [IShapeCollection](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)