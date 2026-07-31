---
title: set_RawFrame()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengatur properti kerangka bentuk mentah. Tulis IShapeFrame.
type: docs
weight: 53
url: /id/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metode


Mengatur properti kerangka bentuk mentah. Tulis [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Catatan


Kode yang mencoba menetapkan frame yang tidak terdefinisi ke [IShape::set_Frame](../../ishape/set_frame/) tidak masuk akal dalam kasus umum (khususnya dalam kasus ketika induk [GroupShape](../../groupshape/) berlapis secara berganda ke dalam GroupShape lainnya). Sebagai contoh: 
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
Kode semacam itu dapat menyebabkan situasi yang tidak jelas. Jadi batasan telah ditambahkan untuk penggunaan nilai yang tidak terdefinisi pada [IShape::set_Frame](../../ishape/set_frame/). Nilai x, y, width, height, flipH, flipV, dan rotationAngle harus didefinisikan (bukan std::numeric_limits<float>::quiet_NaN() atau [NullableBool::NotDefined](../../nullablebool/)). Contoh kode di atas sekarang melemparkan pengecualian ArgumentException. Ini berlaku untuk kasus penggunaan berikut: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // tidak boleh tidak terdefinisi

SharedPtr<IShapeCollection> shapes = ...;
// parameter x, y, width, height tidak boleh menjadi std::numeric_limits<float>::quiet_NaN():
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


Tetapi frame untuk metode [IShape::set_RawFrame](../../ishape/set_rawframe/) dapat tidak terdefinisi. Hal ini masuk akal ketika shape terhubung ke placeholder. Kemudian nilai frame shape yang tidak terdefinisi akan ditimpa dari shape placeholder induk. Jika tidak ada shape placeholder induk untuk shape tersebut, maka shape itu menggunakan nilai default ketika mengevaluasi frame efektif berdasarkan [IShape::get_RawFrame](../../ishape/get_rawframe/)-nya. Nilai default adalah 0 dan [NullableBool::False](../../nullablebool/) untuk x, y, width, height, flipH, flipV, dan rotationAngle. Sebagai contoh: 
```cpp
SharedPtr<IShape> shape = ...; // shape terhubung ke placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // sekarang shape mewarisi nilai x, y, height, flipH, flipV dari placeholder dan menimpa width=100 dan rotationAngle=0.
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)