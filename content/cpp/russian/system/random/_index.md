---
title: Random
second_title: Справочник API Aspose.Slides для C++
description: "Представляет генератор псевдослучайных чисел. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Нельзя создавать экземпляр этого типа в стеке или используя оператор new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 1171
url: /ru/system/random/
---
## Random класс

Represents a pseudo-random number generator. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Random : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **bool** [IsNull](./isnull/)() const | Всегда возвращает false. |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| virtual **int32_t** [Next](./next/)() | Возвращает неотрицательное случайное число, меньше максимального значения int32. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | Возвращает неотрицательное случайное число, меньше указанного максимума. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | Возвращает случайное число в указанном диапазоне. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Заполняет элементы указанного массива байтов случайными числами. |
| virtual **double** [NextDouble](./nextdouble/)() | Возвращает случайное число в диапазоне от 0.0 до 1.0. |
|  [Object](../object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструировать подклассы. |
|  [Random](./random/)() | Инициализирует новый экземпляр, используя зависящее от времени значение семени по умолчанию. |
|  [Random](./random/)(**int32_t**) | Инициализирует новый экземпляр класса [System.Random](./), используя указанное значение семени. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-th шаблонный аргумент как слабый указатель (вместо общего). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Аналог метода C# [Object.ToString()](../object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Реализует конструкцию C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Получить случайный номер месяца и вывести его.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Заполнить массив случайными числами.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Вывести массив.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
Этот пример кода выводит следующее:
Месяц: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## Смотрите также

* Класс [Object](../object/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)