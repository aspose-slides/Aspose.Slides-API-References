---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides для C++ справка API
description: "Представляет указатель на функцию, метод или функциональный объект. Этот тип следует выделять в стеке и передавать функциям по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 287
url: /ru/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> класс

Представляет указатель на функцию, метод или функциональный объект. Этот тип следует выделять в стеке и передавать функциям по значению или по ссылке. Никогда не используйте [System::SmartPtr](../smartptr/) класс для управления объектами этого типа.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ReturnType | The return type of a function, method or a function object pointer to which is represented by the class |
| ArgumentTypes | The argument list of a function, method or a function object pointer to which is represented by the class |
## Методы

| Метод | Описание |
| --- | --- |
|  [Delegate](./delegate/)() | Конструктор по умолчанию. Создаёт объект делегата, который не указывает ни на что. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Перемещающий копирующий конструктор. Перенимает владение сущностью, на которую указывает указанный делегат. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Конструктор. Создаёт объект делегата из указанного указателя на свободную функцию или статический метод. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Конструктор. Создаёт делегат из указанного указателя на функциональный объект, созданный std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Конструктор. Создаёт делегат из указанного функционального объекта. |
|  [Delegate](./delegate/)(long, T\&&) | Перемещающий конструктор. Создаёт делегат из указанного функционального объекта. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Конструктор. Создаёт делегат, указывающий на указанный нестатический метод указанного объекта. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Конструктор. Создаёт делегат, указывающий на указанный нестатический метод указанного объекта. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Создаёт объект делегата, указывающий на объект функции std::function. |
| **bool** [Empty](./empty/)() const | Определяет, является ли текущий объект делегата пустым, т.е. не указывает ни на какую сущность. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Вызывает функцию, метод или функциональный объект, на который указывает текущий объект делегата. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Перемещающий оператор присваивания. Перенимает владение сущностью, на которую указывает указанный делегат. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Сравнивает два объекта делегата, чтобы проверить, указывают ли они на одну и ту же сущность. |
## Замечания

```cpp
#include "system/delegate.h"
#include <iostream"

// Объявление делегата.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Присвоить переменной адрес функции PrintMessage.
  Message mes = Message(&PrintMessage);

  // Вызвать функцию.
  mes();

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