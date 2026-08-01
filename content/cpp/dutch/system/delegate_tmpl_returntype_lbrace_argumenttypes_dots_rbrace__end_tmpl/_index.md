---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides voor C++ API Referentie
description: "Stelt een pointer naar een functie, methode of een function-object voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr-klasse om objecten van dit type te beheren."
type: docs
weight: 287
url: /nl/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> klasse


Stelt een pointer naar een functie, methode of een function-object voor. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/)-klasse om objecten van dit type te beheren.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ReturnType | Het retourtype van een functie, methode of een function-objectpointer waar de klasse naar verwijst |
| ArgumentTypes | De argumentenlijst van een functie, methode of een function-objectpointer waar de klasse naar verwijst |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [Delegate](./delegate/)() | Standaardconstructor. Initialiseert het delegate-object dat nergens naar wijst. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Move-copy-constructor. Neemt het eigendom over van een entiteit waar de opgegeven delegate naar wijst. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Constructor. Initialiseert een delegate-object vanuit de opgegeven pointer naar een vrije functie of statische methode. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Constructor. Initialiseert een delegate vanuit de opgegeven pointer naar het function-object dat door std::bind() is gegenereerd. |
|  [Delegate](./delegate/)(int, T\&) | Constructor. Initialiseert een delegate vanuit het opgegeven function-object. |
|  [Delegate](./delegate/)(long, T\&&) | Move-constructor. Initialiseert een delegate vanuit het opgegeven function-object. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Constructor. Initialiseert een delegate die wijst naar de opgegeven niet-statische methode van het opgegeven object. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Constructor. Initialiseert een delegate die wijst naar de opgegeven niet-statische methode van het opgegeven object. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Initialiseert een delegate-object dat wijst naar een std::function-function-object. |
| **bool** [Empty](./empty/)() const | Bepaalt of het huidige delegate-object leeg is, bijvoorbeeld niet naar een entiteit wijst. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Roep een functie, methode of function-object aan waar het huidige delegate-object naar wijst. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Move-toewijzingsoperator. Neemt het eigendom over van een entiteit waar de opgegeven delegate naar wijst. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Vergelijkt twee delegate-objecten om te controleren of ze naar dezelfde entiteit wijzen. |
## Opmerkingen



```cpp
#include "system/delegate.h"
#include <iostream>

// Declareer de delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Wijs de variabele het adres van de PrintMessage-functie toe.
  Message mes = Message(&PrintMessage);

  // Roep de functie aan.
  mes();

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
Hallo, wereld!
*/
```

## Zie Ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)