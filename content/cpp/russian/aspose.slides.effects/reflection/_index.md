---
title: Reflection
second_title: Справочник API Aspose.Slides для C++
description: Представляет эффект отражения.
type: docs
weight: 1067
url: /ru/aspose.slides.effects/reflection/
---
## Класс Reflection

Представляет [Reflection](./) эффект.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Определяет, равен ли указанный [Reflection](./) текущему [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) радиус. Чтение **double**. |
| **float** [get_Direction](./get_direction/)() override | Направление отражения. Чтение **float**. |
| **double** [get_Distance](./get_distance/)() override | Расстояние отражения. Чтение **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Указывает конечную позицию (по альфа-градиентной лестнице) конечного альфа-значения (в процентах). Чтение **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Прозрачность конечного отражения. (в процентах). Чтение **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Указывает направление смещения отражения. (угол). Чтение **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Только для чтения [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Выравнивание прямоугольника. Чтение [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Указывает, должно ли отражение вращаться вместе с фигурой, если фигура вращается. Чтение **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Указывает горизонтальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Чтение **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Указывает вертикальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Чтение **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Указывает горизонтальный угол наклона. Чтение **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Указывает вертикальный угол наклона. Чтение **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Указывает начальную позицию (по альфа-градиентной лестнице) начального альфа-значения (в процентах). Чтение **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Прозрачность начального отражения. (в процентах). Чтение **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Версия. Только для чтения **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные эффекта [Reflection](./) с примененным наследованием. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Служит хэш-функцией для конкретного типа. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) радиус. Запись **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Направление отражения. Запись **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Расстояние отражения. Запись **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Указывает конечную позицию (по альфа-градиентной лестнице) конечного альфа-значения (в процентах). Запись **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Прозрачность конечного отражения. (в процентах). Запись **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Указывает направление смещения отражения. (угол). Запись **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Выравнивание прямоугольника. Запись [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Указывает, должно ли отражение вращаться вместе с фигурой, если фигура вращается. Запись **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Указывает горизонтальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Запись **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Указывает вертикальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Запись **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Указывает горизонтальный угол наклона. Запись **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Указывает вертикальный угол наклона. Запись **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Указывает начальную позицию (по альфа-градиентной лестнице) начального альфа-значения (в процентах). Запись **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Прозрачность начального отражения. (в процентах). Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IReflection](../ireflection/)
* Класс [IVisualEffect](../ivisualeffect/)
* Класс [IPVIObject](../../aspose.slides/ipviobject/)
* Пространство имён [Aspose::Slides::Effects](../)
* Библиотека [Aspose.Slides](../../)