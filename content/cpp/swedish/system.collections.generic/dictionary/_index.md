---
title: Dictionary
second_title: Aspose.Slides för C++ API-referens
description: Framåtriktad deklaration av Dictionary-klassen.
type: docs
weight: 144
url: /sv/system.collections.generic/dictionary/
---
## Dictionary klass

Forward declaration of [Dictionary](./) klass.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | Lägger till nyckel-värde-par i behållaren. |
| virtual void [Add](../icollection/add/)(const T\&) | Lägger till element i samlingen. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra det refererade objektet eftersom [GetEnumerator()](../ienumerable/getenumerator/) returnerar ett kopieringsobjekt av T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| virtual void [Clear](../icollection/clear/)() | Tar bort alla element från samlingen. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Kontrollerar om elementet finns i samlingen. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | Kontrollerar om behållaren innehåller nyckeln. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Kopierar dictionary-innehåll till befintliga array-element. |
|  [Dictionary](./dictionary/)() | Skapar en tom dictionary. |
|  [Dictionary](./dictionary/)(const [map_t](./map_t/)&) | Kopierar data från map. |
|  [Dictionary](./dictionary/)(int) | Överlagring som motsvarar skapandet av förallokerad dictionary; allokerar i själva verket inget. |
|  [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>&) | Kopieringskonstruktor. |
|  [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>) | Kopieringskonstruktor. |
|  [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>) | Skapar en tom dictionary. |
|  [Dictionary](./dictionary/)(int, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>&) | Skapar en tom dictionary. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra det refererade objektet eftersom [GetEnumerator()](../ienumerable/getenumerator/) returnerar ett kopieringsobjekt av T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual int [get_Count](../icollection/get_count/)() const | Hämtar antalet element i samlingen. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Kontrollerar om samlingens storlek är fast. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Kontrollerar om samlingen är skrivskyddad. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Kontrollerar om behållaren är trådsäker. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Åtkomst till nyckelsamling. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Hämtar objektet som samlingen synkroniseras genom. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Åtkomst till värdesamling. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknare-datstruktur associerad med objektet. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Skapar enumerator-objekt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | Returnerar värdet om det finns; annars **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Returnerar värdet om det finns; annars **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | Returnerar värdet om det finns; annars **null**, vilket endast är meningsfullt för referenstyper. |
|  [ICollection](../icollection/icollection/)() | Standardkonstruktör. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Kopieringskonstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Flyttkonstruktor. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Getter-funktion. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Setter-funktion. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Tillämpar en ackumulatorfunktion över en sekvens. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Avgör om alla element i en sekvens uppfyller ett villkor. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Avgör om en sekvens innehåller några element. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Avgör om någon element i en sekvens finns eller uppfyller ett villkor. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Beräknar medelvärdet av en sekvens numeriska värden. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transform-funktion på varje element i inmatningssekvensen. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Kastar elementen till den specificerade typen. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | Konkatenar två sekvenser. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Avgör om en sekvens innehåller ett specificerat värde. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Returnerar antalet element i sekvensen (beräknat via direkt uppräkning). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Returnerar antalet element i sekvensen som uppfyller det angivna villkoret. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Returnerar elementet vid ett specificerat index i en sekvens. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Returnerar elementet vid ett specificerat index i en sekvens. |
| T [LINQ_First](../ienumerable/linq_first/)() | Returnerar det första elementet i en sekvens. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Returnerar det första elementet i en sekvens som uppfyller det angivna villkoret. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Grupperar elementen i en sekvens. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Grupperar elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Returnerar det sista elementet i en sekvens. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Returnerar det sista elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Anropar en transform-funktion på varje element i en generisk sekvens och returnerar det maximala resulterande värdet. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Anropar en transform-funktion på varje element i en generisk sekvens och returnerar det minsta resulterande värdet. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den specificerade typen. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverterar ordningen på elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Transformerar element i en sekvens. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Transformerar varje element i en sekvens till en ny form genom att inkorporera elementets index. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | Projicerar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Hoppar över ett specificerat antal sammanhängande element från sekvensens början och returnerar resten. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Returnerar ett specificerat antal sammanhängande element från sekvensens början. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Skapar en array från en sekvens. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Skapar en List<T> från en sekvens. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Filtrerar en sekvens baserat på det specificerade predikatet. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Flytttilldelningsoperator. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Flytttilldelningsoperator. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | Tar bort nyckeln från behållaren. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Tar bort elementet från samlingen. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter den n-te mallargumentet till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | Söker efter värde och hämtar det om det finns. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning upp enligt C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Hämtar implementationen av begin-konst-iterator för den aktuella behållaren. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Hämtar implementationen av begin-iterator för den aktuella behållaren. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Hämtar implementationen av end-konst-iterator för den aktuella behållaren. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Hämtar implementationen av end-iterator för den aktuella behållaren. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [KeyCollection](./keycollection/) | Samling av nycklar att extrahera. |
| [ValueCollection](./valuecollection/) | Samling av värden att extrahera. |
| [map_t](./map_t/) | Underliggande datatyp. |
| [Ptr](./ptr/) | Pekartyp. |
| [KVPair](./kvpair/) | Nyckel-värde-par-typ. |
| [IEnumerablePtr](./ienumerableptr/) | Pekare till enumerable-gränssnitt. |
| [IEnumeratorPtr](./ienumeratorptr/) | Pekare till enumerator. |

## Anmärkningar

[Dictionary](./) som mappar värden till nycklar. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, då det kommer leda till körfel och/eller assert-fel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Skapa en instans av Dictionary-klassen.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Fyll dictionaryn.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Skriv ut dictionaryns objekt.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
Detta kodexempel ger följande utdata:
0 - Foo
1 - Bar
2 - Baz
*/
```

## Se även

* Klass [BaseDictionary](../basedictionary/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)