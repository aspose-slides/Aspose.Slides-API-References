---
title: InsertOleObjectFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat frame objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.
type: docs
weight: 79
url: /id/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metode

Membuat frame objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol di mana OLE object frame akan disisipkan. |
| x | **float** | Koordinat x dari frame OLE baru, dalam poin. |
| y | **float** | Koordinat y dari frame OLE baru, dalam poin. |
| width | **float** | Lebar frame OLE baru, dalam poin. |
| height | **float** | Tinggi frame OLE baru, dalam poin. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informasi data OLE yang tersemat ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Nilai Kembalian

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metode

Membuat frame objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol di mana OLE object frame akan disisipkan. |
| x | **float** | Koordinat x dari frame OLE baru, dalam poin. |
| y | **float** | Koordinat y dari frame OLE baru, dalam poin. |
| width | **float** | Lebar frame OLE baru, dalam poin. |
| height | **float** | Tinggi frame OLE baru, dalam poin. |
| className | [System::String](../../../system/string/) | Nama kelas dari objek OLE. |
| path | [System::String](../../../system/string/) | Path ke file yang ditautkan. |

### Nilai Kembalian

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## Keterangan

Path ini disimpan persis dalam presentasi. Jika path relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOleObjectFrame](../../ioleobjectframe/)
* Kelas [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Kelas [IShapeCollection](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)