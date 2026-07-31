---
title: get_RawFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan properti bingkai bentuk mentah. Baca IShapeFrame.
type: docs
weight: 40
url: /id/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() metode

Mengembalikan properti bingkai bentuk mentah. Baca [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Keterangan

Kode yang mencoba menetapkan bingkai yang tidak terdefinisi ke [IShape::set_Frame](../../ishape/set_frame/) tidak masuk akal dalam kasus umum (khususnya ketika induk [GroupShape](../../groupshape/) berlapis secara berulang ke dalam GroupShape-s). Sebagai contoh: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 atau 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Kode semacam itu dapat menyebabkan situasi yang tidak jelas. Jadi pembatasan telah ditambahkan untuk penggunaan nilai yang tidak terdefinisi pada [IShape::set_Frame](../../ishape/set_frame/). Nilai x, y, width, height, flipH, flipV, dan rotationAngle harus didefinisikan (bukan std::numeric_limits<float>::quiet_NaN() atau [NullableBool::NotDefined](../../nullablebool/)). Contoh kode di atas sekarang melempar pengecualian ArgumentException. Ini berlaku untuk kasus penggunaan berikut: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // tidak boleh tidak terdefinisi

SharedPtr<IShapeCollection> shapes = ...;
// parameter x, y, lebar, tinggi tidak boleh std::numeric_limits<float>::quiet_NaN():
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

Namun bingkai untuk metode [IShape::set_RawFrame](../../ishape/set_rawframe/) dapat tidak terdefinisi. Ini masuk akal ketika bentuk terhubung ke placeholder. Kemudian nilai bingkai bentuk yang tidak terdefinisi ditimpa dari bentuk placeholder induk. Jika tidak ada bentuk placeholder induk untuk bentuk tersebut, maka bentuk itu menggunakan nilai default saat mengevaluasi bingkai efektif berdasarkan [IShape::get_RawFrame](../../ishape/get_rawframe/). Nilai default adalah 0 dan [NullableBool::False](../../nullablebool/) untuk x, y, width, height, flipH, flipV, dan rotationAngle. Sebagai contoh: 
```cpp
SharedPtr<IShape> shape = ...; // shape terhubung ke placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // sekarang shape mewarisi nilai x, y, height, flipH, flipV dari placeholder dan menimpa lebar=100 serta rotationAngle=0.
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShapeFrame](../../ishapeframe/)
* Kelas [Shape](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)