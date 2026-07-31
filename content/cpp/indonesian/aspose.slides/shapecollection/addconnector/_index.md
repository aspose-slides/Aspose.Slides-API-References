---
title: AddConnector()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bentuk konektor baru dengan gaya templat default dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 417
url: /id/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) method

Membuat bentuk konektor baru dengan gaya templat default dan menambahkannya ke akhir koleksi bentuk.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk konektor yang akan ditambahkan. |
| x | **float** | Koordinat x dari bingkai konektor, dalam poin. |
| y | **float** | Koordinat y dari bingkai konektor, dalam poin. |
| width | **float** | Lebar bingkai konektor, dalam poin. |
| height | **float** | Tinggi bingkai konektor, dalam poin. |

### Nilai Kembali

[IConnector](../../iconnector/) yang baru dibuat.

## Catatan

Contoh berikut menunjukkan cara menambahkan konektor (konektor bengkok) antara dua bentuk (elips dan persegi panjang) di PowerPoint [Presentation](../../presentation/). 
```cpp
// Membuat instance kelas presentasi yang mewakili file PPTX
auto input = System::MakeObject<Presentation>();

// Mengakses koleksi bentuk untuk slide tertentu
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Menambahkan bentuk otomatis Ellipse
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Menambahkan bentuk otomatis Rectangle
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Menambahkan bentuk konektor ke koleksi bentuk slide
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Menghubungkan bentuk-bentuk menggunakan konektor
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Memanggil reroute yang menetapkan jalur terpendek otomatis antara bentuk-bentuk
connector->Reroute();

// Menyimpan presentasi
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method

Membuat bentuk konektor baru dan menambahkannya ke akhir koleksi bentuk, dengan opsi menerapkan gaya templat default.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk konektor yang akan dibuat. |
| x | **float** | Koordinat x dari bingkai konektor, dalam poin. |
| y | **float** | Koordinat y dari bingkai konektor, dalam poin. |
| width | **float** | Lebar bingkai konektor, dalam poin. |
| height | **float** | Tinggi bingkai konektor, dalam poin. |
| createFromTemplate | **bool** | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat konektor dengan nilai properti default. |

### Nilai Kembali

[IConnector](../../iconnector/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)