---
title: BoxedEnum
second_title: Справочник API Aspose.Slides для C++
description: "Представляет упакованное значение перечисления. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 92
url: /ru/system/boxedenum/
---
## Класс BoxedEnum

Представляет упакованное значение перечисления. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| E | Тип значения перечисления |
| UT | Базовый тип перечисления **E** |

## Методы

| Метод | Описание |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | Создаёт экземпляр, представляющий указанное значение перечисления. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | Возвращает значение, представляющее тип упакованного значения, представленного текущим объектом. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Преобразует значение упакованной константы перечисления в 64-битное целое значение. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Определяет, представляет ли текущий объект упакованное значение типа enum. |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонирование пользовательских типов. |
|  [Object](../object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать построение подклассов. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать построение подклассов. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Упаковывает значение константы перечисления указанного перечисления с заданным именем. Параметр указывает, следует ли игнорировать регистр при интерпретации строки, задающей имя константы перечисления. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Упаковывает значение константы перечисления указанного перечисления с заданным именем. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не совместный). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)() const override | Преобразует упакованное значение, представленное текущим объектом, в строку. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Преобразует упакованный объект в строку, используя указанную строку формата. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Реализует конструкцию C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [BoxedValue](../boxedvalue/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)