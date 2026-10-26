---
title: SmartPtr
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Ukazatelová třída pro zabalení typů alokovaných na haldě. Použijte ji pro správu paměti tříd dědících Object. Tento typ ukazatele následuje intruzivní semantiku ukazatelů. Počítadlo odkazů je uloženo buď v samotném Object, nebo ve struktuře čítače, která je úzce svázána s instancí Object. V každém případě všechny instance SmartPtr tvoří skupinu s jediným vlastníkem bez ohledu na způsob jejich vytvoření, což se liší od chování třídy std::shared_ptr. Převod surového ukazatele na SmartPtr je bezpečný, pokud existují další instance SmartPtr držící sdílené odkazy na stejný objekt. Instance třídy SmartPtr může být ve dvou stavech: sdílený ukazatel a slabý ukazatel. Aby objekt zůstal živý, musí být počet sdílených odkazů na něj kladný. Jak slabé, tak sdílené ukazatele lze použít k přístupu k ukazovanému objektu (volání metod, čtení nebo zápis polí apod.), ale slabé ukazatele se neúčastní počítání odkazů sdílených ukazatelů. Object je odstraněn, když je zničen poslední 'sdílený' SmartPtr ukazatel na něj. Proto se ujistěte, že k tomu nedojde, pokud neexistují jiné sdílené SmartPtr ukazatele na objekt, např. během konstrukce nebo destrukce objektu. Použijte System::Object::ThisProtector strážní objekty (v C++ kódu) nebo atributy CppCTORSelfReference či CppSelfReference (v C# kódu, který se překládá) k nápravě tohoto problému. Podobně zajistěte odstranění cyklických odkazů pomocí třídy System::WeakPtr nebo režimu System::SmartPtrMode::Weak (v C++ kódu) nebo atributu CppWeakPtr (v C# kódu, který se překládá). Pokud dva nebo více objektů odkazují na sebe pomocí 'sdílených' ukazatelů, nebudou nikdy smazány. Pokud má být typ ukazatele (slabý nebo sdílený) za běhu změněn, použijte metodu System::SmartPtr<T>::set_Mode() nebo třídu System::DynamicWeakPtr. Třída SmartPtr neobsahuje žádné virtuální metody. Měli byste ji dědit pouze tehdy, pokud vytváříte vlastní strategii správy paměti. Tento typ je ukazatel pro správu mazání jiných objektů. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo jako const reference."
type: docs
weight: 1236
url: /cs/system/smartptr/
---
## SmartPtr třída

Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ ukazovaného objektu. Musí být buď [System::Object](../object/) nebo podtřídou tohoto. |

## Metody

| Metoda | Popis |
| --- | --- |
| auto [begin](./begin/)() | Přístupová metoda k metodě [begin()](./begin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](./begin/). |
| auto [begin](./begin/)() const | Přístupová metoda k metodě [begin()](./begin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Přetypuje ukazatel na jeho vlastní typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Přetypuje ukazatel na základní typ pomocí static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Přetypuje ukazatel na odvozený typ pomocí dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Přístupová metoda k metodě [cbegin()](./cbegin/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | Přístupová metoda k metodě [cend()](./cend/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí const_cast na ukazovaném objektu. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí dynamic_cast na ukazovaném objektu. |
| auto [end](./end/)() | Přístupová metoda k metodě [end()](./end/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [end()](./end/). |
| auto [end](./end/)() const | Přístupová metoda k metodě [end()](./end/) podkladové kolekce. Kompiluje se pouze pokud je SmartPtr_ specializační typ s metodou [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | Získá ukazovaný objekt. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Získá režim ukazatele. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Získá ukazovaný objekt a ověří, že ukazatel je ve sdíleném režimu. |
| int [get_shared_count](./get_shared_count/)() const | Získá počet existujících sdílených ukazatelů na odkazovaný objekt, včetně aktuálního. Ověřuje, že aktuální ukazatel je ve sdíleném režimu. |
| int [GetHashCode](./gethashcode/)() const | Volá [GetHashCode()](./gethashcode/) na ukazovaném objektu. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Získá aktuálně odkazovaný objekt (pokud existuje) nebo vyhodí výjimku. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Získá odkazovaný objekt. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Získá ukazovaný objekt (pokud existuje) nebo nullptr. Stejné jako [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontroluje, zda je ukazovaný objekt konkrétního typu nebo jeho podtyp. Dodržuje semantiku C# 'is'. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Kontroluje, zda ukazatel ukazuje na jiný objekt než vlastněný (vytvořený aliasovacím konstruktorem). |
| **bool** [IsShared](./isshared/)() const | Kontroluje, zda je ukazatel ve sdíleném režimu. |
| **bool** [IsWeak](./isweak/)() const | Kontroluje, zda je ukazatel ve slabém režimu. |
| explicit  [operator bool](./operator_bool/)() const | Kontroluje, zda ukazatel není null. |
| **bool** [operator!](./operator_not/)() const | Kontroluje, zda je ukazatel null. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Získá referenci na ukazovaný objekt. Ověřuje, že ukazatel není null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Umožňuje přístup k členům odkazovaného objektu. |
| **bool** [operator<](./operator_less/)(Y *) const | Poskytuje porovnání menší než pro třídu [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Poskytuje porovnání menší než pro třídu [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Přiřadí přesunem objekt [SmartPtr](./). x se stane nepoužitelným. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Kopírově přiřadí objekt [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Kopírově přiřadí objekt [SmartPtr](./). Provede požadované konverze typů. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Přiřadí surový ukazatel objektu [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Nastaví hodnotu ukazatele na nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontroluje, zda ukazatel ukazuje na nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Odstraňuje aliasování (vytvořené aliasovacím konstruktorem) z ukazatele, zajišťuje, že spravuje (pokud je sdílený) nebo sleduje (pokud je slabý) stejný objekt, na který ukazuje. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Nastaví ukazovaný objekt. |
| void [reset](./reset/)() | Nastaví ukazatel tak, aby ukazoval na nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Nastaví režim ukazatele. Může změnit počítadla referencí odkazovaného objektu. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Volá metodu SetTemplateWeakPtr() na ukazovaném objektu (pokud existuje). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Vytvoří objekt [SmartPtr](./) požadovaného režimu. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Vytvoří objekt [SmartPtr](./) s null-pointerem požadovaného režimu. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Vytvoří [SmartPtr](./) ukazující na zadaný objekt, nebo převede surový ukazatel na [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](./). Oba ukazatele po konstrukci ukazují na stejný objekt. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopírově konstruuje objekt [SmartPtr](./). Oba ukazatele po konstrukci ukazují na stejný objekt. Provede konverzi typu, pokud je povolena. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Přesunovým konstruktem vytvoří objekt [SmartPtr](./). V podstatě prohodí dva ukazatele, pokud jsou oba ve stejném režimu. x může po volání být nepoužitelný. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Převádí typ odkazovaného pole vytvořením nového pole jiného typu. Užitečné, pokud v C# existuje přetypování pole, které není podporováno v C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Inicializuje prázdné pole. Používá se k překladu některých konstrukcí C# kódu. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruuje [SmartPtr](./), který sdílí informace o vlastnictví s počáteční hodnotou ptr, ale drží nesouvisející a neřízený ukazatel p. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Přetypuje ukazatel na jiný typ pomocí static_cast na ukazovaném objektu. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Převádí jakýkoli typ ukazatele na ukazatel na [Object](../object/). Nevyžaduje, aby typ Pointee_ byl kompletní. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Zkratka pro získání objektu [System::TypeInfo](../typeinfo/) pro typ Pointee_. |
|  [~SmartPtr](./~smartptr/)() | Zničí objekt [SmartPtr](./). V případě potřeby sníží počítadlo referencí ukazovaného objektu a objekt smaže. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [Pointee_](./pointee_/) | Typ, na který ukazuje. |
| [SmartPtr_](./smartptr_/) | Specializovaný typ chytrého ukazatele. |
| [ArrayType](./arraytype/) | Stejný jako Pointee_, pokud je specializací [System::Array](../array/), jinak void. |
| [ValueType](./valuetype/) | Typ úložiště ukazovaného pole. Smysluplné pouze pokud je T specializací [System::Array](../array/). |

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)