---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides C++ API-referencia
description: "Egy delegáltak gyűjteményét képviseli. Ezt a típust a stacken kell lefoglalni, és érték vagy referencia szerint átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 1093
url: /hu/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> osztály

Egy delegáltak gyűjteményét képviseli. Ezt a típust a stacken kell lefoglalni, és érték vagy referencia szerint átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ReturnType | A gyűjteményben lévő minden delegátum által mutatott meghívható entitások visszatérési típusa |
| ArgumentTypes | A gyűjteményben lévő minden delegátum által mutatott meghívható entitások argumentumlistája |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NEM VALÓSÍTOTT. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Hozzáadja a megadott delegátumot a gyűjteményhez. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Hozzáadja a megadott függvényobjektumot a delegátumgyűjteményhez. A függvényobjektum a hozzáadás előtt átalakul a Callback delegált típusra. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Hozzáadja a megadott MulticastDelegate objektumot a delegátumgyűjteményhez. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Hozzáadja a megadott objektum nem statikus metódusát a delegátumgyűjteményhez. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Hozzáadja a megadott objektum nem statikus metódusát a delegátumgyűjteményhez. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Eltávolítja a megadott delegátumot a delegátumgyűjteményből. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Eltávolítja a megadott objektum nem statikus metódusát a delegátumgyűjteményből. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Eltávolítja a megadott objektum nem statikus metódusát a delegátumgyűjteményből. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Eltávolítja a megadott MulticastDelegate objektumot a delegátumgyűjteményből. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Eltávolítja az összes delegátumot a delegátumgyűjteményből. |
| **bool** [empty](./empty/)() const | Megállapítja, hogy a delegátumgyűjtemény üres-e. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NEM VALÓSÍTOTT. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Meghívja az aktuálisan a delegátumgyűjteményben lévő összes delegátumot. A delegátumok ugyanabban a sorrendben hívódnak meg, ahogy a gyűjteménybe kerültek. A metódus blokkol, amíg a delegátumok végrehajtásra kerülnek. |
| **bool** [IsNull](./isnull/)() const | Megállapítja, hogy a delegátumgyűjtemény üres-e. |
| [MulticastDelegate](./multicastdelegate/)() | Üres gyűjteményt hoz létre. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Az alapértelmezett konstruktorral ekvivalens. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Megvalósítja a delegátumgyűjtemény sekély másolatát. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Mozgató konstruktor. |
| [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Példányt hoz létre, és a megadott delegátumot a delegátumgyűjteménybe helyezi. |
| [MulticastDelegate](./multicastdelegate/)(T) | Példányt hoz létre, és a megadott értéket a delegátumgyűjteménybe helyezi. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Példányt hoz létre, és a megadott értéket a delegátumgyűjteménybe helyezi. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Megállapítja, hogy a delegátumgyűjtemény nem üres. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Megállapítja, hogy a MulticastDelegate két példánya – a jelenlegi objektum és a megadott objektum – egyenlőtlenek-e. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Meghívja az aktuálisan a delegátumgyűjteményben lévő összes delegátumot. A delegátumok ugyanabban a sorrendben hívódnak meg, ahogy a gyűjteménybe kerültek. Az operátor blokkol, amíg a delegátumok végrehajtásra kerülnek. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Hozzáadja a megadott delegátumot a gyűjteményhez. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Eltávolítja a megadott delegátumot a delegátumgyűjteményből. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Átadja a megadott objektum által képviselt delegátumgyűjteményt az aktuális objektumnak. Ennek eredményeként mindkét objektum ugyanarra a delegátumgyűjteményre mutat. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Mozgató értékadási operátor. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Megállapítja, hogy a delegátumgyűjtemény üres-e. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Megállapítja, hogy a MulticastDelegate két példánya – a jelenlegi objektum és a megadott objektum – egyenlőek-e. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Törli a tartalmazott, üres (valójában semmit sem hívó) visszahívásokat. |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Visszaad egy referenciát a [TypeInfo](../typeinfo/) objektumra, amely a MulticastDelegate osztály típusinformációját képviseli. |
| [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Callback](./callback/) | A MulticastDelegate osztály által képviselt delegátumok típusa. |
| [Function](./function/) | A delegátszimához kapcsolódó függvény típusa. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)