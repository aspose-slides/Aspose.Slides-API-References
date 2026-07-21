---
title: Predicate
second_title: Справка API Aspose.Slides для C++
description: Представляет указатель на предикат — вызываемый объект, который принимает один аргумент и возвращает значение типа bool.
type: docs
weight: 4148
url: /ru/system/predicate/
---
## typedef предиката


Представляет указатель на предикат — вызываемый объект, который принимает один аргумент и возвращает значение типа bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Примечания



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Заполняем массив.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Создаем предикат, который возвращает элемент массива, больший 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Находим первый элемент массива с помощью созданного предиката и выводим его.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Этот пример кода выводит следующее:
5
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)