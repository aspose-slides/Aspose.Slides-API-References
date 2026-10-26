---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en samling delegater. Denna typ bör allokeras på stacken och passeras till funktioner per värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 1093
url: /sv/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> klass


Representerar en samling delegater. Denna typ bör allokeras på stacken och passeras till funktioner per värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ReturnType | Returtyp för de anropbara enheterna som varje delegat i samlingen pekar på |
| ArgumentTypes | Argumentlista för de anropbara enheterna som varje delegat i samlingen pekar på |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Lägger till den angivna delegaten i samlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Lägger till det angivna funktionsobjektet i delegatsamlingen. Funktionsobjektet konverteras till Callback-delegattypen innan det läggs till i samlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Lägger till det angivna MulticastDelegate-objektet i delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Lägger till den angivna icke-statiska metoden för det angivna objektet i delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Lägger till den angivna icke-statiska metoden för det angivna objektet i delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Tar bort den angivna delegaten från delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Tar bort den angivna icke-statiska metoden för det angivna objektet från delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Tar bort den angivna icke-statiska metoden för det angivna objektet från delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Tar bort det angivna MulticastDelegate-objektet från delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Tar bort alla delegater från delegatsamlingen. |
| **bool** [empty](./empty/)() const | Avgör om delegatsamlingen är tom. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NOT IMPLEMENTED. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Invokerar alla delegater som för närvarande finns i delegatsamlingen. Delegaterna anropas i samma ordning som de lades till i samlingen. Metoden blockeras medan delegaterna körs. |
| **bool** [IsNull](./isnull/)() const | Avgör om delegatsamlingen är tom. |
|  [MulticastDelegate](./multicastdelegate/)() | Skapar en tom samling. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Motsvarar standardkonstruktorn. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Utför en ytlig kopia av delegatsamlingen. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Flyttkonstruktör. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Skapar en instans och lägger den angivna delegaten i delegatsamlingen. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Skapar en instans och lägger det angivna värdet i delegatsamlingen. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Skapar en instans och lägger det angivna värdet i delegatsamlingen. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Avgör om delegatsamlingen inte är tom. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Avgör om två instanser av MulticastDelegate – det aktuella objektet och det angivna objektet – är olika. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invokerar alla delegater som för närvarande finns i delegatsamlingen. Delegaterna anropas i samma ordning som de lades till i samlingen. Operatorn blockeras medan delegaterna körs. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Lägger till den angivna delegaten i samlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Tar bort den angivna delegaten från delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Tilldelar delegatsamlingen som representeras av det angivna objektet till det aktuella objektet. Som ett resultat pekar båda objekten på samma delegatsamling. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Flytttilldelningsoperator. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Avgör om delegatsamlingen är tom. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Avgör om två instanser av MulticastDelegate – det aktuella objektet och det angivna objektet – är lika. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Rensar bort inrymda callbacks som är tomma (som egentligen inte anropar något). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returnerar en referens till [TypeInfo](../typeinfo/)-objektet som representerar typinformationen för MulticastDelegate-klass. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [Callback](./callback/) | Typen för delegaterna som representeras av MulticastDelegate-klassen. |
| [Function](./function/) | Typen för funktionen relaterad till delegatsignaturen. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)