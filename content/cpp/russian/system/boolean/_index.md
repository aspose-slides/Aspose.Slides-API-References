---
title: Boolean
second_title: Справочник API Aspose.Slides для C++
description: Класс, который хранит статические члены типа System.Boolean .Net.
type: docs
weight: 79
url: /ru/system/boolean/
---
## Класс Boolean

Класс, который хранит статические члены типа [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Методы

| Метод | Описание |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку в значение типа bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Преобразует указанную строку в значение типа bool. |
## Поля

| Поле | Описание |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) представление логического значения 'false'. |
| static [TrueString](./truestring/) | [String](../string/) представление логического значения 'true'. |
## Замечания



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Создайте переменную boolean.
  bool isWeekend = false;

  // Разберите входную строку и выведите результат.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Этот пример кода выводит следующее:
Is weekend: Yes
*/
```

## См. также

* Простейство имён [System](../)
* Библиотека [Aspose.Slides](../../)