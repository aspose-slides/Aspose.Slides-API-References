---
title: ListPtr
second_title: Aspose.Slides pro C++ – reference API
description: Ukazatel na seznam s operátory přístupu. Tento typ je ukazatel pro správu mazání jiných objektů. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo const referencí.
type: docs
weight: 456
url: /cs/system.collections.generic/listptr/
---
## ListPtr třída

[List](../list/) ukazatel s operátory přístupu. Tento typ je ukazatel pro správu mazání jiných objektů. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo const referencí.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Přístupový operátor pro metodu [begin()](../../system/smartptr/begin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Přístupový operátor pro metodu [begin()](../../system/smartptr/begin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na svůj vlastní typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na základní typ pomocí static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Přístupový operátor pro metodu [cbegin()](../../system/smartptr/cbegin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Přístupový operátor pro metodu [cend()](../../system/smartptr/cend/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí const_cast na cílovém objektu. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí dynamic_cast na cílovém objektu. |
| auto [end](../../system/smartptr/end/)() | Přístupový operátor pro metodu [end()](../../system/smartptr/end/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Přístupový operátor pro metodu [end()](../../system/smartptr/end/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Získá ukazovaný objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Získá režim ukazatele. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Získá ukazovaný objekt, ale kontroluje, že ukazatel je ve sdíleném režimu. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Vrátí počet existujících sdílených ukazatelů na odkazovaný objekt, včetně aktuálního. Kontroluje, že aktuální ukazatel je ve sdíleném režimu. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Volá [GetHashCode()](../../system/smartptr/gethashcode/) na ukazovaném objektu. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Získá aktuálně odkazovaný objekt (pokud existuje) nebo vyhodí výjimku. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Získá odkazovaný objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda je ukazovaný objekt konkrétního typu nebo jeho podtypu. Dodržuje semantiku C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ověří, zda ukazatel ukazuje na jiný objekt než vlastněný (vytvořeno aliasovacím konstruktorem). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ověří, zda je ukazatel ve sdíleném režimu. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ověří, zda je ukazatel ve slabém režimu. |
|  [ListPtr](./listptr/)(std::nullptr_t) | Inicializuje nulový ukazatel. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Inicializuje ukazatel na určený seznam. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ověří, zda ukazatel není nulový. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ověří, zda je ukazatel nulový. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Získá referenci na ukazovaný objekt. Kontroluje, že ukazatel není nulový. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Umožní přístup k členům odkazovaného objektu. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Poskytuje semantiku méně porovnání pro třídu [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Poskytuje semantiku méně porovnání pro třídu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Přiřadí přesunutí objektu [SmartPtr](../../system/smartptr/). x se stane nepoužitelným. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopírově přiřadí objekt [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopírově přiřadí objekt [SmartPtr](../../system/smartptr/). Provede požadované konverze typů. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Přiřadí surový ukazatel objektu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Nastaví hodnotu ukazatele na nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ověří, zda je ukazatel [List](../list/) nulový. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Přístupový operátor. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Přístupový operátor. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Odstraní aliasování (vytvořené aliasovacím konstruktorem) z ukazatele, zajistí, že spravuje (ve sdíleném režimu) nebo sleduje (ve slabém režimu) stejný objekt, na který ukazuje. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Nastaví ukazovaný objekt. |
| void [reset](../../system/smartptr/reset/)() | Nastaví ukazatel tak, aby ukazoval na nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Nastaví režim ukazatele. Může změnit referenční počty odkazovaného objektu. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Volá metodu SetTemplateWeakPtr() na ukazovaném objektu (pokud existuje). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Vytvoří objekt [SmartPtr](../../system/smartptr/) požadovaného režimu. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Vytvoří nulový ukazatel objektu [SmartPtr](../../system/smartptr/) požadovaného režimu. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Vytvoří [SmartPtr](../../system/smartptr/) ukazující na určený objekt, nebo převádí surový ukazatel na [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](../../system/smartptr/). Oba ukazatele poté ukazují na stejný objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](../../system/smartptr/). Oba ukazatele poté ukazují na stejný objekt. Provede konverzi typu, pokud je povolena. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Přesunem konstruuje objekt [SmartPtr](../../system/smartptr/). V podstatě prohodí dva ukazatele, pokud jsou oba ve stejném režimu. x může být po volání nepoužitelný. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Převede typ odkazovaného pole vytvořením nového pole jiného typu. Užitečné, pokud v C# existuje typový převod pole, který není podporován v C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializuje prázdné pole. Používá se pro překlad některých konstrukcí kódu v C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruuje [SmartPtr](../../system/smartptr/), který sdílí informaci o vlastnictví s počáteční hodnotou ptr, ale drží nesouvisející a neřízený ukazatel p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí static_cast na ukazovaném objektu. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Převádí jakýkoli typ ukazatele na ukazatel na [Object](../../system/object/). Nepožaduje, aby typ Pointee_ byl kompletní. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Zkratka pro získání objektu [System::TypeInfo](../../system/typeinfo/) pro typ Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Zničí objekt [SmartPtr](../../system/smartptr/). Pokud je potřeba, sníží referenční čítač ukazovaného objektu a objekt smaže. |
## Viz také

* Třída [SmartPtr](../../system/smartptr/)
* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)