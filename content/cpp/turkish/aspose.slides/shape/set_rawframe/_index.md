---
title: set_RawFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Ham şekil çerçevesinin özelliklerini ayarlar. IShapeFrame yazın.
type: docs
weight: 53
url: /tr/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metodu

Ham şekil çerçevesinin özelliklerini ayarlar. [IShapeFrame](../../ishapeframe/) yazın.

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Açıklamalar

Tanımsız çerçeveyi [IShape::set_Frame](../../ishape/set_frame/)'ye atamaya çalışan kod genel durumda (özellikle üst [GroupShape](../../groupshape/) başka GroupShape'ların içinde birden fazla iç içe olduğunda) mantıksızdır. Örneğin:
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
Bu tür kod belirsiz durumlara yol açabilir. Bu nedenle [IShape::set_Frame](../../ishape/set_frame/) için tanımsız değerlerin kullanımı üzerine kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerleri tanımlı olmalıdır (std::numeric_limits<float>::quiet_NaN() ya da [NullableBool::NotDefined](../../nullablebool/) olmamalıdır). Yukarıdaki örnek kod artık ArgumentException hatası atar. Bu, aşağıdaki kullanım durumları için geçerlidir:
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

Ancak [IShape::set_RawFrame](../../ishape/set_rawframe/) metodunun çerçevesi tanımsız olabilir. Bu, şeklin bir yer tutucuya bağlı olduğu durumlarda mantıklıdır. Daha sonra tanımsız şekil çerçevesi değerleri üst yer tutucu şekilden geçersiz kılınır. Eğer o şekil için üst yer tutucu şekil yoksa, şekil [IShape::get_RawFrame](../../ishape/get_rawframe/) temelinde etkili çerçeveyi değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve [NullableBool::False](../../nullablebool/)'dir. Örneğin:
```cpp
SharedPtr<IShape> shape = ...; // shape yer tutucuya bağlıdır
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // şimdi shape x, y, height, flipH, flipV değerlerini placeholder'dan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShapeFrame](../../ishapeframe/)
* Sınıf [Shape](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)