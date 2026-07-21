---
title: IOuterShadow
second_title: Справочник API Aspose.Slides для C++
description: Представляет эффект внешней тени.
type: docs
weight: 885
url: /ru/aspose.slides.effects/ioutershadow/
---
## IOuterShadow класс

Представляет эффект внешней тени.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) радиус в пунктах. Значение по умолчанию — 0 pt. Читать **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Направление тени в градусах. Значение по умолчанию — 0 ° (слева направо). Читать **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Расстояние тени от объекта в пунктах. Значение по умолчанию — 0 pt. Читать **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Выравнивание прямоугольника. Значение по умолчанию — [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Чтение [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию — true. Чтение **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Горизонтальный коэффициент масштабирования в процентах от оригинального размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Чтение **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Вертикальный коэффициент масштабирования в процентах от оригинального размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Чтение **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Цвет тени. Значение по умолчанию — автоматический черный (зависит от темы). Толькочтение [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Горизонтальный угол наклона в градусах. Значение по умолчанию — 0 °. Чтение **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Вертикальный угол наклона в градусах. Значение по умолчанию — 0 °. Чтение **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Получает эффективные данные с примененным наследованием. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) радиус в пунктах. Значение по умолчанию — 0 pt. Записать **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Направление тени в градусах. Значение по умолчанию — 0 ° (слева направо). Записать **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Расстояние тени от объекта в пунктах. Значение по умолчанию — 0 pt. Записать **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Выравнивание прямоугольника. Значение по умолчанию — [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Записать [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию — true. Записать **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Горизонтальный коэффициент масштабирования в процентах от оригинального размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Записать **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Вертикальный коэффициент масштабирования в процентах от оригинального размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Записать **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Горизонтальный угол наклона в градусах. Значение по умолчанию — 0 °. Записать **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Вертикальный угол наклона в градусах. Значение по умолчанию — 0 °. Записать **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IImageTransformOperation](../iimagetransformoperation/)
* Класс [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Пространство имён [Aspose::Slides::Effects](../)
* Библиотека [Aspose.Slides](../../)