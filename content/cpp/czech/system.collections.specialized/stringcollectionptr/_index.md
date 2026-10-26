---
title: StringCollectionPtr
second_title: Aspose.Slides pro C++ – reference API
description: Ukazatel kolekce řetězců s operátorem přístupu.
type: docs
weight: 40
url: /cs/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr třída

Ukazatel kolekce řetězců s operátorem přístupu.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Metody

| Metoda | Popis |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Přístupová metoda k metodě [begin()](../../system/smartptr/begin/) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Přístupová metoda k metodě [begin()](../../system/smartptr/begin/) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na jeho vlastní typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na základní typ pomocí static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Přístupová metoda k metodě [cbegin()](../../system/smartptr/cbegin/) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Přístupová metoda k metodě [cend()](../../system/smartptr/cend/) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí const_cast na ukazovaném objektu. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí dynamic_cast na ukazovaném objektu. |
| auto [end](../../system/smartptr/end/)() | Přístupová metoda k metodě [end()](../../system/smartptr/end/) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Přístupová metoda k metodě [end()](../../system/smartptr/end/) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Vrací ukazovaný objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Získává režim ukazatele. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Vrací ukazovaný objekt, ale asertuje, že ukazatel je ve sdíleném režimu. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Vrací počet existujících sdílených ukazatelů na odkazovaný objekt, včetně aktuálního. Asertuje, že aktuální ukazatel je ve sdíleném režimu. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Volá [GetHashCode()](../../system/smartptr/gethashcode/) na ukazovaném objektu. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Vrací aktuálně odkazovaný objekt (pokud existuje) nebo vyvolá výjimku. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Vrací ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Vrací odkazovaný objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Vrací ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda je ukazovaný objekt konkrétního typu nebo jeho podtypu. Odpovídá semantice C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontroluje, zda ukazatel ukazuje na jiný objekt než vlastněný (vytvořeno aliasing konstruktorem). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontroluje, zda je ukazatel ve sdíleném režimu. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontroluje, zda je ukazatel v slabém (weak) režimu. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Kontroluje, zda ukazatel není null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontroluje, zda je ukazatel null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Vrací referenci na ukazovaný objekt. Asertuje, že ukazatel není null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Umožňuje přístup k členům odkazovaného objektu. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Poskytuje semantiku méně než pro třídu [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Poskytuje semantiku méně než pro třídu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Přesune přiřazení objektu [SmartPtr](../../system/smartptr/). x se stane nepoužitelným. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopírově přiřazuje objekt [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopírově přiřazuje objekt [SmartPtr](../../system/smartptr/). Provádí požadované konverze typů. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Přiřazuje neupravený ukazatel objektu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Nastavuje hodnotu ukazatele na nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Kontroluje, zda ukazatel ukazuje na nullptr. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Přístupová funkce. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Odstraňuje aliasing (vytvořený aliasing konstruktorem) z ukazatele, zajišťuje, že spravuje (pokud je sdílený) nebo sleduje (pokud je slabý) stejný objekt na který ukazuje. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Nastavuje ukazovaný objekt. |
| void [reset](../../system/smartptr/reset/)() | Nastavuje ukazatel, aby ukazoval na nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Nastavuje režim ukazatele. Může měnit počty referencí odkazovaného objektu. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Volá metodu SetTemplateWeakPtr() na ukazovaném objektu (pokud existuje). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Vytváří objekt [SmartPtr](../../system/smartptr/) požadovaného režimu. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Vytváří null-pointer objekt [SmartPtr](../../system/smartptr/) požadovaného režimu. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Vytváří [SmartPtr](../../system/smartptr/) ukazující na zadaný objekt, nebo konvertuje surový ukazatel na [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopírující konstruktor objektu [SmartPtr](../../system/smartptr/). Oba ukazatele potom ukazují na stejný objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopírující konstruktor objektu [SmartPtr](../../system/smartptr/). Oba ukazatele potom ukazují na stejný objekt. Provede konverzi typu, pokud je povolena. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Přesunovým konstruktorem vytvoří objekt [SmartPtr](../../system/smartptr/). Efektivně prohodí dva ukazatele, pokud jsou ve stejném režimu. x může být po volání nepoužitelný. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Převádí typ odkazovaného pole vytvořením nového pole jiného typu. Užitečné, pokud v C# existuje přetypování pole, které není podporováno v C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializuje prázdné pole. Používá se pro překlad některých konstrukcí kódu v C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Vytváří [SmartPtr](../../system/smartptr/), který sdílí informace o vlastnictví s počáteční hodnotou ptr, ale drží nesouvisející a neřízený ukazatel p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí static_cast na ukazovaném objektu. |
|  [StringCollectionPtr](./stringcollectionptr/)() | Vytváří null ukazatel. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Vytváří ukazatel na konkrétní kolekci. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Převádí libovolný typ ukazatele na ukazatel na [Object](../../system/object/). Nepotřebuje, aby typ Pointee_ byl kompletní. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Zkratka pro získání objektu [System::TypeInfo](../../system/typeinfo/) pro typ Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Ničí objekt [SmartPtr](../../system/smartptr/). Pokud je potřeba, sníží čítač referencí ukazovaného objektu a smaže objekt. |

## Viz také

* Třída [SmartPtr](../../system/smartptr/)
* Jmenný prostor [System::Collections::Specialized](../)
* Knihovna [Aspose.Slides](../../)