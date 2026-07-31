---
title: AddOleObjectFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 183
url: /id/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam point. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam point. |
| width | **float** | Lebar bingkai OLE baru, dalam point. |
| height | **float** | Tinggi bingkai OLE baru, dalam point. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informasi tentang data OLE yang disematkan ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Nilai Kembali

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## Catatan

Contoh berikut menunjukkan cara menambahkan Bingkai Objek OLE ke [Slides](../../) PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Mengakses slide pertama
auto slide = pres->get_Slides()->idx_get(0);
// Muat file excel ke stream
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Membuat objek data untuk penyematan
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Menambahkan shape Bingkai Objek Ole
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//Menulis file PPTX ke disk
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam point. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam point. |
| width | **float** | Lebar bingkai OLE baru, dalam point. |
| height | **float** | Tinggi bingkai OLE baru, dalam point. |
| className | [System::String](../../../system/string/) | Nama kelas dari objek OLE. |
| path | [System::String](../../../system/string/) | Path ke file yang ditautkan. |

### Nilai Kembali

[IOleObjectFrame](../../ioleobjectframe/) yang baru dibuat.

## Catatan

Path ini disimpan persis dalam presentasi. Jika path relatif ditentukan, file akan tidak dapat diakses saat membuka presentasi dari direktori yang berbeda.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOleObjectFrame](../../ioleobjectframe/)
* Kelas [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Kelas [ShapeCollection](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)