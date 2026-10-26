---
title: Object
second_title: Aspose.Slides для C++ справочник API
description: Базовый класс, позволяющий использовать методы, доступные для класса System.Object в C#. Все нетривиальные классы, используемые в трансляционной среде, должны наследовать его.
type: docs
weight: 1119
url: /ru/system/object/
---
## Object класс

Базовый класс, позволяющий использовать методы, доступные для класса [System.Object](./) в C#. Все нетривиальные классы, используемые в трансляционной среде, должны наследовать его.

```cpp
class Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Получает структуру счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](./gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](./lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте страж-объект [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](./memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](./object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](./object/)([Object](./) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](./referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](./referenceequals/) для случая строк. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона в слабый указатель (вместо общего). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](./sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Аналог метода C# [Object.ToString()](./tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Реализует конструкцию C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте страж-объект [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](./~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [ptr](./ptr/) | Псевдоним для типа умного указателя. |

## Примечания

Вместе с методами, доступными в классе C# [System.Object](./), он также обеспечивает поддержку некоторых концепций, специфичных для среды транслированного кода. Это включает подсчет ссылок, используемый классами умных указателей ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) и другие сервисы, связанные с управлением памятью, отладкой и т.д.

Каждый [Object](./) имеет два счетчика ссылок: счетчик общих ссылок и счетчик слабых ссылок. Счетчик слабых ссылок всегда хранится в отдельной структуре данных, а не в самом [Object](./), что позволяет слабым указателям пережить объект. Счетчик умных ссылок хранится либо в самом объекте, либо в той же отдельной структуре, в зависимости от состояния макроса ENABLE_EXTERNAL_REFCOUNT. По умолчанию он включен в отладочных сборках и отключен в релизных. Если счетчик умного указателя хранится в самом объекте, отдельная структура данных создаётся только при наличии слабых указателей на объект. В противном случае она создаётся вместе с объектом.

Все умные указатели используют эти два счетчика ссылок и принадлежат одной и той же группе владения.

Если подкласс [Object](./) создаётся в стеке, к нему нельзя создавать умные указатели, иначе возникает проблема удаления со стека.

Этот тип может быть выделен либо в стеке как тип-значение, либо в куче с помощью функции [System::MakeObject()](../makeobject/). После выделения объекта никогда не смешивайте эти два варианта использования: наличие [SmartPtr](../smartptr/) указателей на объекты, выделенные в стеке, строго запрещено.

## См. также

* Namespace [System](../)
* Library [Aspose.Slides](../../)