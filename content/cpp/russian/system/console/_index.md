---
title: Console
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет методы для вывода данных в стандартный поток вывода. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры любыми способами.
type: docs
weight: 196
url: /ru/system/console/
---
## Console класс

Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Console
```

## Методы

| Метод | Описание |
| --- | --- |
| static void [Beep](./beep/)() | НЕ РЕАЛИЗОВАНО. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Возвращает shared pointer, указывающий на объект, представляющий стандартный поток ошибок. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Возвращает shared pointer, указывающий на объект, представляющий стандартный поток ввода. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Возвращает shared pointer, указывающий на объект, представляющий стандартный поток вывода. |
| static void [Mute](./mute/)(**bool**) | Приглушает или восстанавливает звук стандартного потока вывода. |
| static void [ReadKey](./readkey/)() | НЕ РЕАЛИЗОВАНО. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Устанавливает заголовок окна консоли. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Назначает указанный объект свойству Error класса. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Устанавливает свойство In указанным объектом TextReader. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Назначает указанный объект свойству Out класса. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Выводит строковое представление указанного объекта в поток стандартного вывода. |
| static void [Write](./write/)(**bool**) | Выводит строковое представление логического значения в поток стандартного вывода. |
| static void [Write](./write/)(char_t) | Выводит указанное символьное значение в поток стандартного вывода. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Выводит строковое представление указанного массива символов в поток стандартного вывода. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Выводит строковое представление значения [Decimal](../decimal/) в поток стандартного вывода. |
| static void [Write](./write/)(**double**) | Выводит строковое представление значения double-precision floating-point в поток стандартного вывода. |
| static void [Write](./write/)(**float**) | Выводит строковое представление значения single-precision floating-point в поток стандартного вывода. |
| static void [Write](./write/)(**int32_t**) | Выводит строковое представление 32-битного целого значения в поток стандартного вывода. |
| static void [Write](./write/)(**int64_t**) | Выводит строковое представление 64-битного целого значения в поток стандартного вывода. |
| static void [Write](./write/)(const [String](../string/)\&) | Выводит указанный объект строки в поток стандартного вывода. |
| static void [Write](./write/)(const char_t *) | Выводит указанную C-строку в поток стандартного вывода. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Выводит строковое представление значения [TypeInfo](../typeinfo/) в поток стандартного вывода. |
| static void [Write](./write/)(**uint32_t**) | Выводит строковое представление беззнакового 32-битного целого значения в поток стандартного вывода. |
| static void [Write](./write/)(**uint64_t**) | Выводит строковое представление беззнакового 64-битного целого значения в поток стандартного вывода. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Выводит строковое представление указанного диапазона указанного массива символов в поток стандартного вывода. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Выводит строковое представление указанных аргументов, отформатированных согласно указанному формату, в поток стандартного вывода. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Выводит текущий разделитель строк в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Выводит строковое представление указанного объекта, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**bool**) | Выводит строковое представление логического значения, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(char_t) | Выводит указанное символьное значение, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Выводит строковое представление указанного массива символов, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Выводит строковое представление значения [Decimal](../decimal/), за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**double**) | Выводит строковое представление значения double-precision floating-point, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**float**) | Выводит строковое представление значения single-precision floating-point, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**int32_t**) | Выводит строковое представление 32-битного целого значения, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**int64_t**) | Выводит строковое представление 64-битного целого значения, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Выводит указанный объект строки, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const char_t *) | Выводит указанную C-строку, за которой следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Выводит строковое представление значения [TypeInfo](../typeinfo/), за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Выводит строковое представление беззнакового 32-битного целого значения, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Выводит строковое представление беззнакового 64-битного целого значения, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Выводит строковое представление указанного диапазона указанного массива символов, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Выводит строковое представление указанного объекта Exception, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Выводит строковое представление указанных аргументов, отформатированных согласно указанному формату, за которым следует текущий разделитель строк, в поток стандартного вывода. |
| static void [WriteLine](./writeline/)(const char *) |  |
## Примечания

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Выводит приветственное сообщение.
  Console::WriteLine(u"Hello, world!");

  // Создаёт экземпляр класса 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Выводит элементы массива.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Этот пример кода выводит следующее:
Hello, world!
1 2 3 4 5
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)