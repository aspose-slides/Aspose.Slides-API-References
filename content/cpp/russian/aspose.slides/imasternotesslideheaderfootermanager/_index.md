---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides для C++ справочник API
description: Представляет менеджер, который определяет поведение заменителей нижнего колонтитула, даты-времени и номера страницы главного слайда заметок, а также всех вложенных заменителей. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок.
type: docs
weight: 2900
url: /ru/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager класс

Представляет менеджер, который определяет поведение заменителей нижнего колонтитула, даты-времени и номера страницы главного слайда заметок, а также всех вложенных заменителей. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Получает значение, указывающее, что заменитель даты-времени присутствует. Чтение**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Получает значение, указывающее, что заменитель нижнего колонтитула присутствует. Чтение **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | Получает значение, указывающее, что заменитель заголовка присутствует. Чтение **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Получает значение, указывающее, что заменитель номера страницы присутствует. Чтение**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Устанавливает текст в заменитель даты-времени главного слайда заметок и во все вложенные заменители даты-времени. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Изменяет видимость заменителя даты-времени главного слайда заметок и всех вложенных заменителей даты-времени. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Устанавливает текст в заменитель даты-времени слайда. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Изменяет видимость заменителя даты-времени слайда. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Устанавливает текст в заменитель нижнего колонтитула главного слайда заметок и во все вложенные заменители нижнего колонтитула. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Изменяет видимость заменителя нижнего колонтитула главного слайда заметок и всех вложенных заменителей нижнего колонтитула. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Устанавливает текст в заменитель нижнего колонтитула слайда. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Изменяет видимость заменителя нижнего колонтитула слайда. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | Устанавливает текст в заменитель заголовка главного слайда заметок и во все вложенные заменители заголовка. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | Изменяет видимость заменителя заголовка главного слайда заметок и всех вложенных заменителей заголовка. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | Устанавливает текст в заменитель заголовка слайда. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | Изменяет видимость заменителя заголовка слайда. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Изменяет видимость заменителя номера страницы главного слайда заметок и всех вложенных заменителей номеров страниц. Вложенные заменители означают, что заменители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от главного слайда заметок. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Изменяет видимость заменителя номера страницы слайда. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в виде слабого указателя (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)