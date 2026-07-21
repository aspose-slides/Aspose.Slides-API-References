---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает эффективные данные 3-D форматирования с применённым наследованием.
type: docs
weight: 183
url: /ru/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() метод


Получает эффективные данные 3-D форматирования с применённым наследованием.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### Возвращаемое значение

Объект [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## Примечания



Этот пример демонстрирует, как получить эффективные свойства камеры, световой установки и верхней фаски формы. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Класс [ThreeDFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)