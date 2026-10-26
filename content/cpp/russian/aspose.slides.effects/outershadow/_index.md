---
title: OuterShadow
second_title: Справочник API Aspose.Slides для C++
description: Представляет эффект внешней тени.
type: docs
weight: 1041
url: /ru/aspose.slides.effects/outershadow/
---
## OuterShadow класс

Представляет эффект внешней тени.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Определяет, равен ли указанный [OuterShadow](./) текущему [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) радиус, в пунктах. Значение по умолчанию \u2013 0 pt. Чтение **double**. |
| **float** [get_Direction](./get_direction/)() override | Направление тени, в градусах. Значение по умолчанию \u2013 0 \u00B0 (слева направо). Чтение **float**. |
| **double** [get_Distance](./get_distance/)() override | Расстояние тени от объекта, в пунктах. Значение по умолчанию \u2013 0 pt. Чтение **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Только для чтения [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Выравнивание прямоугольника. Значение по умолчанию \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Чтение [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию \u2013 true. Чтение **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Коэффициент горизонтального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию \u2013 100 %. Чтение **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Коэффициент вертикального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию \u2013 100 %. Чтение **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Цвет тени. Значение по умолчанию \u2013 автоматический черный (зависит от темы). Только для чтения [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Горизонтальный угол наклона, в градусах. Значение по умолчанию \u2013 0 \u00B0. Чтение **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Вертикальный угол наклона, в градусах. Значение по умолчанию \u2013 0 \u00B0. Чтение **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Версия. Только для чтения **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные эффекта Outer Shadow с учётом наследования. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Служит в качестве хеш-функции для конкретного типа. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) радиус, в пунктах. Значение по умолчанию \u2013 0 pt. Запись **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Направление тени, в градусах. Значение по умолчанию \u2013 0 \u00B0 (слева направо). Запись **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Расстояние тени от объекта, в пунктах. Значение по умолчанию \u2013 0 pt. Запись **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Выравнивание прямоугольника. Значение по умолчанию \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Запись [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию \u2013 true. Запись **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Коэффициент горизонтального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию \u2013 100 %. Запись **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Коэффициент вертикального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию \u2013 100 %. Запись **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Горизонтальный угол наклона, в градусах. Значение по умолчанию \u2013 0 \u00B0. Запись **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Вертикальный угол наклона, в градусах. Значение по умолчанию \u2013 0 \u00B0. Запись **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IOuterShadow](../ioutershadow/)
* Класс [IVisualEffect](../ivisualeffect/)
* Класс [IPVIObject](../../aspose.slides/ipviobject/)
* Пространство имён [Aspose::Slides::Effects](../)
* Библиотека [Aspose.Slides](../../)