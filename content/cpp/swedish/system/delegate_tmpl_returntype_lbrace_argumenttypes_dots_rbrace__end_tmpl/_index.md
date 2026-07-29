---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en pekare till en funktion, metod eller ett funktionsobjekt. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av den här typen."
type: docs
weight: 287
url: /sv/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> klass


Representerar en pekare till en funktion, metod eller ett funktionsobjekt. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av den här typen.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ReturnType | Returtypen för en funktion, metod eller ett funktionsobjekt som pekaren representeras av klassen |
| ArgumentTypes | Argumentlistan för en funktion, metod eller ett funktionsobjekt som pekaren representeras av klassen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [Delegate](./delegate/)() | Standardkonstruktor. Skapar delegate-objektet som inte pekar på någonting. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Flyttande kopieringskonstruktor. Tar äganderätten för en entitet som pekas på av den specificerade delegaten. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Skapar ett delegate-objekt från den specificerade pekaren till en fri funktion eller statisk metod. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Skapar en delegat från den specificerade pekaren till funktionsobjektet som genererats av std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Konstruktor. Skapar en delegat från det specificerade funktionsobjektet. |
|  [Delegate](./delegate/)(long, T\&&) | Flyttkonstruktor. Skapar en delegat från det specificerade funktionsobjektet. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Skapar en delegat som pekar på den specificerade icke-statiska metoden för det specificerade objektet. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Konstruktor. Skapar en delegat som pekar på den specificerade icke-statiska metoden för det specificerade objektet. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Skapar ett delegatobjekt som pekar på ett std::function-funktionsobjekt. |
| **bool** [Empty](./empty/)() const | Bestämmer om det aktuella delegatobjektet är tomt, t.ex. inte pekar på någon entitet. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Anropar en funktion, metod eller ett funktionsobjekt som pekas på av det aktuella delegatobjektet. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Flyttande tilldelningsoperator. Tar äganderätten för en entitet som pekas på av den specificerade delegaten. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Jämför två delegatobjekt för att kontrollera om de pekar på samma entitet. |
## Anmärkningar



```cpp
#include "system/delegate.h"
#include <iostream"

// Deklarera delegaten.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Tilldela variabeln adressen till funktionen PrintMessage.
  Message mes = Message(&PrintMessage);

  // Anropa funktionen.
  mes();

  return 0;
}
/*
Detta kodexempel ger följande utskrift:
Hej, världen!
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)