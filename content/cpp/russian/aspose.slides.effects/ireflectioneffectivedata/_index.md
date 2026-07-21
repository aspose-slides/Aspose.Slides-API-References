---
title: IReflectionEffectiveData
second_title: Справочник API Aspose.Slides для C++
description: Неизменяемый объект, представляющий эффект отражения.
type: docs
weight: 950
url: /ru/aspose.slides.effects/ireflectioneffectivedata/
---
## IReflectionEffectiveData класс


Неизменяемый объект, представляющий эффект [Reflection](../reflection/).

```cpp
class IReflectionEffectiveData : public virtual Aspose::Slides::Effects::IEffectEffectiveData
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) радиус. Только для чтения **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Направление отражения. Только для чтения **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Расстояние отражения. Только для чтения **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Задает конечную позицию (по градиенту альфа) конечного значения альфа (в процентах). Только для чтения **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Прозрачность конечного отражения (в процентах). Только для чтения **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Задает направление смещения отражения (угол). Только для чтения **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Выравнивание прямоугольника. Только для чтения [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Указывает, должно ли отражение вращаться вместе с фигурой при её вращении. Только для чтения **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Указывает горизонтальный коэффициент масштабирования, отрицательное значение вызывает отражение. (в процентах) Только для чтения **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Указывает вертикальный коэффициент масштабирования, отрицательное значение вызывает отражение. (в процентах) Только для чтения **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Указывает горизонтальный угол наклона. Только для чтения **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Указывает вертикальный угол наклона. Только для чтения **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Задает начальную позицию (по градиенту альфа) начального значения альфа (в процентах). Только для чтения **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Прозрачность начального отражения (в процентах). Только для чтения **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет использовать хеширование пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект экземпляром типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует поведение оператора C# `lock()`. Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. По-настоящему ничего не копирует, лишь инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. По-настоящему ничего не копирует, лишь инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку C# `lock()`. Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [IEffectEffectiveData](../ieffecteffectivedata/)
* Пространство имён [Aspose::Slides::Effects](../)
* Библиотека [Aspose.Slides](../../)