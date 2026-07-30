---
title: List
second_title: Aspose.Slides for C++ Reference API
description: Předběžná deklarace List.
type: docs
weight: 430
url: /cs/system.collections.generic/list/
---
## List třída


[List](./) předběžná deklarace.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvku. |
## Metody

| Metoda | Popis |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Specifické pro C++. |
| void [Add](./add/)(const T\&) override | Přidá prvek na konec seznamu. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Přidá prvky do seznamu; používá se při převodu inicializátorů. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Přidá všechny prvky ze sbírky (nebo sebe sama) na konec aktuálního seznamu. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Získá referenci jen pro čtení na tuto sbírku. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Získá iterátor na první prvek sbírky. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Získá iterátor na první prvek sbírky s kvalifikací const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Vyhledá položku ve seřazeném seznamu. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Vyhledá položku ve seřazeném seznamu. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Vyhledá položku ve seřazeném seznamu. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Získá iterátor na první prvek sbírky s kvalifikací const. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Získá iterátor na neexistující prvek s kvalifikací const za koncem sbírky. |
| void [Clear](./clear/)() override | Odstraní všechny prvky. |
| **bool** [Contains](./contains/)(const T\&) const override | Zkontroluje, zda je položka v seznamu. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Vytvoří seznam prvků převedených na jiný typ. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Zkopíruje prvky seznamu do existujících prvků pole. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Zkopíruje všechny prvky do existujících prvků pole. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Zkopíruje prvky počínaje zadaným indexem do existujících prvků pole. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Získá reverzní iterátor na poslední prvek sbírky s kvalifikací const (první v opačném směru). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Získá reverzní iterátor na neexistující prvek s kvalifikací const před začátkem sbírky. |
| [vector_t](./vector_t/)\& [data](./data/)() | Funkce přístupu k podkladové datové struktuře. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Funkce přístupu k podkladové datové struktuře. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Získá iterátor na neexistující prvek za koncem sbírky. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Získá iterátor na neexistující prvek za koncem sbírky s kvalifikací const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Zkontroluje, zda v seznamu existuje prvek splňující konkrétní predikát. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Vyhledá prvek splňující konkrétní predikát. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Vyhledá prvky splňující konkrétní predikát. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Vyhledá prvek splňující konkrétní predikát. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Vyhledá prvek splňující konkrétní predikát. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Vyhledá prvek splňující konkrétní predikát. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Vyhledá poslední prvek splňující konkrétní predikát. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Aplikuje akci na všechny prvky v seznamu. |
| int [get_Capacity](./get_capacity/)() const | Získá aktuální kapacitu seznamu. |
| int [get_Count](./get_count/)() const override | Získá počet prvků v aktuálním seznamu. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Kontroluje, zda je sbírka pevné velikosti. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Kontroluje, zda je sbírka jen pro čtení. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Získá objekt, přes který je sbírka synchronizována. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Získá enumerátor pro iteraci přes prvky seznamu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Vytvoří výřez ze seznamu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../icollection/icollection/)() | Výchozí konstruktor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopírovací konstruktor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor přesunu. |
| T [idx_get](./idx_get/)(int) const override | Získá prvek na konkrétní pozici. |
| void [idx_set](./idx_set/)(int, T) override | Nastaví prvek na konkrétní pozici. |
| int [IndexOf](./indexof/)(const T\&) const override | Získá první index konkrétní položky. |
| int [IndexOf](./indexof/)(const T\&, int) const | Vyhledá konkrétní položku v seznamu. |
| void [Insert](./insert/)(int, const T\&) override | Vloží položku na zadanou pozici. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Vloží rozsah dat na konkrétní pozici. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Vyhledá zadaný objekt a vrátí index posledního výskytu (nulový základ) v celém seznamu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Vyhledá zadaný objekt a vrátí index posledního výskytu v rozsahu prvků v [List](./), který sahá od prvního prvku po zadaný index. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Vyhledá zadaný objekt a vrátí index posledního výskytu v rozsahu prvků v [List](./), který obsahuje zadaný počet prvků a končí na zadaném indexu. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplikuje akumulátorovou funkci na posloupnost. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Určuje, zda všechny prvky posloupnosti splňují podmínku. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Určuje, zda posloupnost obsahuje nějaké prvky. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Určuje, zda existuje jakýkoli prvek posloupnosti nebo splňuje podmínku. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Vypočítá průměr posloupnosti číselných hodnot. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vypočítá průměr posloupnosti hodnot získaných voláním transformační funkce na každý prvek vstupní posloupnosti. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Přetypuje prvky na zadaný typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Spojí dvě posloupnosti. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Určuje, zda posloupnost obsahuje zadanou hodnotu. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Vrací počet prvků v posloupnosti (vypočítáno přímým počítáním). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Vrací počet prvků v posloupnosti, které splňují zadanou podmínku. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Vrací prvek na zadaném indexu v posloupnosti. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Vrací prvek na zadaném indexu v posloupnosti. |
| T [LINQ_First](../ienumerable/linq_first/)() | Vrací první prvek posloupnosti. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Vrací první prvek posloupnosti, který splňuje zadanou podmínku. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Vrací první prvek posloupnosti nebo výchozí hodnotu, pokud je posloupnost prázdná. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Vrací první prvek posloupnosti, který splňuje podmínku, nebo výchozí hodnotu, pokud žádný takový prvek není nalezen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Skupinuje prvky posloupnosti. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Skupinuje prvky posloupnosti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Vrací poslední prvek posloupnosti. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Vrací poslední prvek posloupnosti nebo výchozí hodnotu, pokud je posloupnost prázdná. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Volá transformační funkci na každý prvek obecné posloupnosti a vrací maximální výslednou hodnotu. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Volá transformační funkci na každý prvek obecné posloupnosti a vrací minimální výslednou hodnotu. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje prvky posloupnosti podle zadaného typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Řadí prvky posloupnosti vzestupně podle hodnot klíčů vybraných funkcí keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Řadí prvky posloupnosti sestupně podle hodnot klíčů vybraných funkcí keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Obrátí pořadí prvků v posloupnosti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje prvky posloupnosti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje každý prvek posloupnosti do nové formy za použití indexu prvku. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projektuje každý prvek posloupnosti a kombinuje výsledné posloupnosti do jedné. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Přeskočí zadaný počet souvislých prvků od začátku posloupnosti a vrátí zbytek. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Vrací zadaný počet souvislých prvků od začátku posloupnosti. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Vytvoří pole ze posloupnosti. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Vytvoří List<T> ze posloupnosti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje posloupnost podle zadaného predikátu. |
| [List](./list/)() | Vytvoří prázdný seznam. |
| [List](./list/)(int) | Vytvoří seznam s předdefinovanou kapacitou. |
| [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Kopírovací konstruktor. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operátor přiřazení přesunem. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operátor přiřazení přesunem. |
| vector_t::reference [operator[]](./operator[]/)(int) | Funkce přístupu. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Funkce přístupu. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Získá reverzní iterátor na poslední prvek sbírky (první v opačném směru). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Získá reverzní iterátor na poslední prvek sbírky s kvalifikací const (první v opačném směru). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| **bool** [Remove](./remove/)(const T\&) override | Odstraní první výskyt konkrétní položky ze seznamu. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Odstraní všechny prvky splňující konkrétní predikát. |
| void [RemoveAt](./removeat/)(int) override | Odstraní položku na zadané pozici. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počítadlo sdílených referencí o zadanou hodnotu. |
| void [RemoveRange](./removerange/)(int, int) | Odstraní výřez ze seznamu. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Získá reverzní iterátor na neexistující prvek před začátkem sbírky. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Získá reverzní iterátor na neexistující prvek před začátkem sbírky s kvalifikací const. |
| void [Reverse](./reverse/)() | Obrátí pořadí prvků celého seznamu. |
| void [Reverse](./reverse/)(int, int) | Obrátí pořadí prvků výřezu seznamu. |
| void [set_Capacity](./set_capacity/)(int) | Nastaví kapacitu seznamu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako weak pointer (namísto shared). Umožňuje změnu ukazatelů v kontejnerech do weak režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší počítadlo sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počítadlo sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Řadí prvky v seznamu. |
| void [Sort](./sort/)() | Řadí prvky v seznamu pomocí výchozího komparátoru. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Řadí prvky ve výřezu seznamu. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Řadí prvky v seznamu. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Převede seznam na pole. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| void [TrimExcess](./trimexcess/)() | Upraví kapacitu seznamu tak, aby odpovídala jeho velikosti. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Určuje, zda každý prvek sbírky odpovídá podmínkám definovaným zadaným predikátem. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Získá implementaci begin const iterátoru pro aktuální kontejner. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Získá implementaci begin iterátoru pro aktuální kontejner. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Získá implementaci end const iterátoru pro aktuální kontejner. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Získá implementaci end iterátoru pro aktuální kontejner. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší počítadlo weak referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počítadlo weak referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [ValueType](./valuetype/) | Tento typ. |
| [BaseType](./basetype/) | Typ rozhraní. |
| [vector_t](./vector_t/) | Podkladový datový typ. |
| [iterator](./iterator/) | Iterator typ. |
| [const_iterator](./const_iterator/) | Const iterator typ. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator typ. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator typ. |
| [IEnumerablePtr](./ienumerableptr/) | Kontejner držící prvky stejného typu, jaký držíme. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** typ. |
## Poznámky


[List](./) - obal kolem std::vector, který se používá v přeloženém kódu. Vyžaduje, aby byl pro typ prvku implementován operátor ==. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předávání jako argument funkcím.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Vytvořte první seznam.
  auto list1 = MakeObject<List<int>>();

  // Naplněte první seznam.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Seřaďte první seznam.
  // Položky prvního seznamu budou: {-5, 1, 3, 8}
  list1->Sort();

  // Odstraňte položku na indexu 2.
  // Položky prvního seznamu budou: {-5, 1, 8}
  list1->RemoveAt(2);

  // Vložte položku na index 1.
  // Položky prvního seznamu budou: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Vytvořte druhý seznam.
  auto list2 = MakeObject<List<int>>();

  // Naplněte druhý seznam.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Přidejte prvky ze druhého seznamu do prvního.
  list1->AddRange(list2);

  // Vytiskněte položky prvního seznamu.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Tento příklad kódu produkuje následující výstup:
- 5 15 1 8 10 20 30
*/
```

## Viz také

* Třída [Object](../../system/object/)
* Třída [IList](../ilist/)
* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)