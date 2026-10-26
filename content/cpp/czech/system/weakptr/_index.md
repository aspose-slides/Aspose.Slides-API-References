---
title: WeakPtr
second_title: Aspose.Slides pro C++ API Reference
description: "Podtřída System::SmartPtr, která se při konstrukci nastaví do slabého režimu. Všimněte si, že tato třída nezaručuje, že její instance bude vždy zůstávat ve slabém režimu, protože set_Mode() je stále přístupná. Tento typ je ukazatel pro správu mazání jiných objektů. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo konstantní referencí."
type: docs
weight: 1496
url: /cs/system/weakptr/
---
## WeakPtr třída


Podtřída [System::SmartPtr](../smartptr/) která při konstrukci nastaví sebe do slabého režimu. Upozorňujeme, že tato třída nezaručuje, že její instance bude vždy zůstávat ve slabém režimu, protože [set_Mode()](../smartptr/set_mode/) je stále přístupná. Tento typ je ukazatel pro správu mazání jiných objektů. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo konstantní referencí.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ ukazovaného objektu. |
## Metody

| Metoda | Popis |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Přístupová metoda pro metodu [begin()](../smartptr/begin/) podkladové kolekce. Překládá se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Přístupová metoda pro metodu [begin()](../smartptr/begin/) podkladové kolekce. Překládá se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypovává ukazatel na jeho vlastní typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypovává ukazatel na základní typ pomocí static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypovává ukazatel na odvozený typ pomocí dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypovává ukazatel na odvozený typ pomocí dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Přístupová metoda pro metodu [cbegin()](../smartptr/cbegin/) podkladové kolekce. Překládá se pouze pokud je SmartPtr_ specializační typ s metodou [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Přístupová metoda pro metodu [cend()](../smartptr/cend/) podkladové kolekce. Překládá se pouze pokud je SmartPtr_ specializační typ s metodou [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Přetypovává ukazatel na jiný typ pomocí const_cast na objektu, na který ukazuje. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Přetypovává ukazatel na jiný typ pomocí dynamic_cast na objektu, na který ukazuje. |
| auto [end](../smartptr/end/)() | Přístupová metoda pro metodu [end()](../smartptr/end/) podkladové kolekce. Překládá se pouze pokud je SmartPtr_ specializační typ s metodou [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Přístupová metoda pro metodu [end()](../smartptr/end/) podkladové kolekce. Překládá se pouze pokud je SmartPtr_ specializační typ s metodou [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Kontroluje, zda byl odkazovaný objekt již smazán. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Získá objekt, na který ukazuje. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Získá režim ukazatele. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Získá objekt, na který ukazuje, ale ověří, že ukazatel je ve sdíleném režimu. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Získá počet sdílených ukazatelů existujících na odkazovaný objekt, včetně aktuálního. Ověří, že aktuální ukazatel je ve sdíleném režimu. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Získá odkazovaný objekt. Ověří, že ukazatel je ve slabém režimu. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Volá [GetHashCode()](../smartptr/gethashcode/) na ukazovaném objektu. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Získá aktuálně odkazovaný objekt (pokud existuje) nebo vyvolá výjimku. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Totéž jako [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Získá odkazovaný objekt. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Totéž jako [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontroluje, zda je ukazovaný objekt specifického typu nebo jeho podtyp. Řídí se semantikou C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Kontroluje, zda ukazatel ukazuje na jiný objekt než vlastněný (vytvořený aliasovým konstruktorem). |
| **bool** [IsShared](../smartptr/isshared/)() const | Kontroluje, zda je ukazatel ve sdíleném režimu. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Kontroluje, zda je ukazatel ve slabém režimu. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Kontroluje, zda ukazatel není null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Kontroluje, zda je ukazatel null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Získá referenci na ukazovaný objekt. Ověří, že ukazatel není null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Umožňuje přístup k členům odkazovaného objektu. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Poskytuje semantiku porovnání menší pro třídu [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Poskytuje semantiku porovnání menší pro třídu [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Přiřadí hodnotu slabému ukazateli. Volá specifický operátor přiřazení SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Přesune přiřazený [SmartPtr](../smartptr/) objekt. x se stane nepoužitelným. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Kopíruje přiřazený [SmartPtr](../smartptr/) objekt. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopíruje přiřazený [SmartPtr](../smartptr/) objekt. Provádí potřebné konverze typů. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Přiřadí surový ukazatel objektu [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Nastaví hodnotu ukazatele na nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontroluje, zda je slabý ukazatel null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Odstraňuje aliasing (vytvořený aliasovým konstruktorem) z ukazatele, zajišťuje, že spravuje (pokud je sdílený) nebo sleduje (pokud je slabý) stejný objekt, na který ukazuje. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Nastaví ukazovaný objekt. |
| void [reset](../smartptr/reset/)() | Nastaví ukazatel tak, aby ukazoval na nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Nastaví režim ukazatele. Může změnit referenční počty odkazovaného objektu. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Volá metodu SetTemplateWeakPtr() na ukazovaném objektu (pokud existuje). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Vytvoří objekt [SmartPtr](../smartptr/) požadovaného režimu. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Vytvoří null-pointer objekt [SmartPtr](../smartptr/) požadovaného režimu. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Vytvoří [SmartPtr](../smartptr/) ukazující na zadaný objekt, nebo převádí surový ukazatel na [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopíruje konstruktor [SmartPtr](../smartptr/) objektu. Oba ukazatele po vytvoření ukazují na stejný objekt. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopíruje konstruktor [SmartPtr](../smartptr/) objektu. Oba ukazatele po vytvoření ukazují na stejný objekt. Provede konverzi typu, pokud je povolena. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Přesunovým konstruktor vytvoří objekt [SmartPtr](../smartptr/). V podstatě prohodí dva ukazatele, pokud jsou ve stejném režimu. x může být po volání nepoužitelný. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Převádí typ referencovaného pole vytvořením nového pole jiného typu. Užitočné, pokud v C# existuje přetypování pole, které není podporováno v C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicializuje prázdné pole. Použito pro převod některých konstrukcí kódu C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruktorem vytvoří [SmartPtr](../smartptr/), který sdílí informace o vlastnictví s počáteční hodnotou ptr, ale obsahuje nesouvisející a neřízený ukazatel p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Přetypovává ukazatel na jiný typ pomocí static_cast na ukazovaném objektu. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Převádí libovolný typ ukazatele na ukazatel typu [Object](../object/). Nepotřebuje, aby typ Pointee_ byl kompletní. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Zkratka pro získání objektu [System::TypeInfo](../typeinfo/) pro typ Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Vytvoří null ukazatel. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Vytvoří slabý ukazatel na daný objekt. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Vytvoří slabý ukazatel odkazující na stejný ukazatel, na který ukazuje ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Vytvoří slabý ukazatel odkazující na stejný ukazatel, na který ukazuje x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Kopíruje konstruktor slabého ukazatele. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Kopíruje konstruktor slabého ukazatele. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Přesunovým konstruktorem vytvoří slabý ukazatel. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Zničí objekt [SmartPtr](../smartptr/). Pokud je potřeba, sníží referenční čítač ukazovaného objektu a smaže objekt. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias pro odpovídající třídu [SmartPtr](../smartptr/). |
| [WeakPtr_](./weakptr_/) | Alias pro typ vlastní třídy. |
| [Pointee_](./pointee_/) | Ukazovaný typ. |

## Viz také

* Třída [SmartPtr](../smartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)