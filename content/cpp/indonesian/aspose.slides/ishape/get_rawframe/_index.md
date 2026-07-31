---
title: get_RawFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan properti bingkai bentuk mentah. Baca IShapeFrame.
type: docs
weight: 40
url: /id/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metode

Mengembalikan properti bingkai bentuk mentah. Baca [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Catatan

Kode yang mencoba menetapkan bingkai yang tidak terdefinisi ke [IShape::set_Frame](../set_frame/) tidak masuk akal dalam kasus umum (khususnya ketika induk [GroupShape](../../groupshape/) berada dalam beberapa tingkat bersarang ke GroupShape lain). Misalnya: 
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
 Kode semacam itu dapat menyebabkan situasi yang tidak jelas. Oleh karena itu pembatasan telah ditambahkan untuk penggunaan nilai yang tidak terdefinisi pada [IShape::set_Frame](../set_frame/). Nilai x, y, width, height, flipH, flipV, dan rotationAngle harus didefinisikan (bukan std::numeric_limits<float>::quiet_NaN() atau [NullableBool::NotDefined](../../nullablebool/)). Kode contoh di atas kini melempar pengecualian ArgumentException. Ini berlaku untuk kasus penggunaan berikut: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // tidak boleh tidak terdefinisi

SharedPtr<IShapeCollection> shapes = ...;
// parameter x, y, width, height tidak boleh std::numeric_limits<float>::quiet_NaN():
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

Namun bingkai untuk metode [IShape::set_RawFrame](../set_rawframe/) dapat tidak terdefinisi. Hal ini masuk akal ketika bentuk terhubung ke placeholder. Kemudian nilai bingkai bentuk yang tidak terdefinisi akan ditimpa dari bentuk placeholder induk. Jika tidak ada bentuk placeholder induk untuk bentuk tersebut, maka bentuk itu akan menggunakan nilai default ketika mengevaluasi bingkai efektif berdasarkan [IShape::get_RawFrame](./). Nilai default adalah 0 dan [NullableBool::False](../../nullablebool/) untuk x, y, width, height, flipH, flipV, dan rotationAngle. Misalnya: 
```cpp
SharedPtr<IShape> shape = ...; // shape terhubung ke placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // sekarang shape mewarisi nilai x, y, height, flipH, flipV dari placeholder dan mengganti width=100 serta rotationAngle=0.
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShapeFrame](../../ishapeframe/)
* Kelas [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)