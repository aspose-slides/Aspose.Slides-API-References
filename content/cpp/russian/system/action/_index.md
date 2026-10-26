---
title: Action
second_title: Справочник API Aspose.Slides для C++
description: Тип делегата, который ссылается на методы, не возвращающие значение.
type: docs
weight: 3563
url: /ru/system/action/
---
## Action typedef


Тип делегата, который ссылается на методы, не возвращающие значение.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Примечания



```cpp
#include <system/action.h>

using namespace System;

// Функция, которая выводит переданную строку.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Создать экземпляр Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Вызвать действие.
  action(u"Hello, world!");

  return 0;
}
/*
Этот пример кода выводит следующее:
Привет, мир!
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)