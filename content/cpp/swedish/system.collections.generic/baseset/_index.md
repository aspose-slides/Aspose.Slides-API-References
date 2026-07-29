---
title: BaseSet
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 92
url: /sv/system.collections.generic/baseset/
---
## BaseSet klass




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++-specifik. |
| void [Add](./add/)(const T\&) override | Lägger till ett element i mängden. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Hämtar iterator till det första elementet i den const-kvalificerade samlingen. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra det refererade objektet eftersom [GetEnumerator()](../ienumerable/getenumerator/) returnerar ett kopierat objekt av T. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Hämtar iterator till det första const-kvalificerade elementet i samlingen. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Hämtar iterator för ett icke-existerande const-kvalificerat element bakom samlingens slut. |
| void [Clear](./clear/)() override | Tar bort alla element i mängden. |
| **bool** [Contains](./contains/)(const T\&) const override | Kontrollerar om elementet finns i mängden. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopierar hash-innehåll till befintliga array-element. |
| [set_t](./set_t/)\& [data](./data/)() | Åtkomst åt underliggande datastruktur. |
| const [set_t](./set_t/)\& [data](./data/)() const | Åtkomst åt underliggande datastruktur. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Hämtar iterator för ett icke-existerande element bakom slutet av den const-kvalificerade samlingen. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra det refererade objektet eftersom [GetEnumerator()](../ienumerable/getenumerator/) returnerar ett kopierat objekt av T. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| int [get_Count](./get_count/)() const override | Hämtar antalet element i mängden. |
| virtual int [get_Count](./get_count/)() const | Förhindrar att [get_Count()](./get_count/) döljs. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Kontrollerar om samlingen är skrivskyddad. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Hämtar objektet som samlingen synkroniseras genom. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Skapar enumerator. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [ICollection](../icollection/icollection/)() | Standardkonstruktör. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopieringskonstruktör. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Flyttkonstruktör. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Tillämpar en ackumulatorfunktion över en sekvens. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestämmer om alla element i en sekvens uppfyller ett villkor. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bestämmer om en sekvens innehåller några element. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestämmer om något element i en sekvens existerar eller uppfyller ett villkor. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Beräknar medelvärdet av en sekvens av numeriska värden. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transform-funktion på varje element i inmatningssekvensen. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Kastar elementen till den specificerade typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Konkatenar två sekvenser. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bestämmer om en sekvens innehåller ett specificerat värde. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Returnerar antalet element i sekvensen (beräknat genom direkt uppräkning). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar antalet element i sekvensen som uppfyller det specificerade villkoret. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Returnerar elementet på ett specificerat index i en sekvens. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Returnerar elementet på ett specificerat index i en sekvens. |
| T [LINQ_First](../ienumerable/linq_first/)() | Returnerar det första elementet i en sekvens. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar det första elementet i en sekvens som uppfyller det specificerade villkoret. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupperar elementen i en sekvens. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupperar elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Returnerar det sista elementet i en sekvens. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Returnerar det sista elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Anropar en transform-funktion på varje element i en generisk sekvens och returnerar det maximala resulterande värdet. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Anropar en transform-funktion på varje element i en generisk sekvens och returnerar det minsta resulterande värdet. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den specificerade typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Vänder på ordningen av elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformerar element i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformerar varje element i en sekvens till en ny form genom att inkludera elementets index. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projekterar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Hoppar över ett specificerat antal på varandra följande element från början av en sekvens och returnerar resten. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Returnerar ett specificerat antal på varandra följande element från början av en sekvens. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Skapar en array från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Skapar en List<T> från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtrerar en sekvens baserat på det specificerade predikatet. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Flyttilldelningsoperator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Flyttilldelningsoperator. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| **bool** [Remove](./remove/)(const T\&) override | Tar bort element från mängden. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknet med ett specificerat värde. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), System::BaseTypesInfo\<[System::Object](../../system/object/)\>) | RTTI-information. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n-te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| **bool** [TryAdd](./tryadd/)(const T\&) | Lägger till element i mängden. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin-const-iterator för den aktuella containern. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end-const-iterator för den aktuella containern. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end-iterator för den aktuella containern. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ThisType](./thistype/) | Självtyp. |
| [ThisPtr](./thisptr/) | Pekartyp. |
| [set_t](./set_t/) | Underliggande datatyp. |
| [iterator](./iterator/) | Iterator-typ. |
| [const_iterator](./const_iterator/) | Const-iterator-typ. |
| [ValueType](./valuetype/) | Värdetyp. |
| [BaseType](./basetype/) | Implementerat gränssnitt. |
| [IEnumerablePtr](./ienumerableptr/) | Pekare till enumererbart gränssnitt. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator**-pekare. |

## Se även

* Klass [Object](../../system/object/)
* Klass [ICollection](../icollection/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)