---
title: AdjustableArrowCap
second_title: Aspose.Slides для C++ API Reference
description: "Представляет регулируемую стрелкуобразную заглушку линии. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 1
url: /ru/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap класс

Представляет регулируемую стрелкуобразную заглушку линии. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа на стеке или с помощью оператора new, так как это приведет к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## Методы

| Метод | Описание |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | Создает новый экземпляр [AdjustableArrowCap](./) с указанной шириной и высотой. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | Возвращает копию текущего объекта. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | Создает новый экземпляр класса [CustomLineCap](../customlinecap/), представляющего пользовательскую заглушку линии с указанными свойствами. |
| void [Dispose](../customlinecap/dispose/)() | Освобождает все ресурсы операционной системы, полученные текущим объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | Возвращает базовую заглушку линии, из которой создана эта пользовательская заглушка. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | Возвращает расстояние между линией и заглушкой. |
| **bool** [get_Filled](./get_filled/)() const | Возвращает значение, указывающее, заполнена ли стрелка, представляемая текущим объектом. |
| **float** [get_Height](./get_height/)() const | Возвращает высоту стрелки, представляемой текущим объектом. |
| **float** [get_MiddleInset](./get_middleinset/)() const | Устанавливает расстояние между линией и заглушкой, представляемой текущим объектом. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | Возвращает значение LineJoin, определяющее способ соединения линий этой пользовательской заглушки. |
| **float** [get_Width](./get_width/)() const | Возвращает ширину стрелки, представляемой текущим объектом. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | Возвращает масштаб этой пользовательской заглушки. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | Получает начальную и конечную заглушки линии пользовательской заглушки, представляемой текущим объектом. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | Устанавливает значение базовой заглушки линии для этой пользовательской заглушки. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | Устанавливает расстояние между линией и заглушкой. |
| void [set_Filled](./set_filled/)(**bool**) | Устанавливает значение, указывающее, заполнена ли стрелка, представляемая текущим объектом. |
| void [set_Height](./set_height/)(**float**) | Устанавливает высоту стрелки, представляемой текущим объектом. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | Устанавливает расстояние между линией и заглушкой, представляемой текущим объектом. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | Устанавливает значение LineJoin, определяющее способ соединения линий этой пользовательской заглушки. |
| void [set_Width](./set_width/)(**float**) | Устанавливает ширину стрелки, представляемой текущим объектом. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | Устанавливает значение масштаба этой пользовательской заглушки. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | Устанавливает начальную и конечную заглушки линии пользовательской заглушки, представляемой текущим объектом. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [CustomLineCap](../customlinecap/)
* Пространство имён [System::Drawing::Drawing2D](../)
* Библиотека [Aspose.Slides](../../)