---
title: StringBuilder
second_title: Справочник API Aspose.Slides для C++
description: "Буфер для поэтапного накопления строки. Этот тип может быть выделен либо в стеке как тип значения, либо в куче с помощью функции System::MakeObject(). После выделения объекта никогда не смешивайте эти два случая использования: наличие указателей SmartPtr на объекты, выделенные в стеке, строго запрещено."
type: docs
weight: 326
url: /ru/system.text/stringbuilder/
---
## StringBuilder класс

[Buffer](../../system/buffer/) для поэтапного накопления строк. Этот тип может быть выделен либо в стеке как тип значения, либо в куче с помощью функции [System::MakeObject()](../../system/makeobject/). После выделения объекта никогда не смешивайте эти два случая использования: наличие [SmartPtr](../../system/smartptr/) указателей на объекты, выделенные в стеке, строго запрещено.

```cpp
class StringBuilder : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Добавляет символ в builder. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Добавляет символы в builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Добавляет массив символов в builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Добавляет срез массива символов в builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Добавляет строку в builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Добавляет срез строки в builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Добавляет строковое представление объекта в builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Добавляет содержимое builder'а в builder. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Добавляет значение с плавающей точкой в builder. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Добавляет значение с плавающей точкой в builder. |
| [StringBuilder](./) * [Append](./append/)(int) | Добавляет целочисленное значение в builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Добавляет арифметическое значение в builder. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Добавляет строковое представление значения перечисления в builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Добавляет отформатированную строку в builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Добавляет отформатированную строку в builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Добавляет символ новой строки в builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Добавляет строку, за которой следует символ новой строки, в builder. |
| [StringBuilder](./) * [Clear](./clear/)() | Удаляет все символы из builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Копирует данные builder в существующие позиции массива. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Обеспечивает, чтобы ёмкость этого экземпляра [System.Text.StringBuilder](./) была не менее указанного значения. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| int [get_Capacity](./get_capacity/)() const | Возвращает текущую ёмкость строкового builder'а. |
| int [get_Length](./get_length/)() const | Возвращает длину строки, содержащейся в builder. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Возвращает символ в указанной позиции. |
| void [idx_set](./idx_set/)(int, char_t) | Устанавливает символ в указанной позиции. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Вставляет строку в фиксированную позицию builder'а. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Вставляет повторяющуюся строку в фиксированную позицию builder'а. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Вставляет символ в фиксированную позицию builder'а. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Вставляет символы в фиксированную позицию builder'а. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Вставляет значение в фиксированную позицию builder'а. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| char_t [operator[]](./operator[]/)(int) const | Возвращает символ в указанной позиции. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Удаляет фрагмент из builder'а. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Заменяет подстроку в builder'е. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Заменяет подстроку в диапазоне builder'а. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Заменяет символ в builder'е. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Заменяет символ в диапазоне builder'а. |
| void [set_Capacity](./set_capacity/)(int) | Устанавливает текущую ёмкость строкового builder'а. |
| void [set_Length](./set_length/)(int) | Обрезает или расширяет строковый builder до указанной длины. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Конструктор. |
|  [StringBuilder](./stringbuilder/)(int) | Конструктор. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Конструктор. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Конструктор. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Конструктор. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Возвращает строку, содержащуюся в данный момент в builder. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Возвращает подстроку, содержащуюся в данный момент в builder. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
|  [~StringBuilder](./~stringbuilder/)() | Деструктор. |
## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Text](../)
* Библиотека [Aspose.Slides](../../)