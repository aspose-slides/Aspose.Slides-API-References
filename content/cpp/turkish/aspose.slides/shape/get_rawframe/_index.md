---
title: get_RawFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Ham şekil çerçevesinin özelliklerini döndürür. IShapeFrame'i okuyun.
type: docs
weight: 40
url: /tr/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() yöntemi

Ham şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Açıklamalar

[IShape::set_Frame](../../ishape/set_frame/)'ye tanımsız çerçeve atamaya çalışan kod, genel durumda mantıklı değildir (özellikle ebeveyn [GroupShape](../../groupshape/) diğer GroupShape-s içinde çoklu iç içe geçtiğinde). Örneğin: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
veya 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
Böyle kodlar belirsiz durumlara yol açabilir. Bu nedenle [IShape::set_Frame](../../ishape/set_frame/) için tanımsız değerlerin kullanılmasına yönelik kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerleri tanımlı olmalıdır (std::numeric_limits<float>::quiet_NaN() veya [NullableBool::NotDefined](../../nullablebool/) olmamalıdır). Yukarıdaki örnek kod artık ArgumentException istisnası atar. Bu, aşağıdaki kullanım durumları için geçerlidir: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // tanımsız olamaz

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height parametreleri std::numeric_limits<float>::quiet_NaN() olamaz:
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

[IShape::set_RawFrame](../../ishape/set_rawframe/) yöntemi için bir çerçeve tanımsız olabilir. Bu, şekil bir yer tutucuya bağlandığında mantıklı olur. Bu durumda tanımsız şekil çerçevesi değerleri, üst yer tutucu şekilden geçersiz kılınır. Eğer o şekil için üst yer tutucu şekil yoksa, şekil [IShape::get_RawFrame](../../ishape/get_rawframe/)'ına dayanarak etkili çerçeveyi değerlendirirken varsayılan değerleri kullanır. x, y, width, height, flipH, flipV ve rotationAngle için varsayılan değerler 0 ve [NullableBool::False](../../nullablebool/)'dir. Örneğin: 
```cpp
SharedPtr<IShape> shape = ...; // shape yer tutucuya bağlanmıştır
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // şimdi shape, x, y, height, flipH, flipV değerlerini yer tutucudan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShapeFrame](../../ishapeframe/)
* Sınıf [Shape](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)