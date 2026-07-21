---
title: MotionEffect
second_title: Справочник API Aspose.Slides для C++
description: Представляет поведение эффекта движения.
type: docs
weight: 469
url: /ru/aspose.slides.animation/motioneffect/
---
## MotionEffect класс

Represent motion effect behavior of effect.

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типов значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Отображает, являются ли анимационные поведения накопленными. Чтение [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Отображает, объединяется ли текущее анимационное поведение с другими запущенными анимациями. Чтение [BehaviorAdditiveType](../behavioradditivetype/). |
| **float** [get_Angle](./get_angle/)() override | Описывает относительный угол траектории движения. Чтение **float**. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | Описывает относительное значение смещения для анимации (в процентах). Чтение [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | Указывает координату x/y, от которой начинается анимация (в процентах). Чтение [System::Drawing::PointF](../../system.drawing/pointf/). |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | Указывает, относительно чего находится исходная точка траектории движения, например макета слайда или родителя. Чтение [MotionOriginType](../motionorigintype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | Указывает примитив пути, за которым следуют координаты для анимационного движения. Чтение [IMotionPath](../imotionpath/). |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | Указывает, как перемещается траектория движения при перемещении фигуры. Чтение [MotionPathEditMode](../motionpatheditmode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Отображает свойства поведения. Только чтение [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | Описывает центр вращения, используемый для поворота траектории движения на угол X. Чтение [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Отображает свойства синхронизации для поведения эффекта. Чтение [ITiming](../itiming/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | Указывает целевое местоположение для анимационного эффекта движения (в процентах). Чтение [System::Drawing::PointF](../../system.drawing/pointf/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Отображает, являются ли анимационные поведения накопленными. Запись [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Отображает, объединяется ли текущее анимационное поведение с другими запущенными анимациями. Запись [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_Angle](./set_angle/)(**float**) override | Описывает относительный угол траектории движения. Запись **float**. |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Описывает относительное значение смещения для анимации (в процентах). Запись [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Указывает координату x/y, от которой начинается анимация (в процентах). Запись [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родитель. Запись [MotionOriginType](../motionorigintype/). |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | Указывает примитив пути, за которым следуют координаты для анимационного движения. Запись [IMotionPath](../imotionpath/). |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | Указывает, как перемещается траектория движения при перемещении фигуры. Запись [MotionPathEditMode](../motionpatheditmode/). |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Описывает центр вращения, используемый для поворота траектории движения на угол X. Запись [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Отображает свойства синхронизации для поведения эффекта. Запись [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Указывает целевое местоположение для анимационного эффекта движения (в процентах). Запись [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Behavior](../behavior/)
* Класс [IMotionEffect](../imotioneffect/)
* Пространство имён [Aspose::Slides::Animation](../)
* Библиотека [Aspose.Slides](../../)