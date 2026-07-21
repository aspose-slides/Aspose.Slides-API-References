---
title: FontFallBackRule
second_title: Справочник API Aspose.Slides для C++
description: Представляет правило резервного шрифта
type: docs
weight: 937
url: /ru/aspose.slides/fontfallbackrule/
---
## FontFallBackRule класс

Represents font fallback rule

```cpp
class FontFallBackRule : public Aspose::Slides::IFontFallBackRule
```

## Методы

| Метод | Описание |
| --- | --- |
| void [AddFallBackFonts](./addfallbackfonts/)([System::String](../../system/string/)) override | Добавляет новые шрифты в список шрифтов FallBack. |
| void [AddFallBackFonts](./addfallbackfonts/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Добавляет новые шрифты в список шрифтов FallBack. |
| void [Clear](./clear/)() override | Удаляет все шрифты из списка. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::String](../../system/string/)) | Создаёт новый экземпляр. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Создаёт новый экземпляр. |
| **int32_t** [get_Count](./get_count/)() override | Возвращает количество шрифтов, фактически определённых для диапазона. Только для чтения **int32_t**. |
| **uint32_t** [get_RangeEndIndex](./get_rangeendindex/)() override | Получает последний индекс непрерывного диапазона Unicode. |
| **uint32_t** [get_RangeStartIndex](./get_rangestartindex/)() override | Получает первый индекс непрерывного диапазона Unicode. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) override | Возвращает имя шрифта по указанному индексу. Только для чтения [IFontFallBackRule](../ifontfallbackrule/). |
| **int32_t** [IndexOf](./indexof/)([System::String](../../system/string/)) override | Возвращает индекс указанного правила в коллекции. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| void [Remove](./remove/)([System::String](../../system/string/)) override | Удаляет первое вхождение конкретного шрифта FallBack из списка. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Удаляет шрифт FallBack по указанному индексу в списке. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_RangeEndIndex](./set_rangeendindex/)(**uint32_t**) | Получает последний индекс непрерывного диапазона Unicode. |
| void [set_RangeStartIndex](./set_rangestartindex/)(**uint32_t**) | Получает первый индекс непрерывного диапазона Unicode. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона в виде слабой указки (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)() override | Создаёт и возвращает массив со всеми шрифтами FallBack для этого правила. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | Создаёт и возвращает массив со всеми шрифтами FallBack из указанного диапазона в списке. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Class [IFontFallBackRule](../ifontfallbackrule/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)