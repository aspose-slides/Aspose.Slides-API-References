---
title: CompareInfo
second_title: Aspose.Slides для C++ API Reference
description: "Осуществляет сравнение строк с учётом культуры. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 40
url: /ru/system.globalization/compareinfo/
---
## CompareInfo класс

Выполняет сравнение строк с учётом культуры. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CompareInfo : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Сравнивает строки. Не реализовано. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Сравнивает строки. Поддерживаются только режимы Ordinal и OrdinalIgnoreCase. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Сравнивает участок одной строки с участком второй строки. Не реализовано. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Сравнивает конечный участок одной строки с конечным участком второй строки, используя методы сравнения строк. Не реализовано. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Сравнивает конечный участок одной строки с конечным участком второй строки. Не реализовано. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Сравнивает участок одной строки с участком второй строки, используя методы сравнения строк. Не реализовано. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | Информация RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| int [get_LCID](./get_lcid/)() const | Возвращает LCID культуры, ассоциированной с компаратором. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Возвращает название культуры, ассоциированной с компаратором. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Возвращает информацию о версии сортировки. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Возвращает [CompareInfo](./), связанную с указанной культурой и использующую методы сравнения строк в указанной сборке. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Возвращает [CompareInfo](./), связанную с указанной культурой и использующую методы сравнения строк в указанной сборке. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Возвращает [CompareInfo](./), связанную с указанной культурой. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Возвращает [CompareInfo](./), связанную с указанной культурой. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, связанную с объектом. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Возвращает хэш-код строки на основе указанных параметров сравнения. |
| int [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Возвращает объект [SortKey](../sortkey/) для указанной строки, используя заданные параметры сравнения. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Возвращает объект [SortKey](../sortkey/) для указанной строки. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Ищет подстроку. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Ищет подстроку. Поддерживается только режим Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Ищет подстроку. Поддерживается только режим Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Ищет указанный символ. Поддерживается только режим Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Ищет подстроку. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Ищет указанный символ. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Ищет подстроку. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Ищет указанный символ. Поддерживается только режим Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Ищет указанный символ. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Ищет указанный символ. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Ищет подстроку. Поддерживается только режим Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Ищет указанный символ. Поддерживается только режим Ordinal. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Проверяет, начинается ли указанная строка с указанного префикса, используя заданные параметры сравнения. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Проверяет, начинается ли указанная строка с указанного префикса. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Проверяет, является ли указанный символ сортируемым. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Проверяет, является ли указанная строка сортируемой. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Проверяет, заканчивается ли указанная строка указанным суффиксом, используя заданные параметры сравнения. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Проверяет, заканчивается ли указанная строка указанным суффиксом. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Ищет последнее вхождение указанной подстроки. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Ищет последнее вхождение указанной подстроки, используя заданные параметры сравнения. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Ищет последнее вхождение указанного символа, используя заданные параметры сравнения. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Ищет последнее вхождение указанной строки. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Ищет последнее вхождение указанной строки, используя заданные параметры сравнения. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Ищет последнее вхождение указанного символа, используя заданные параметры сравнения. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Ищет последнее вхождение указанной строки. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Ищет последнее вхождение указанного символа. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Ищет последнее вхождение указанной строки, используя заданные параметры сравнения. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Ищет последнее вхождение указанного символа, используя заданные параметры сравнения. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Ищет последнее вхождение указанного символа. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Ищет последнее вхождение указанного символа. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона в слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [System::Globalization](../)
* Библиотека [Aspose.Slides](../../)