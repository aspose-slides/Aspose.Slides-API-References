---
title: IShapeStyle
second_title: Aspose.Slides для C++ справочник API
description: Представляет ссылку на стиль фигуры.
type: docs
weight: 3719
url: /ru/aspose.slides/ishapestyle/
---
## IShapeStyle класс

Представляет ссылку на стиль фигуры.

```cpp
class IShapeStyle : public virtual System::Object
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() | Возвращает цвет эффекта фигуры. Только для чтения [IColorFormat](../icolorformat/). |
| virtual **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() | Возвращает индекс столбца эффекта фигуры в матрице стилей. Чтение **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() | Возвращает цвет заливки фигуры. Только для чтения [IColorFormat](../icolorformat/). |
| virtual **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() | Возвращает индекс столбца заливки фигуры в матрицах стилей. 0 означает отсутствие заливки, положительное значение — индекс в стилях заливки темы, отрицательное значение — индекс в стилях фона темы. Чтение **int16_t**. |
| virtual [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() | Возвращает индекс шрифта фигуры в коллекции шрифтов. Чтение [Slides::FontCollectionIndex](../fontcollectionindex/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() | Возвращает цвет шрифта фигуры. Только для чтения [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() | Возвращает цвет контура фигуры. Только для чтения [IColorFormat](../icolorformat/). |
| virtual **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() | Возвращает индекс столбца линии в матрице стилей. Чтение **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| virtual void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) | Устанавливает индекс столбца эффекта фигуры в матрице стилей. Запись **uint32_t**. |
| virtual void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) | Устанавливает индекс столбца заливки фигуры в матрицах стилей. 0 означает отсутствие заливки, положительное значение — индекс в стилях заливки темы, отрицательное значение — индекс в стилях фона темы. Запись **int16_t**. |
| virtual void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) | Устанавливает индекс шрифта фигуры в коллекции шрифтов. Запись [Slides::FontCollectionIndex](../fontcollectionindex/). |
| virtual void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) | Устанавливает индекс столбца линии в матрице стилей. Запись **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)