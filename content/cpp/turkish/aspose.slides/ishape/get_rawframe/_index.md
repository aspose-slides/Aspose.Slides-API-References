---
title: get_RawFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Ham şekil çerçevesinin özelliklerini döndürür. IShapeFrame'i okuyun.
type: docs
weight: 40
url: /tr/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metodu


Ham şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Açıklamalar


Tanımsız çerçeveyi [IShape::set_Frame](../set_frame/)'ye atamaya çalışan kod, genel durumda mantıklı değildir (özellikle ebeveyn [GroupShape](../../groupshape/) birden fazla diğer GroupShape içine iç içe geçtiğinde). Örneğin: 
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
 Böyle kodlar belirsiz durumlara yol açabilir. Bu yüzden [IShape::set_Frame](../set_frame/) için tanımsız değerlerin kullanımına kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerlerinin tanımlı olması gerekir (std::numeric_limits<float>::quiet_NaN() ya da [NullableBool::NotDefined](../../nullablebool/) olmamalıdır). Yukarıdaki örnek kod artık ArgumentException istisnası fırlatır. Bu durum aşağıdaki kullanım senaryolarına uygulanır: 
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


Ancak [IShape::set_RawFrame](../set_rawframe/) metodunun çerçevesi tanımsız olabilir. Bu, şeklin bir yer tutucuya bağlı olduğunda mantıklıdır. Ardından tanımsız şekil çerçevesi değerleri ebeveyn yer tutucu şekilden geçersiz kılınır. Eğer o şekil için ebeveyn yer tutucu şekil yoksa, şekil [IShape::get_RawFrame](./)'ye dayalı etkili çerçeveyi değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve [NullableBool::False](../../nullablebool/)'dir. Örneğin: 
```cpp
SharedPtr<IShape> shape = ...; // şekil yer tutucuya bağlanmıştır
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // şimdi şekil x, y, height, flipH, flipV değerlerini yer tutucudan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShapeFrame](../../ishapeframe/)
* Sınıf [IShape](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)