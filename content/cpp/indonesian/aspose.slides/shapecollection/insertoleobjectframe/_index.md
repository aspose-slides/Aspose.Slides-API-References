---
title: InsertOleObjectFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 196
url: /id/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metode

Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the OLE object frame. |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | The embedded OLE data information ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Nilai Kembalian

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan cara menyisipkan objek OLE pada indeks kedua: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metode

Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the OLE object frame. |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| className | [System::String](../../../system/string/) | The class name of the OLE object. |
| path | [System::String](../../../system/string/) | The path to the linked file. |

### Nilai Kembalian

Bingkai objek OLE yang baru dibuat.

## Catatan

Path ini disimpan persis dalam presentasi. Jika path relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOleObjectFrame](../../ioleobjectframe/)
* Kelas [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Kelas [ShapeCollection](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)