---
title: INormalViewProperties
second_title: Aspose.Slides для C++ API Reference
description: "Представляет свойства обычного представления. Обычное представление состоит из трех областей контента: самого слайда, боковой области контента и нижней области контента."
type: docs
weight: 2978
url: /ru/aspose.slides/inormalviewproperties/
---
## INormalViewProperties класс

Represent normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region.

```cpp
class INormalViewProperties : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() | Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. Горизонтальная разделительная полоса отделяет слайд от нижнего контентного региона. |
| virtual **bool** [get_PreferSingleView](./get_prefersingleview/)() | Указывает, предпочитает ли пользователь видеть одиночный контентный регион во весь экран вместо стандартного нормального представления с тремя контентными регионами. Если включено, приложение может выбрать отображать один из контентных регионов во всём окне. Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() | Этот элемент определяет размер бокового контентного региона нормального представления, когда регион имеет переменный восстановленный размер (не свернут и не развернут). Только чтение [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() | Этот элемент определяет размер верхнего слайд-региона нормального представления, когда регион имеет переменный восстановленный размер (не свернут и не развернут). Только чтение [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() | Указывает, должна ли приложение показывать значки при отображении содержания контуров в любых контентных регионах режима нормального просмотра. Чтение **bool**. |
| virtual **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() | Указывает, должна ли вертикальная разделительная полоса «прищёлкнуть» к свернутому состоянию, когда боковой регион достаточно мал. Чтение **bool**. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() | Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. Вертикальная разделительная полоса отделяет слайд от бокового контентного региона. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет конструировать копии подп классов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет конструировать копии подп классов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. Горизонтальная разделительная полоса отделяет слайд от нижнего контентного региона. |
| virtual void [set_PreferSingleView](./set_prefersingleview/)(**bool**) | Указывает, предпочитает ли пользователь видеть одиночный контентный регион во весь экран вместо стандартного нормального представления с тремя контентными регионами. Если включено, приложение может выбрать отображать один из контентных регионов во всём окне. Записать **bool**. |
| virtual void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) | Указывает, должна ли приложение показывать значки при отображении содержания контуров в любых контентных регионах режима нормального просмотра. Записать **bool**. |
| virtual void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) | Указывает, должна ли вертикальная разделительная полоса «прищёлкнуть» к свернутому состоянию, когда боковой регион достаточно мал. Записать **bool**. |
| virtual void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. Вертикальная разделительная полоса отделяет слайд от бокового контентного региона. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
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

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)