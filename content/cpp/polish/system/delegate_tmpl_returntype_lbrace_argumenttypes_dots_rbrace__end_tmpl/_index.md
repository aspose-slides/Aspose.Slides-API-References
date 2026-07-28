---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Reprezentuje wskaźnik do funkcji, metody lub obiektu funkcyjnego. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 287
url: /pl/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> klasa


Represents a pointer to a function, method or a function object. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ReturnType | The return type of a function, method or a function object pointer to which is represented by the class |
| ArgumentTypes | The argument list of a function, method or a function object pointer to which is represented by the class |
## Metody

| Metoda | Opis |
| --- | --- |
|  [Delegate](./delegate/)() | Domyślny konstruktor. Tworzy obiekt delegata, który nie wskazuje na nic. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Konstruktor kopiujący przenoszący. Przejmuje własność encji wskazywanej przez określony delegat. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Tworzy obiekt delegata z określonego wskaźnika do wolnej funkcji lub metody statycznej. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Tworzy delegata z określonego wskaźnika do obiektu funkcyjnego wygenerowanego przez std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Konstruktor. Tworzy delegata z określonego obiektu funkcyjnego. |
|  [Delegate](./delegate/)(long, T\&&) | Konstruktor przenoszący. Tworzy delegata z określonego obiektu funkcyjnego. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Tworzy delegata wskazującego na określoną metodę niestatyczną podanego obiektu. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Konstruktor. Tworzy delegata wskazującego na określoną metodę niestatyczną podanego obiektu. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Tworzy obiekt delegata wskazujący na obiekt funkcji std::function. |
| **bool** [Empty](./empty/)() const | Określa, czy bieżący obiekt delegata jest pusty, np. nie wskazuje na żadną encję. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Wywołuje funkcję, metodę lub obiekt funkcyjny wskazywany przez bieżący obiekt delegata. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Operator przypisania przenoszącego. Przejmuje własność encji wskazywanej przez określony delegat. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Porównuje dwa obiekty delegata, aby sprawdzić, czy wskazują na tę samą encję. |
## Uwagi



```cpp
#include "system/delegate.h"
#include <iostream"

// Zadeklaruj delegata.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Przypisz do zmiennej adres funkcji PrintMessage.
  Message mes = Message(&PrintMessage);

  // Wywołaj funkcję.
  mes();

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Hello, world!
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)