---
title: MasterNotesSlideHeaderFooterManager
second_title: Справочная документация API Aspose.Slides для C++
description: Представляет менеджер, который управляет поведением нижнего колонтитула слайда заметок мастера, заполнителями даты и времени, номеров страниц и всех дочерних заполнителей. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.
type: docs
weight: 4460
url: /ru/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager класс


Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Возвращает значение, указывающее, что заполнитель даты и времени присутствует. Чтение**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Возвращает значение, указывающее, что заполнитель нижнего колонтитула присутствует. Чтение **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | Возвращает значение, указывающее, что заполнитель верхнего колонтитула присутствует. Чтение **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Возвращает значение, указывающее, что заполнитель номера страницы присутствует. Чтение**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Устанавливает текст в заполнитель даты и времени мастер-слайда и во все дочерние заполнитель даты и времени. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Изменяет видимость заполнителя даты и времени мастер-слайда и всех дочерних заполнителей даты и времени. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Устанавливает текст в заполнитель даты и времени слайда. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Изменяет видимость заполнителя даты и времени слайда. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Устанавливает текст в заполнитель нижнего колонтитула мастер-слайда и во все дочерние заполнители нижнего колонтитула. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Изменяет видимость заполнителя нижнего колонтитула мастер-слайда и всех дочерних заполнителей нижнего колонтитула. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Устанавливает текст в заполнитель нижнего колонтитула слайда. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Изменяет видимость заполнителя нижнего колонтитула слайда. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | Устанавливает текст в заполнитель верхнего колонтитула мастер-слида заметок и во все дочерние заполнители верхнего колонтитула. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | Изменяет видимость заполнителя верхнего колонтитула мастер-слида заметок и всех дочерних заполнителей верхнего колонтитула. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | Устанавливает текст в заполнитель верхнего колонтитула слайда. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | Изменяет видимость заполнителя верхнего колонтитула слайда. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Изменяет видимость заполнителя номера страницы мастер-слайда и всех дочерних заполнителей номеров страниц. Дочерние заполнители — это заполнители, содержащиеся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от мастер-слайда заметок. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Изменяет видимость заполнителя номера страницы слайда. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим слабого указателя. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* Класс [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)