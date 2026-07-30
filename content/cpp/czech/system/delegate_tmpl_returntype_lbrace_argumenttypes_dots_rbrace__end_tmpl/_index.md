---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Reprezentuje ukazatel na funkci, metodu nebo objekt funkce. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k správě objektů tohoto typu."
type: docs
weight: 287
url: /cs/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> třída


Represents a pointer to a function, method or a function object. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) třídu to manage objects of this type.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ReturnType | Návratový typ funkce, metody nebo ukazatele na objekt funkce, který je reprezentován touto třídou |
| ArgumentTypes | Seznam argumentů funkce, metody nebo ukazatele na objekt funkce, který je reprezentován touto třídou |
## Metody

| Metoda | Popis |
| --- | --- |
|  [Delegate](./delegate/)() | Výchozí konstruktor. Vytvoří objekt delegáta, který neukazuje na nic. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Kopírovací konstruktor s přesunem. Převzává vlastnictví entity, na kterou ukazuje zadaný delegát. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Vytvoří objekt delegáta ze zadaného ukazatele na volnou funkci nebo statickou metodu. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Vytvoří delegáta ze zadaného ukazatele na funkční objekt vytvořený pomocí std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Konstruktor. Vytvoří delegáta ze zadaného funkčního objektu. |
|  [Delegate](./delegate/)(long, T\&&) | Konstruktorem přesunu. Vytvoří delegáta ze zadaného funkčního objektu. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Vytvoří delegáta, který ukazuje na zadanou nestatickou metodu zadaného objektu. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Konstruktor. Vytvoří delegáta, který ukazuje na zadanou nestatickou metodu zadaného objektu. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Vytvoří objekt delegáta, který ukazuje na objekt funkce std::function. |
| **bool** [Empty](./empty/)() const | Určuje, zda je aktuální objekt delegáta prázdný, tj. neukazuje na žádnou entitu. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Vyvolá funkci, metodu nebo funkční objekt, na který ukazuje aktuální objekt delegáta. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Operátor přiřazení s přesunem. Převzává vlastnictví entity, na kterou ukazuje zadaný delegát. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Porovnává dva objekty delegáta, aby zjistil, zda ukazují na stejnou entitu. |
## Poznámky



```cpp
#include "system/delegate.h"
#include <iostream"

// Deklarujte delegáta.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Přiřaďte proměnné adresu funkce PrintMessage.
  Message mes = Message(&PrintMessage);

  // Zavolejte funkci.
  mes();

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
Hello, world!
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)