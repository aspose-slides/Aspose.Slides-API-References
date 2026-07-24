---
title: set_RawFrame()
second_title: Aspose.Slides C++ API Referansı
description: Raw shape frame'in özelliklerini ayarlar. IShapeFrame yazın.
type: docs
weight: 53
url: /tr/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) yöntem

Raw shape frame'in özelliklerini belirler. [IShapeFrame](../../ishapeframe/) yazın.

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Açıklamalar

Tanımsız çerçeveyi [IShape::set_Frame](../set_frame/)'ye atamaya çalışan kod, genel durumda (özellikle ebeveyn [GroupShape](../../groupshape/) başka GroupShape'lerin içinde birden çok kez iç içe olduğunda) mantıklı değildir. Örneğin: 
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
 Bu tür kodlar belirsiz durumlara yol açabilir. Bu nedenle [IShape::set_Frame](../set_frame/) için tanımsız değerlerin kullanılması üzerine kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerleri tanımlanmış olmalıdır (std::numeric_limits<float>::quiet_NaN() veya [NullableBool::NotDefined](../../nullablebool/) olmamalıdır). Yukarıdaki örnek kod şimdi ArgumentException istisnası fırlatır. Bu, aşağıdaki kullanım durumları için geçerlidir: 
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

Ancak [IShape::set_RawFrame](./) yöntemi için çerçeve tanımsız olabilir. Bu, şekil bir yer tutucuya bağlı olduğunda mantıklıdır. Bu durumda tanımsız şekil çerçevesi değerleri, ebeveyn yer tutucu şekilden geçersiz kılınır. Eğer o şekil için ebeveyn yer tutucu şekil yoksa, şekil [IShape::get_RawFrame](../get_rawframe/)'ine dayanarak etkili çerçeveyi değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve [NullableBool::False](../../nullablebool/)'dır. Örneğin: 
```cpp
SharedPtr<IShape> shape = ...; // şekil yer tutucuya bağlanmış
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // şimdi şekil x, y, height, flipH, flipV değerlerini yer tutucudan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShapeFrame](../../ishapeframe/)
* Sınıf [IShape](../)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)