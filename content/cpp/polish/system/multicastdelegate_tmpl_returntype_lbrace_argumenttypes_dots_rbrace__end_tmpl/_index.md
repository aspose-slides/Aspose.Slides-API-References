---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides dla C++ - Referencja API
description: "Reprezentuje kolekcję delegatów. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1093
url: /pl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> klasa


Reprezentuje kolekcję delegatów. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ReturnType | Typ zwracany przez wywoływalne jednostki, na które wskazuje każdy delegat w kolekcji |
| ArgumentTypes | Lista argumentów wywoływalnych jednostek, na które wskazuje każdy delegat w kolekcji |
## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NIE ZAIMPLEMENTOWANO. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Dodaje określony delegat do kolekcji. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Dodaje określony obiekt funkcyjny do kolekcji delegatów. Obiekt funkcyjny jest konwertowany do typu delegata Callback przed dodaniem do kolekcji. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Dodaje określony obiekt MulticastDelegate do kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Dodaje określoną niestatyczną metodę określonego obiektu do kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Dodaje określoną niestatyczną metodę określonego obiektu do kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Usuwa określony delegat z kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Usuwa określoną niestatyczną metodę określonego obiektu z kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Usuwa określoną niestatyczną metodę określonego obiektu z kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Usuwa określony obiekt MulticastDelegate z kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Usuwa wszystkie delegaty z kolekcji delegatów. |
| **bool** [empty](./empty/)() const | Określa, czy kolekcja delegatów jest pusta. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NIE ZAIMPLEMENTOWANO. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Wywołuje wszystkie delegaty aktualnie obecne w kolekcji delegatów. Delegaty są wywoływane w takiej samej kolejności, w jakiej zostały dodane do kolekcji. Metoda blokuje się, dopóki delegaty są wykonywane. |
| **bool** [IsNull](./isnull/)() const | Określa, czy kolekcja delegatów jest pusta. |
|  [MulticastDelegate](./multicastdelegate/)() | Tworzy pustą kolekcję. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Równoznaczny z domyślnym konstruktorem. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Wykonuje płytką kopię kolekcji delegatów. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Konstruktor przenoszący. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Tworzy instancję i umieszcza określony delegat w kolekcji delegatów. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Tworzy instancję i umieszcza określoną wartość w kolekcji delegatów. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Tworzy instancję i umieszcza określoną wartość w kolekcji delegatów. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Określa, czy kolekcja delegatów nie jest pusta. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Określa, czy dwie instancje MulticastDelegate - bieżący obiekt i określony obiekt - są nierówne. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Wywołuje wszystkie delegaty aktualnie obecne w kolekcji delegatów. Delegaty są wywoływane w takiej samej kolejności, w jakiej zostały dodane do kolekcji. Operator blokuje się, dopóki delegaty są wykonywane. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Dodaje określony delegat do kolekcji. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Usuwa określony delegat z kolekcji delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Przypisuje kolekcję delegatów reprezentowaną przez określony obiekt do bieżącego obiektu. W rezultacie oba obiekty wskazują na tę samą kolekcję delegatów. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Operator przypisania przenoszącego. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Określa, czy kolekcja delegatów jest pusta. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Określa, czy dwie instancje MulticastDelegate - bieżący obiekt i określony obiekt - są równe. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Usuwa zawarte wywołania zwrotne, które są puste (nie wywołują niczego). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Zwraca referencję do obiektu [TypeInfo](../typeinfo/) reprezentującego informacje o typie klasy MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [Callback](./callback/) | Typ delegatów reprezentowanych przez klasę MulticastDelegate. |
| [Function](./function/) | Typ funkcji związanej z sygnaturą delegata. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)