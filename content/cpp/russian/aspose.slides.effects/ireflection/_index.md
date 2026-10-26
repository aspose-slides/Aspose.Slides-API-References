---
title: IReflection
second_title: Справочник API Aspose.Slides для C++
description: Представляет эффект отражения.
type: docs
weight: 937
url: /ru/aspose.slides.effects/ireflection/
---
## IReflection класс

Представляет эффект отражения.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) радиус. Читать **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Направление отражения. Читать **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Расстояние отражения. Читать **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Указывает конечную позицию (по градиенту альфа) конечного альфа-значения (в процентах). Читать **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Прозрачность конечного отражения. (в процентах). Читать **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Указывает направление смещения отражения. (угол). Читать **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Выравнивание прямоугольника. Читать [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Указывает, должна ли отражение вращаться вместе с фигурой, если фигура вращается. Читать **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Указывает горизонтальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Читать **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Указывает вертикальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Читать **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Указывает горизонтальный угол сдвига. Читать **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Указывает вертикальный угол сдвига. Читать **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Указывает начальную позицию (по градиенту альфа) начального альфа-значения (в процентах). Читать **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Прозрачность начального отражения. (в процентах). Читать **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Получает эффективные данные с примененным наследованием. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или используется объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значений с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) радиус. Записать **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Направление отражения. Записать **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Расстояние отражения. Записать **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Указывает конечную позицию (по градиенту альфа) конечного альфа-значения (в процентах). Записать **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Прозрачность конечного отражения. (в процентах). Записать **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Указывает направление смещения отражения. (угол). Записать **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Выравнивание прямоугольника. Записать [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Указывает, должна ли отражение вращаться вместе с фигурой, если фигура вращается. Записать **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Указывает горизонтальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Записать **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Указывает вертикальный коэффициент масштабирования, отрицательное масштабирование приводит к отражению. (в процентах) Записать **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Указывает горизонтальный угол сдвига. Записать **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Указывает вертикальный угол сдвига. Записать **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Указывает начальную позицию (по градиенту альфа) начального альфа-значения (в процентах). Записать **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Прозрачность начального отражения. (в процентах). Записать **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Задает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или используется объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IImageTransformOperation](../iimagetransformoperation/)
* Класс [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Пространство имён [Aspose::Slides::Effects](../)
* Библиотека [Aspose.Slides](../../)