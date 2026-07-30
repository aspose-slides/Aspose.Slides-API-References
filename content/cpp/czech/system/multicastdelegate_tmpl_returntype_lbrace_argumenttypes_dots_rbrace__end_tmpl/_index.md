---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides pro C++ API Reference
description: "Představuje kolekci delegátů. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte System::SmartPtr třídu ke správě objektů tohoto typu."
type: docs
weight: 1093
url: /cs/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> třída


Representuje kolekci delegátů. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte [System::SmartPtr](../smartptr/) třídu ke správě objektů tohoto typu.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ReturnType | Návratový typ volatelných entit, na které ukazuje každý delegát v kolekci |
| ArgumentTypes | Seznam argumentů volatelných entit, na které ukazuje každý delegát v kolekci |
## Metody

| Metoda | Popis |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NEIMPLEMENTOVÁNO. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Přidá zadaný delegát do kolekce. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Přidá zadaný objekt funkce do kolekce delegátů. Objekt funkce je před přidáním do kolekce převeden na typ delegáta Callback. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Přidá zadaný objekt MulticastDelegate do kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Přidá zadanou nestatickou metodu zadaného objektu do kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Přidá zadanou nestatickou metodu zadaného objektu do kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Odebere zadaný delegát z kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Odebere zadanou nestatickou metodu zadaného objektu z kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Odebere zadanou nestatickou metodu zadaného objektu z kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Odebere zadaný objekt MulticastDelegate z kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Odebere všechny delegáty z kolekce delegátů. |
| **bool** [empty](./empty/)() const | Určuje, zda je kolekce delegátů prázdná. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NEIMPLEMENTOVÁNO. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Vyvolá všechny delegáty aktuálně přítomné v kolekci delegátů. Delegáty jsou vyvolány ve stejném pořadí, v jakém byly přidány do kolekce. Metoda blokuje, dokud jsou delegáti vykonáváni. |
| **bool** [IsNull](./isnull/)() const | Určuje, zda je kolekce delegátů prázdná. |
|  [MulticastDelegate](./multicastdelegate/)() | Vytvoří prázdnou kolekci. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Ekvivalent k výchozímu konstruktoru. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Provede mělkou kopii kolekce delegátů. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Přesunovací konstruktor. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Vytvoří instanci a umístí zadaný delegát do kolekce delegátů. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Vytvoří instanci a umístí zadanou hodnotu do kolekce delegátů. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Vytvoří instanci a umístí zadanou hodnotu do kolekce delegátů. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Určuje, zda kolekce delegátů není prázdná. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Určuje, zda dvě instance MulticastDelegate – aktuální objekt a zadaný objekt – nejsou rovny. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Vyvolá všechny delegáty aktuálně přítomné v kolekci delegátů. Delegáty jsou vyvolány ve stejném pořadí, v jakém byly přidány do kolekce. Operátor blokuje, dokud jsou delegáti vykonáváni. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Přidá zadaný delegát do kolekce. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Odebere zadaný delegát z kolekce delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Přiřadí kolekci delegátů reprezentované zadaným objektem aktuálnímu objektu. Výsledkem je, že oba objekty ukazují na stejnou kolekci delegátů. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Operátor přiřazení přesunutím. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Určuje, zda je kolekce delegátů prázdná. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Určuje, zda jsou dvě instance MulticastDelegate – aktuální objekt a zadaný objekt – stejné. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Vyčistí obsažené prázdné zpětné volání (nevolá nic). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Vrací odkaz na objekt [TypeInfo](../typeinfo/) představující informace o typu třídy MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [Callback](./callback/) | Typ delegátů reprezentovaných třídou MulticastDelegate. |
| [Function](./function/) | Typ funkce související s podpisem delegáta. |

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)