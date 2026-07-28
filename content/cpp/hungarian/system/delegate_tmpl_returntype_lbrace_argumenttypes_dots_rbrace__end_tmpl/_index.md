---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides C++ API referencia
description: "Függvényre, metódusra vagy függvényobjektumra mutató mutatót képvisel. Ez a típus a stacken kell, hogy legyen lefoglalva, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak a példányainak kezelésére."
type: docs
weight: 287
url: /hu/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> osztály


Egy függvényre, metódusra vagy függvényobjektumra mutató mutatót képvisel. Ez a típus a stacken kell, hogy legyen lefoglalva, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak a példányainak kezelésére.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ReturnType | A függvény, metódus vagy függvényobjektum mutató visszatérési típusa, amelyet az osztály képvisel |
| ArgumentTypes | A függvény, metódus vagy függvényobjektum mutató argumentumlistája, amelyet az osztály képvisel |
## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [Delegate](./delegate/)() | Alapértelmezett konstruktor. Létrehozza a delegált objektumot, amely nem mutat semmire. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Mozgó másoló konstruktor. Átvállalja a megadott delegátum által mutatott entitás tulajdonjogát. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Létrehoz egy delegált objektumot a megadott szabad függvényre vagy statikus metódusra mutató mutatóból. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Létrehoz egy delegáltat a std::bind() által generált függvényobjektumra mutató megadott mutatóból. |
|  [Delegate](./delegate/)(int, T\&) | Konstruktor. Létrehoz egy delegáltat a megadott függvényobjektumból. |
|  [Delegate](./delegate/)(long, T\&&) | Mozgó konstruktor. Létrehoz egy delegáltat a megadott függvényobjektumból. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Létrehoz egy delegáltat, amely a megadott objektum nem statikus metódusára mutat. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Konstruktor. Létrehoz egy delegáltat, amely a megadott objektum nem statikus metódusára mutat. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Létrehoz egy delegált objektumot, amely egy std::function függvényobjektumra mutat. |
| **bool** [Empty](./empty/)() const | Megállapítja, hogy a jelenlegi delegált objektum üres-e, például nem mutat egyetlen entitásra sem. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Meghív egy függvényt, metódust vagy függvényobjektumot, amelyre a jelenlegi delegált objektum mutat. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Mozgó hozzárendelő operátor. Átvállalja a megadott delegátum által mutatott entitás tulajdonjogát. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Összehasonlít két delegált objektumot, hogy ellenőrizze, ugyanarra az entitásra mutatnak-e. |
## Megjegyzések



```cpp
#include "system/delegate.h"
#include <iostream"

// Deklarálja a delegáltat.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // A változóhoz hozzárendeli a PrintMessage függvény címét.
  Message mes = Message(&PrintMessage);

  // Meghívja a függvényt.
  mes();

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet állítja elő:
Helló, világ!
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)