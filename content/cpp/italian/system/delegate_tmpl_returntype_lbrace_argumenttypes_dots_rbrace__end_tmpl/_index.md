---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un puntatore a una funzione, metodo o oggetto funzione. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire gli oggetti di questo tipo."
type: docs
weight: 287
url: /it/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> classe


Represents a pointer to a function, method or a function object. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ReturnType | The return type of a function, method or a function object pointer to which is represented by the class |
| ArgumentTypes | The argument list of a function, method or a function object pointer to which is represented by the class |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [Delegate](./delegate/)() | Costruttore predefinito. Costruisce l'oggetto delegate che non punta a nulla. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Costruttore di copia di spostamento. Assume la proprietà di un'entità puntata dal delegate specificato. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Costruttore. Costruisce un oggetto delegate dal puntatore specificato a una funzione libera o a un metodo statico. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Costruttore. Costruisce un delegate dal puntatore specificato all'oggetto funzione generato da std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Costruttore. Costruisce un delegate dall'oggetto funzione specificato. |
|  [Delegate](./delegate/)(long, T\&&) | Costruttore di spostamento. Costruisce un delegate dall'oggetto funzione specificato. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Costruttore. Costruisce un delegate che punta al metodo non statico specificato dell'oggetto specificato. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Costruttore. Costruisce un delegate che punta al metodo non statico specificato dell'oggetto specificato. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Costruisce un oggetto delegate che punta a un oggetto funzione std::function. |
| **bool** [Empty](./empty/)() const | Determina se l'oggetto delegate corrente è vuoto, ad esempio non punta a nessuna entità. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoca una funzione, metodo o oggetto funzione a cui punta l'oggetto delegate corrente. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Operatore di assegnazione di spostamento. Assume la proprietà di un'entità puntata dal delegate specificato. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Confronta due oggetti delegate per verificare se puntano alla stessa entità. |
## Osservazioni



```cpp
#include "system/delegate.h"
#include <iostream>

// Dichiarare il delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Assegna alla variabile l'indirizzo della funzione PrintMessage.
  Message mes = Message(&PrintMessage);

  // Chiama la funzione.
  mes();

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
Ciao, mondo!
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)