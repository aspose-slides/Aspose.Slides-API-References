---
title: Func
second_title: Справочник API Aspose.Slides для C++
description: "Функция-делегат. Этот тип должен быть выделен в стеке и передаваться функциям по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 859
url: /ru/system/func/
---
## Func класс

Функция-делегат. Этот тип должен быть выделен в стеке и передаваться функциям по значению или по ссылке. Никогда не используйте [System::SmartPtr](../smartptr/) класс для управления объектами этого типа.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Args | Аргументы вызова, затем обязательный тип возвращаемого значения. |
## Методы

| Метод | Описание |
| --- | --- |
|  [Func](./func/)() | Конструктор по умолчанию, создающий null-Func. |
|  [Func](./func/)(T\&&) | Конструктор, который создает объект [Func](./) и присваивает ему значение (либо реальный колбэк, либо nullptr). |
|  [Func](./func/)(const [Func](./)\&) | Конструктор копирования. |
|  [Func](./func/)([Func](./)\&&) | Конструктор перемещения. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Присваивание копированием. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Присваивание перемещением. |
|  [~Func](./~func/)() | Деструктор. |
## Замечания



```cpp
#include "system/func.h"
#include <iostream>

// Эта функция принимает экземпляр делегата System::Func в качестве параметра.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Создаём экземпляр делегата System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Передайте созданный экземпляр в качестве аргумента функции.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Этот пример кода выводит следующее:
1
4
9
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)