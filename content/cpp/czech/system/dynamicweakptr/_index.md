---
title: DynamicWeakPtr
second_title: Aspose.Slides pro C++ referenční příručka API
description: Třída chytrého ukazatele, která sleduje režimy ukazatelů šablonových argumentů uloženého objektu a aktualizuje je po každém přiřazení. Tento typ je ukazatelem pro správu mazání jiného objektu. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo konstantní referencí.
type: docs
weight: 781
url: /cs/system/dynamicweakptr/
---
## DynamicWeakPtr třída


Třída chytrého ukazatele, která sleduje režimy ukazatelů šablonových argumentů uloženého objektu a aktualizuje je po každém přiřazení. Tento typ je ukazatelem pro správu mazání jiného objektu. Měl by být alokován na zásobníku a předáván do funkcí buď hodnotou, nebo konstantní referencí.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Pointee | typ. |
| trunkMode | Režim samotného chytrého ukazatele, sdílený nebo slabý. |
| weakLeafs | Indexy šablonových argumentů uloženého typu, které by měly být nastaveny do režimu slabého ukazatele. |
## Metody

| Metoda | Popis |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Přístupový prvek pro metodu [begin()](../smartptr/begin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Přístupový prvek pro metodu [begin()](../smartptr/begin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypuje ukazatel na jeho vlastní typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypuje ukazatel na základní typ pomocí static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Přístupový prvek pro metodu [cbegin()](../smartptr/cbegin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Přístupový prvek pro metodu [cend()](../smartptr/cend/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí const_cast na ukazovaném objektu. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí dynamic_cast na ukazovaném objektu. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Vytvoří nulový chytrý ukazatel. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Vytvoří chytrý ukazatel ukazující na zadaný objekt. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Kopírově konstruuje chytrý ukazatel. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopírově konstruuje chytrý ukazatel. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Kopírově konstruuje chytrý ukazatel. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Přesunově konstruuje chytrý ukazatel. |
| auto [end](../smartptr/end/)() | Přístupový prvek pro metodu [end()](../smartptr/end/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Přístupový prvek pro metodu [end()](../smartptr/end/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Získá ukazovaný objekt. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Získá režim ukazatele. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Získá ukazovaný objekt, ale ověří, že ukazatel je v režimu sdílený. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Získá počet sdílených ukazatelů existujících na odkazovaný objekt, včetně aktuálního. Ověří, že aktuální ukazatel je v režimu sdílený. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Volá [GetHashCode()](../smartptr/gethashcode/) na ukazovaném objektu. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Získá aktuálně odkazovaný objekt (pokud existuje) nebo vyhodí výjimku. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Získá odkazovaný objekt. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontroluje, zda je ukazovaný objekt konkrétního typu nebo jeho podtřídy. Dodržuje semantiku C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Kontroluje, zda ukazatel ukazuje na jiný objekt než vlastní (vytvořeno aliasing konstruktorem). |
| **bool** [IsShared](../smartptr/isshared/)() const | Kontroluje, zda je ukazatel v režimu sdílený. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Kontroluje, zda je ukazatel v režimu slabý. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Kontroluje, zda ukazatel není null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Kontroluje, zda je ukazatel null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Získá referenci na ukazovaný objekt. Ověří, že ukazatel není null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Umožňuje přístup k členům odkazovaného objektu. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Poskytuje semantiku méně než pro třídu [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Poskytuje semantiku méně než pro třídu [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Přesunu přiřazuje chytrý ukazatel. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Kopírující přiřazuje chytrý ukazatel. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopírující přiřazuje chytrý ukazatel. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Přiřazuje chytrý ukazatel. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Nastaví chytrý ukazatel na null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontroluje, zda je chytrý ukazatel null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Odstraňuje aliasing (vytvořený aliasing konstruktorem) z ukazatele, zajišťuje, že spravuje (pokud je sdílený) nebo sleduje (pokud je slabý) stejný objekt, na který ukazuje. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Nastaví ukazovaný objekt. |
| void [reset](../smartptr/reset/)() | Nastaví ukazatel tak, aby ukazoval na nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Nastaví režim ukazatele. Může změnit referenční počty odkazovaného objektu. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Volá metodu SetTemplateWeakPtr() na ukazovaném objektu (pokud existuje). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Vytvoří objekt [SmartPtr](../smartptr/) požadovaného režimu. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Vytvoří nulový [SmartPtr](../smartptr/) objekt požadovaného režimu. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Vytvoří [SmartPtr](../smartptr/) ukazující na zadaný objekt, nebo převádí surový ukazatel na [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](../smartptr/). Oba ukazatele po té ukazují na stejný objekt. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](../smartptr/). Oba ukazatele po té ukazují na stejný objekt. Provede konverzi typu, pokud je povoleno. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Přesunově konstruuje objekt [SmartPtr](../smartptr/). V podstatě prohodí dva ukazatele, pokud jsou oba ve stejném režimu. x může být po volání nepoužitelný. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Převádí typ odkazovaného pole vytvořením nového pole jiného typu. Užitečné, pokud v C# existuje typová konverze pole, která není podporována v C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicializuje prázdné pole. Používá se k překladu některých konstrukcí kódu v C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruuje [SmartPtr](../smartptr/), který sdílí informace o vlastnictví s počáteční hodnotou ptr, ale drží nesouvisející a neřízený ukazatel p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí static_cast na ukazovaném objektu. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Převádí libovolný typ ukazatele na ukazatel na [Object](../object/). Nepožaduje kompletní typ Pointee_. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Zkratka pro získání objektu [System::TypeInfo](../typeinfo/) pro typ Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Zničí objekt [SmartPtr](../smartptr/). Pokud je potřeba, sníží referenční čítač ukazovaného objektu a smaže objekt. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias základní třídy. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias typu sebe sama. |
| [Pointee_](./pointee_/) | ukazovaný typ. |

## Viz také

* Třída [SmartPtr](../smartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)