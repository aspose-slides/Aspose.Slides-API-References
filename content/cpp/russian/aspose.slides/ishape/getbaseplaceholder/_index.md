---
title: GetBasePlaceholder()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает базовую заполнительную форму (форма из макета и/или главного слайда, от которой наследуется текущая форма).
type: docs
weight: 573
url: /ru/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() метод

Возвращает базовую заполнительную форму (форма из макета и/или главного слайда, от которой наследуется текущая форма).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Примечания


Возвращается null, если текущая форма не наследована.

```cpp
// получить все (master/layout/slide) анимированные эффекты заполнительной формы
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)