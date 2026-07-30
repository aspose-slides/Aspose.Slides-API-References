---
title: GroupCollectionPtr
second_title: Aspose.Slides pro C++ API Reference
description: Ukazatel na kolekci skupin. Tento typ je ukazatel, který spravuje mazání objektu jiného. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo konstantní referencí.
type: docs
weight: 53
url: /cs/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr třída


[Group](../group/) kolekční ukazatel. Tento typ je ukazatel, který spravuje mazání jiného objektu. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo konstantní referencí.

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## Metody

| Metoda | Popis |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Přístupová metoda k metodě [begin()](../../system/smartptr/begin/) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ specializační typ s metodou [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Přístupová metoda k metodě [begin()](../../system/smartptr/begin/) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ specializační typ s metodou [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypovává ukazatel na jeho vlastní typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypovává ukazatel na základní typ pomocí static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypovává ukazatel na odvozený typ pomocí dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypovává ukazatel na odvozený typ pomocí dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Přístupová metoda k metodě [cbegin()](../../system/smartptr/cbegin/) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ specializační typ s metodou [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Přístupová metoda k metodě [cend()](../../system/smartptr/cend/) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ specializační typ s metodou [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Přetypovává ukazatel na jiný typ pomocí const_cast na ukazovaném objektu. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Přetypovává ukazatel na jiný typ pomocí dynamic_cast na ukazovaném objektu. |
| auto [end](../../system/smartptr/end/)() | Přístupová metoda k metodě [end()](../../system/smartptr/end/) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ specializační typ s metodou [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Přístupová metoda k metodě [end()](../../system/smartptr/end/) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ specializační typ s metodou [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Získá ukazovaný objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Získá režim ukazatele. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Získá ukazovaný objekt, ale ověří, že ukazatel je ve sdíleném režimu. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Získá počet sdílených ukazatelů existujících na referencovaný objekt, včetně aktuálního. Ověří, že aktuální ukazatel je ve sdíleném režimu. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Volá [GetHashCode()](../../system/smartptr/gethashcode/) na ukazovaném objektu. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Získá aktuálně referencovaný objekt (pokud existuje) nebo vyhodí výjimku. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Získá referencovaný objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../../system/smartptr/get/). |
| [GroupCollectionPtr](./groupcollectionptr/)() | Konstruktor nulového ukazatele. |
| [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | Konstruktor převodu typu. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda je ukazovaný objekt konkrétního typu nebo jeho podtyp. Dodržuje semantiku 'is' v C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontroluje, zda ukazatel ukazuje na jiný objekt než vlastní (vytvořený aliasovým konstruktorem). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontroluje, zda je ukazatel ve sdíleném režimu. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontroluje, zda je ukazatel v slabém režimu. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Kontroluje, zda ukazatel není nulový. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontroluje, zda je ukazatel nulový. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Získá referenci na ukazovaný objekt. Ověří, že ukazatel není nulový. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Umožňuje přístup k členům referencovaného objektu. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Poskytuje semantiku porovnání méně pro třídu [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Poskytuje semantiku porovnání méně pro třídu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Přiřadí přesunutím objekt [SmartPtr](../../system/smartptr/). x se stane nepoužitelným. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopírově přiřadí objekt [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopírově přiřadí objekt [SmartPtr](../../system/smartptr/). Provede požadované konverze typů. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Přiřadí surový ukazatel objektu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Nastaví hodnotu ukazatele na nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Kontroluje, zda ukazatel ukazuje na nullptr. |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(size_t) const | [Group](../group/) přístupová metoda. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Odstraní aliasování (vytvořené aliasovým konstruktorem) z ukazatele, zajistí, že spravuje (pokud sdílený) nebo sleduje (pokud slabý) stejný objekt, na který ukazuje. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Nastaví ukazovaný objekt. |
| void [reset](../../system/smartptr/reset/)() | Nastaví ukazatel tak, aby ukazoval na nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Nastaví režim ukazatele. Může změnit počty referencí referencovaného objektu. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Volá metodu SetTemplateWeakPtr() na ukazovaném objektu (pokud existuje). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Vytvoří objekt [SmartPtr](../../system/smartptr/) požadovaného režimu. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Vytvoří nulový [SmartPtr](../../system/smartptr/) objekt požadovaného režimu. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Vytvoří [SmartPtr](../../system/smartptr/) ukazující na specifikovaný objekt, nebo převede surový ukazatel na [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](../../system/smartptr/). Oba ukazatele po operaci ukazují na stejný objekt. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](../../system/smartptr/). Oba ukazatele po operaci ukazují na stejný objekt. Provede konverzi typu, pokud je povolena. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Přesunově konstruuje objekt [SmartPtr](../../system/smartptr/). V podstatě vymění dva ukazatele, pokud jsou oba ve stejném režimu. x může být po volání nepoužitelný. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Převádí typ referencovaného pole vytvořením nového pole jiného typu. Užitečné, pokud v C# existuje převod typu pole, který není v C++ podporován. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializuje prázdné pole. Používá se při převodu některých konstrukcí kódu v C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruuje [SmartPtr](../../system/smartptr/), který sdílí informaci o vlastnictví s počáteční hodnotou ptr, ale drží nesouvisející a neřízený ukazatel p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Přetypovává ukazatel na jiný typ pomocí static_cast na ukazovaném objektu. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Převádí jakýkoliv typ ukazatele na ukazatel na [Object](../../system/object/). Nevyžaduje, aby typ Pointee_ byl kompletní. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Zkratka pro získání objektu [System::TypeInfo](../../system/typeinfo/) pro typ Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Zničí objekt [SmartPtr](../../system/smartptr/). Pokud je potřeba, sníží čítač referencí ukazovaného objektu a objekt odstraní. |

## Viz také

* třída [SmartPtr](../../system/smartptr/)
* jmenný prostor [System::Text::RegularExpressions](../)
* knihovna [Aspose.Slides](../../)