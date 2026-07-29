---
title: CaptureCollection
second_title: Aspose.Slides för C++ API-referens
description: "Lista över fångster som utförs av en enskild fångstgrupp. Objekt av den här klassen bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 14
url: /sv/system.text.regularexpressions/capturecollection/
---
## CaptureCollection klass

Lista över fångster som utförs av en enskild fångstgrupp. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omge alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CaptureCollection : public System::Collections::Generic::List<CapturePtr>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | C++-specifik. |
| void [Add](./add/)(const [CapturePtr](../captureptr/)\&) override | Inaktiverar ändring av samlingen. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Lägger till element i slutet av listan. |
| void [AddCapture](./addcapture/)(const [CapturePtr](../captureptr/)\&) | Tjänstmetod för att lägga till en fångst i samlingen. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Lägger till element i listan; används vid översättning av initierare. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Lägger till alla element från samlingen (eller sig själv) i slutet av den aktuella listan. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Hämtar en skrivskyddad referens till denna samling. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Hämtar iterator till det första elementet i samlingen. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Hämtar iterator till det första elementet i den konstant-kvalificerade samlingen. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Söker efter objekt i en sorterad lista. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Söker efter objekt i en sorterad lista. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Söker efter objekt i en sorterad lista. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Hämtar iterator till det första konstant-kvalificerade elementet i samlingen. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Hämtar iterator för ett icke-existerande konstant-kvalificerat element bakom slutet av samlingen. |
| void [Clear](./clear/)() override | Inaktiverar rensning av samlingen. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Kontrollerar om objektet finns i listan. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Skapar en lista med element konverterade till en annan typ. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopierar list-element till befintliga array-element. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopierar alla element till befintliga array-element. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopierar element med början från det angivna indexet till befintliga array-element. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Hämtar en omvänd iterator till det sista konstant-kvalificerade elementet i samlingen (första i omvänd ordning). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Hämtar en omvänd iterator för ett icke-existerande konstant-kvalificerat element före början av samlingen. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Funktion för åtkomst till underliggande datastruktur. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Funktion för åtkomst till underliggande datastruktur. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Hämtar iterator för ett icke-existerande element bakom slutet av samlingen. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Hämtar iterator för ett icke-existerande element bakom slutet av den konstant-kvalificerade samlingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Kontrollerar om ett element som uppfyller ett specifikt predikat finns i listan. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Söker efter sista element som uppfyller ett specifikt predikat. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Tillämpar en åtgärd på alla element i listan. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | Hämtar aktuell listkapacitet. |
| int [get_Count](./get_count/)() const override | Hämtar antal fångster. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Kontrollerar om samlingen har fast storlek. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Markerar samlingen som skrivskyddad. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() const | Markerar samlingen som osynkroniserad. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Hämtar objektet som samlingen synkroniseras genom. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Hämtar enumerator för att iterera genom listans element. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog av C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | Skapar ett snitt av listan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog av C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Standardkonstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopieringskonstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Flyttkonstruktor. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Hämtar element på angiven position. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Sätter element på angiven position. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Hämtar första index för ett specifikt objekt. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Söker efter specifikt objekt i listan. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Infogar objekt på angiven position. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Infogar dataintervall på specifik position. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog av C# 'is'-operatorn. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för det sista förekomsten i hela listan. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för det sista förekomsten inom intervallet av element i [List](../../system.collections.generic/list/) som sträcker sig från det första elementet till det angivna indexet. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för det sista förekomsten inom intervallet av element i [List](../../system.collections.generic/list/) som innehåller det angivna antalet element och slutar vid det angivna indexet. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applicerar en ackumulatorfunktion över en sekvens. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestämmer om alla element i en sekvens uppfyller ett villkor. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bestämmer om en sekvens innehåller några element. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestämmer om något element i en sekvens finns eller uppfyller ett villkor. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Beräknar medelvärdet av en sekvens av numeriska värden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transformeringsfunktion på varje element i inmatningssekvensen. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Kastar element till den angivna typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Konkatenar två sekvenser. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bestämmer om en sekvens innehåller ett specifikt värde. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Returnerar antalet element i sekvensen (beräknat via direkt räkning). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar antalet element i sekvensen som uppfyller det angivna villkoret. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Returnerar det första elementet i en sekvens. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar det första elementet i en sekvens som uppfyller det angivna villkoret. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupperar elementen i en sekvens. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupperar elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Returnerar det sista elementet i en sekvens. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Returnerar det sista elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Anropar en transform-funktion på varje element i en generell sekvens och returnerar det maximala resulterande värdet. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Anropar en transform-funktion på varje element i en generell sekvens och returnerar det minsta resulterande värdet. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den angivna typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Vänder på ordningen av elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformerar element i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformerar varje element i en sekvens till en ny form genom att inkludera elementets index. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projekterar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Hoppar över ett angivet antal intilliggande element från början av en sekvens och returnerar resten. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Returnerar ett angivet antal intilliggande element från början av en sekvens. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Skapar en array från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Skapar en List<T> från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtrerar en sekvens baserat på det angivna predikatet. |
|  [List](../../system.collections.generic/list/list/)() | Skapar en tom lista. |
|  [List](../../system.collections.generic/list/list/)(int) | Skapar en lista med fördefinierad kapacitet. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Kopieringskonstruktor. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog av C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Flytt-tilldelningsoperator. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Flytt-tilldelningsoperator. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Åtkomstfunktion. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Åtkomstfunktion. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den konstant-kvalificerade samlingen (första i omvänd ordning). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenskör jämförelse av värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| **bool** [Remove](./remove/)(const [CapturePtr](../captureptr/)\&) override | Inaktiverar förändring av samlingen. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | Tar bort första instansen av ett specifikt objekt från listan. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Tar bort alla element som matchar ett specifikt predikat. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | Tar bort objekt på angiven position. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | Tar bort ett snitt av listan. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | Hämtar en omvänd iterator för ett icke-existerande element före början av samlingen. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | Hämtar en omvänd iterator för ett icke-existerande element före början av den konstant-kvalificerade samlingen. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | Vänder på elementordningen för hela listan. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | Vänder på elementordningen för listsnittet. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | Sätter listkapacitet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (snarare än delad). Tillåter byte av pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Sorterar element i listan. |
| void [Sort](../../system.collections.generic/list/sort/)() | Sorterar element i listan med standardkomparator. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Sorterar element i listsnittet. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sorterar element i listan. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | Konverterar lista till array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog av C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | Ställer in listkapaciteten så att den matchar dess storlek. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Bestämmer om varje element i samlingen matchar villkoren definierade av det angivna predikatet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | Hämtar implementationen av end const-iterator för den aktuella containern. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | Hämtar implementationen av end-iterator för den aktuella containern. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [Base](./base/) | Bastyp. |

## Se även

* Klass [List](../../system.collections.generic/list/)
* Namnrymd [System::Text::RegularExpressions](../)
* Bibliotek [Aspose.Slides](../../)