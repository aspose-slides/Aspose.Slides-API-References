---
title: GetBasePlaceholder()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает базовую форму-заполнитель (форму из макета и/или главного слайда, из которой наследуется текущая форма).
type: docs
weight: 638
url: /ru/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() метод


Возвращает базовую форму-заполнитель (форма из макета и/или главного слайда, из которого наследуется текущая форма).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Примечания


Если текущая форма не наследуется, возвращается null.


```cpp
// получить все (master/layout/slide) анимированные эффекты заполнителя формы
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

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../../ishape/)
* Класс [Shape](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)