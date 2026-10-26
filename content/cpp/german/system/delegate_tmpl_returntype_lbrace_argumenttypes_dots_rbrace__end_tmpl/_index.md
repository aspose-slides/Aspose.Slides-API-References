---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Zeiger auf eine Funktion, Methode oder ein Funktionsobjekt dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 287
url: /de/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> Klasse


Stellt einen Zeiger auf eine Funktion, Methode oder ein Funktionsobjekt dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ReturnType | Der Rückgabetyp einer Funktion, Methode oder eines Funktionsobjektzeigers, der durch die Klasse repräsentiert wird |
| ArgumentTypes | Die Argumentliste einer Funktion, Methode oder eines Funktionsobjektzeigers, der durch die Klasse repräsentiert wird |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [Delegate](./delegate/)() | Standardkonstruktor. Erstellt das Delegate-Objekt, das auf nichts zeigt. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Move-Kopierkonstruktor. Übernimmt das Eigentum an einer Entität, auf die der angegebene Delegate zeigt. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Erstellt ein Delegate-Objekt aus dem angegebenen Zeiger auf eine freie Funktion oder statische Methode. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Erstellt ein Delegate aus dem angegebenen Zeiger auf das Funktionsobjekt, das von std::bind() erzeugt wurde. |
|  [Delegate](./delegate/)(int, T\&) | Konstruktor. Erstellt ein Delegate aus dem angegebenen Funktionsobjekt. |
|  [Delegate](./delegate/)(long, T\&&) | Move-Konstruktor. Erstellt ein Delegate aus dem angegebenen Funktionsobjekt. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Erstellt ein Delegate, das auf die angegebene nicht-statische Methode des angegebenen Objekts zeigt. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Konstruktor. Erstellt ein Delegate, das auf die angegebene nicht-statische Methode des angegebenen Objekts zeigt. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Erstellt ein Delegate-Objekt, das auf ein std::function Funktionsobjekt zeigt. |
| **bool** [Empty](./empty/)() const | Bestimmt, ob das aktuelle Delegate-Objekt leer ist, d.h. auf keine Entität zeigt. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Ruft eine Funktion, Methode oder ein Funktionsobjekt auf, auf das das aktuelle Delegate-Objekt zeigt. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Move-Zuweisungsoperator. Übernimmt das Eigentum an einer Entität, auf die der angegebene Delegate zeigt. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Vergleicht zwei Delegate-Objekte, um festzustellen, ob sie auf dieselbe Entität zeigen. |
## Hinweise



```cpp
#include "system/delegate.h"
#include <iostream>

// Deklariere das Delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Weist der Variablen die Adresse der Funktion PrintMessage zu.
  Message mes = Message(&PrintMessage);

  // Ruft die Funktion auf.
  mes();

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Hello, world!
*/
```

## Siehe Auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)