---
title: List
second_title: Aspose.Slides för C++ API-referens
description: Framåtriktad deklaration av List.
type: docs
weight: 430
url: /sv/system.collections.generic/list/
---
## Listklass

[List](./) framåtriktad deklaration.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++-specifik. |
| void [Add](./add/)(const T\&) override | Lägger till ett element i slutet av listan. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Lägger till element i listan; används vid översättning av initialiserare. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Lägger till alla element från samlingen (eller sig själv) i slutet av den aktuella listan. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Hämtar en skrivskyddad referens till denna samling. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Hämtar en iterator till det första elementet i samlingen. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Hämtar en iterator till det första elementet i den const-kvalificerade samlingen. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Söker efter objekt i en sorterad lista. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Söker efter objekt i en sorterad lista. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Söker efter objekt i en sorterad lista. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Hämtar en iterator till det första const-kvalificerade elementet i samlingen. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Hämtar en iterator för ett icke-existerande const-kvalificerat element bakom slutet av samlingen. |
| void [Clear](./clear/)() override | Raderar alla element. |
| **bool** [Contains](./contains/)(const T\&) const override | Kontrollerar om objektet finns i listan. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Skapar en lista med element konverterade till en annan typ. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopierar listans element till befintliga arrayelement. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopierar alla element till befintliga arrayelement. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopierar element från angivet index till befintliga arrayelement. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Hämtar en omvänd iterator till det sista const-kvalificerade elementet i samlingen (första i omvänd ordning). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Hämtar en omvänd iterator för ett icke-existerande const-kvalificerat element före början av samlingen. |
| [vector_t](./vector_t/)\& [data](./data/)() | Funktion för åtkomst till underliggande datastruktur. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Funktion för åtkomst till underliggande datastruktur. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Hämtar en iterator för ett icke-existerande element bakom slutet av samlingen. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Hämtar en iterator för ett icke-existerande element bakom slutet av den const-kvalificerade samlingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Kontrollerar om ett element som uppfyller ett specifikt predikat finns i listan. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter sista elementet som uppfyller ett specifikt predikat. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Applicerar en åtgärd på alla element i listan. |
| int [get_Capacity](./get_capacity/)() const | Hämtar aktuell listkapacitet. |
| int [get_Count](./get_count/)() const override | Hämtar antalet element i aktuell lista. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Kontrollerar om samlingen har fast storlek. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Kontrollerar om samlingen är skrivskyddad. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Hämtar objektet som samlingen synkroniseras genom. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastruktur associerad med objektet. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera över listans element. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Skapar ett segment av listan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [ICollection](../icollection/icollection/)() | Standardkonstruktor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopieringskonstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Flyttkonstruktor. |
| T [idx_get](./idx_get/)(int) const override | Hämtar element på en specifik position. |
| void [idx_set](./idx_set/)(int, T) override | Sätter element på en specifik position. |
| int [IndexOf](./indexof/)(const T\&) const override | Hämtar första index för ett specifikt objekt. |
| int [IndexOf](./indexof/)(const T\&, int) const | Söker efter specifikt objekt i listan. |
| void [Insert](./insert/)(int, const T\&) override | Infogar objekt på angiven position. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Infogar ett dataområde på en specifik position. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten i hela listan. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](./) som sträcker sig från första elementet till det angivna indexet. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](./) som innehåller det angivna antalet element och slutar vid det angivna indexet. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applicerar en ackumulatorfunktion över en sekvens. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestämmer om alla element i en sekvens uppfyller ett villkor. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bestämmer om en sekvens innehåller några element. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestämmer om något element i en sekvens existerar eller uppfyller ett villkor. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Beräknar medelvärdet av en sekvens av numeriska värden. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transform-funktion på varje element i indatasekvensen. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Kastar element till den angivna typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Konkatenar två sekvenser. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bestämmer om en sekvens innehåller ett specifikt värde. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Returnerar antalet element i sekvensen (beräknat genom direkt uppräkning). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar antalet element i sekvensen som uppfyller det angivna villkoret. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_First](../ienumerable/linq_first/)() | Returnerar det första elementet i en sekvens. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar det första elementet i en sekvens som uppfyller det angivna villkoret. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den angivna typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Vänder ordningen på elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformerar element i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformerar varje element i en sekvens till en ny form genom att införliva elementets index. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projicerar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Hoppar över ett angivet antal sammanhängande element från början av en sekvens och returnerar resten. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Returnerar ett angivet antal sammanhängande element från början av en sekvens. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Skapar en array från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Skapar en List<T> från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtrerar en sekvens baserat på det angivna predikatet. |
|  [List](./list/)() | Skapar en tom lista. |
|  [List](./list/)(int) | Skapar en lista med fördefinierad kapacitet. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Kopieringskonstruktor. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Flytt-tilldelningsoperator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Flytt-tilldelningsoperator. |
| vector_t::reference [operator[]](./operator[]/)(int) | Accessorfunktion. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Accessorfunktion. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den const-kvalificerade samlingen (första i omvänd ordning). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| **bool** [Remove](./remove/)(const T\&) override | Tar bort den första instansen av ett specifikt objekt från listan. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Tar bort alla element som matchar ett specifikt predikat. |
| void [RemoveAt](./removeat/)(int) override | Tar bort objekt på angiven position. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| void [RemoveRange](./removerange/)(int, int) | Tar bort ett segment av listan. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Hämtar en omvänd iterator för ett icke-existerande element före början av samlingen. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Hämtar en omvänd iterator för ett icke-existerande element före början av den const-kvalificerade samlingen. |
| void [Reverse](./reverse/)() | Vänder ordningen på alla element i hela listan. |
| void [Reverse](./reverse/)(int, int) | Vänder ordningen på elementen i listsegmentet. |
| void [set_Capacity](./set_capacity/)(int) | Sätter listkapacitet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sorterar element i listan. |
| void [Sort](./sort/)() | Sorterar element i listan med standardkomparator. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sorterar element i listsegmentet. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sorterar element i listan. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Konverterar lista till array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| void [TrimExcess](./trimexcess/)() | Justera listkapaciteten så den passar storleken. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Bestämmer om varje element i samlingen matchar villkoren som definierats av det angivna predikatet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satser för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementeringen av begin-const-iterator för den aktuella behållaren. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementeringen av begin-iterator för den aktuella behållaren. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementeringen av end-const-iterator för den aktuella behållaren. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementeringen av end-iterator för den aktuella behållaren. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ValueType](./valuetype/) | Denna typ. |
| [BaseType](./basetype/) | Gränssnittstyp. |
| [vector_t](./vector_t/) | Underliggande datatyp. |
| [iterator](./iterator/) | Iterator-typ. |
| [const_iterator](./const_iterator/) | Konstant iterator-typ. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
| [const_reverse_iterator](./const_reverse_iterator/) | Konstant omvänd iterator-typ. |
| [IEnumerablePtr](./ienumerableptr/) | Behållare som håller element av samma typ som vi håller. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator**-typ. |
## Anmärkningar

[List](./) - omslag runt std::vector för att användas i översatt kod. Kräver att operator == implementeras för elementtypen. Objekt av den här klassen bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det medför körfel och/eller påstående fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Skapa den första listan.
  auto list1 = MakeObject<List<int>>();

  // Fyll den första listan.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Sortera den första listan.
  // De första listans element blir: {-5, 1, 3, 8}
  list1->Sort();

  // Ta bort objektet på index 2.
  // De första listans element blir: {-5, 1, 8}
  list1->RemoveAt(2);

  // Infoga objektet på index 1.
  // De första listans element blir: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Skapa den andra listan.
  auto list2 = MakeObject<List<int>>();

  // Fyll den andra listan.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Lägg till element från den andra listan till den första.
  list1->AddRange(list2);

  // Skriv ut den första listans element.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Detta kodexempel producerar följande utdata:
- 5 15 1 8 10 20 30
*/
```

## Se även

* Klass [Object](../../system/object/)
* Klass [IList](../ilist/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)