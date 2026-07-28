---
title: Array
second_title: Aspose.Slides C++ API Referencia
description: "Egy tömb adatstruktúrát reprezentáló osztály. Ennek az osztálynak az objektumait csak a System::MakeArray() és a System::MakeObject() függvényekkel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new segítségével, mivel ez futási időbeli hibákhoz és/vagy assert hibákhoz vezet. Mindig csomagolja be ezt az osztályt a System::SmartPtr mutatóba, és ezt a mutatót használja a függvények argumentumaként."
type: docs
weight: 14
url: /hu/system/array/
---
## Array osztály

Class that represents an array data structure. Objects of this class should only be allocated using [System::MakeArray()](../makearray/) and [System::MakeObject()](../makeobject/) functions. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Template parameters

| Paraméter | Leírás |
| --- | --- |
| T | Type of elements of an array |

## Methods

| Metódus | Leírás |
| --- | --- |
| void [Add](./add/)(const T\&) override | Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható. |
|  [Array](./array/)() | Üres tömböt hoz létre. |
|  [Array](./array/)(int, const T\&) | Kitöltő konstruktor. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Kitöltő konstruktor. |
|  [Array](./array/)(int, const T) | Kitöltő konstruktor. |
|  [Array](./array/)(**vector_t**\&&) | Mozgató konstruktor. |
|  [Array](./array/)(const **vector_t**\&) | Másoló konstruktor. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Hozzá egy [Array](./) objektumot, és feltölti olyan értékekkel, amelyeket egy std::vector objektumból másolt, amelynek értéktípusa megegyezik **T**-vel, de eltér **UnderlyingType**-tól. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Létrehoz egy [Array](./) objektumot, és feltölti olyan értékekkel, amelyeket egy std::vector objektumból mozgatott, amelynek értéktípusa megegyezik **T**-vel, de eltér **UnderlyingType**-tól. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Létrehoz egy [Array](./) objektumot, és feltölti a megadott initializer listából származó **UnderlyingType** típusú elemekkel. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Létrehoz egy [Array](./) objektumot, és feltölti a megadott tömbből származó **UnderlyingType** típusú elemekkel. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Létrehoz egy [Array](./) objektumot, és feltölti a megadott initializer listából származó **bool** típusú elemekkel. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Átalakítja a tömböt csak olvasható gyűjteményé. |
| [iterator](./iterator/) [begin](./begin/)() | Visszaad egy iterátort a tároló első elemére. Ha a tároló üres, a visszaadott iterátor egyenlő lesz [end()](./end/)-val. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Visszaad egy iterátort a const-kvalifikált tároló első elemére. Ha a tároló üres, a visszaadott iterátor egyenlő lesz [end()](./end/)-val. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Bináris keresést hajt végre a rendezett tömbön. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NINCS IMPLEMENTÁLVA. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Visszaad egy iterátort a tároló első const-kvalifikált elemére. Ha a tároló üres, a visszaadott iterátor egyenlő lesz [cend()](./cend/)-val. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Visszaad egy iterátort a tároló utolsó elemét követő elemre. Ez az elem helykitöltőként működik; megkísérlése hozzáférni meghatározott viselkedéshez vezet. |
| void [Clear](./clear/)() override | Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | A megadott tömbben a **startIndex** indexnél kezdődő **count** értéket alapértelmezett értékekkel helyettesíti. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Klónozza a tömböt. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Másol egy elemtartományt egy [System.Array](./)-ból, a megadott forrástól kezdve. |
| **bool** [Contains](./contains/)(const T\&) const override | Megállapítja, hogy a megadott elem benne van-e a tömbben. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Létrehoz egy új [Array](./) objektumot, és feltölti a megadott tömb elemeivel, amelyeket a megadott konverter delegát használatával **OutputType** típusra konvertál. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Létrehoz egy új [Array](./) objektumot, és feltölti a megadott tömb elemeivel, amelyeket a megadott konverter függvényobjektum **OutputType** típusra konvertál. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | A megadott számú elemet átmásolja a forrás tömbből a cél tömbbe. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Átmásolja a megadott számú elemet a forrás tömb nézetből a cél tömbbe. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | A megadott számú elemet átmásolja a forrás tömbből a cél tömb nézetbe. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | A megadott számú elemet átmásolja a forrás tömb nézetből a cél tömb nézetbe. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | A megadott számú elemet átmásolja a veremben lévő forrás tömbből a cél tömbbe. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | A megadott számú elemet átmásolja a forrás tömbből a veremben lévő cél tömbbe. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | A megadott számú elemet átmásolja a forrás veremtömbből a cél veremtömbbe. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a forrás tömbből, a megadott indexnél kezdve, a cél tömb megadott pozíciójába. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a forrás tömb nézetből, a megadott indexnél kezdve, a cél tömb megadott pozíciójába. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a forrás tömbből, a megadott indexnél kezdve, a cél tömb nézet megadott pozíciójába. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a forrás tömb nézetből, a megadott indexnél kezdve, a cél tömb nézet megadott pozíciójába. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a veremben lévő forrás tömbből, a megadott indexnél kezdve, a cél tömb megadott pozíciójába. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a forrás tömbből, a megadott indexnél kezdve, a veremben lévő cél tömb megadott pozíciójába. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a veremben lévő forrás tömbből, a megadott indexnél kezdve, a veremben lévő cél tömb megadott pozíciójába. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | A megadott számú elemet átmásolja a forrás tömb nézetből, a megadott indexnél kezdve, a veremben lévő cél tömb megadott pozíciójába. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Az aktuális tömb összes elemét átmásolja a megadott cél tömbbe. Az elemek a cél tömbbe a **arrayIndex** argumentummal megadott indexnél kezdődően kerülnek beszúrásra. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Az aktuális tömb összes elemét átmásolja a megadott cél tömbbe. Az elemek a cél tömbbe a **dstIndex** argumentummal megadott indexnél kezdődően kerülnek beszúrásra. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Az aktuális tömb összes elemét átmásolja a megadott cél tömb nézetbe. Az elemek a cél tömb nézetbe a **dstIndex** argumentummal megadott indexnél kezdődően kerülnek beszúrásra. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | A megadott számú elemet átmásolja az aktuális tömbből, a megadott pozíciótól kezdve, a megadott cél tömbbe. Az elemek a cél tömbbe a **dstIndex** argumentummal megadott indexnél kezdődően kerülnek beszúrásra. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | A megadott számú elemet átmásolja az aktuális tömbből, a megadott pozíciótól kezdve, a megadott cél tömb nézetbe. Az elemek a cél tömb nézetbe a **dstIndex** argumentummal megadott indexnél kezdődően kerülnek beszúrásra. |
| int [Count](./count/)() const | Visszaad egy számot, amely a tömb minden dimenziójában található összes elem számát jelenti. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Visszaad egy fordított iterátort a megfordított tároló első elemére. Ez a nem megfordított tároló utolsó elemének felel meg. Ha a tároló üres, a visszaadott iterátor egyenlő lesz [crend()](./crend/)-val. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Visszaad egy fordított iterátort a megfordított tároló utolsó elemét követő elemre. Ez a nem megfordított tároló első elemét megelőző elemnek felel meg. Ez az elem helykitöltőként működik, megkísérlése hozzáférni meghatározott viselkedéshez vezet. |
| **vector_t**\& [data](./data/)() | Visszaad egy referenciát a tömb elemeinek tárolására használt belső adatstruktúrára. |
| const **vector_t**\& [data](./data/)() const | Visszaad egy konstans referenciát a tömb elemeinek tárolására használt belső adatstruktúrára. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Visszaad egy nyers mutatót a memória buffer elejére, ahol a tömb elemei tárolódnak. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Visszaad egy konstans nyers mutatót a memória buffer elejére, ahol a tömb elemei tárolódnak. |
| [iterator](./iterator/) [end](./end/)() | Visszaad egy iterátort a tároló utolsó elemét követő elemre. Ez az elem helykitöltőként működik; megkísérlése hozzáférni meghatározott viselkedéshez vezet. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Visszaad egy iterátort a const-kvalifikált tároló utolsó elemét követő elemre. Ez az elem helykitöltőként működik; megkísérlése hozzáférni meghatározott viselkedéshez vezet. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Megállapítja, hogy a megadott [Array](./) objektum tartalmaz-e olyan elemet, amely megfelel a megadott predikátum követelményeinek. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Megkeresi a megadott tömbben az első olyan elemet, amely megfelel a megadott predikátum feltételeinek. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Visszaadja az összes olyan elemet, amely megfelel a megadott predikátum által definiált feltételeknek. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Megkeresi a megadott tömbben az első olyan elemet, amely megfelel a megadott predikátum feltételeinek. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Végrehajtja a megadott műveletet a megadott tömb minden elemén. |
| int [get_Count](./get_count/)() const override | Visszaadja a tömb méretét. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény rögzített méretű-e. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Megadja, hogy a tömb csak olvasható-e. |
| **int32_t** [get_Length](./get_length/)() const override | Visszaad egy 32-bites egész számot, amely a tömb minden dimenziójában lévő összes elem számát jelenti. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Visszaad egy 64-bites egész számot, amely a tömb minden dimenziójában lévő összes elem számát jelenti. |
| **int32_t** [get_Rank](./get_rank/)() const | NINCS MEGVALÓSÍTVA. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Lekéri azt az objektumot, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Visszaad egy mutatót a **Enumerator** objektumra, amely IEnumerator interfészt biztosít a jelenlegi objektum által képviselt tömb elemeihez. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| int [GetLength](./getlength/)(int) | Visszaadja a megadott dimenzióban lévő elemek számát. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Visszaadja a megadott dimenzióban lévő elemek számát 64-bites egész számként. |
| int [GetLowerBound](./getlowerbound/)(int) const | Visszaadja a megadott dimenzió alsó határát. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Visszaad egy std::size_t változót, amely a tömb minden dimenziójában lévő összes elem számát jelenti. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógiája. |
| int [GetUpperBound](./getupperbound/)(int) | Visszaadja a megadott dimenzió felső határát. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Alapértelmezett konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Másoló konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Mozgató konstruktor. |
| T [idx_get](./idx_get/)(int) const override | Visszaadja a megadott indexű elemet. |
| void [idx_set](./idx_set/)(int, T) override | Beállítja a megadott értéket a tömbben a megadott indexű elemként. |
| int [IndexOf](./indexof/)(const T\&) const override | Meghatározza a megadott elem tömbben való első előfordulásának indexét. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Meghatározza a megadott elem tömbben való első előfordulásának indexét. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Meghatározza a megadott elem tömbben való első előfordulásának indexét a megadott indextől kezdve. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Meghatározza a megadott elem tömbben való első előfordulásának indexét a kezdő index és a tartomány elemeinek száma által megadott tartományban. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Kitölti a jelenlegi objektum által képviselt tömböt a megadott tömb értékeivel. |
| void [Initialize](./initialize/)() | Kitölti a tömböt a **T** típusú alapértelmezett példányokkal. |
| void [Insert](./insert/)(int, const T\&) override | Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógiája. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Meghatározza a megadott elem tömbben való utolsó előfordulásának indexét a kezdő index és a tartomány elemeinek száma által megadott tartományban. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Meghatározza a megadott elem tömbben való utolsó előfordulásának indexét a megadott indextől kezdve. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Meghatározza a megadott elem tömbben való utolsó előfordulásának indexét. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Alkalmaz egy akkumulátor függvényt egy sorozaton. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme teljesíti-e a feltételt. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e bármilyen elemet. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármelyik eleme létezik-e vagy teljesíti-e a feltételt. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Kiszámítja a numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Kiszámítja egy sorozat értékeinek átlagát, amelyeket egy transzformáló függvény minden bemeneti elemre alkalmazásával kapunk. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Átalakítja az elemeket a megadott típusra. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Összefűzi a két sorozatot. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmazza-e a megadott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással kiszámítva). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Visszaadja a sorozatban a megadott feltételt teljesítő elemek számát. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely a megadott feltételt teljesíti. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely teljesíti a feltételt, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Meghív egy transzformáló függvényt egy általános sorozat minden elemére, és visszaadja a legnagyobb eredményértéket. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Meghív egy transzformáló függvényt egy általános sorozat minden elemére, és visszaadja a legkisebb eredményértéket. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Szűri a sorozat elemeit a megadott típus alapján. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Rendezi a sorozat elemeit növekvő sorrendbe a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Rendezi a sorozat elemeit csökkenő sorrendbe a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Minden sorozatelemet átalakít egy új formába az elem indexének felhasználásával. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektálja a sorozat minden elemét, és egyesíti a kapott sorozatokat egyetlen sorozatba. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy megadott számú egymást követő elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy megadott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Létrehoz egy tömböt egy sorozatból. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Létrehoz egy List<T>-et egy sorozatból. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentinel objektumot. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Megkeresi a legnagyobb elemet a tömbben a [operator<()](../operator_less/) használatával az elemek összehasonlításához. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Megkeresi a legkisebb elemet a tömbben a [operator<()](../operator_less/) használatával az elemek összehasonlításához. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Nem másol semmit, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Nem másol semmit, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Mozgató értékadási operátor. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Mozgató értékadási operátor. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Visszaad egy elemet a megadott indexnél. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Visszaad egy elemet a megadott indexnél. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Visszaad egy mutatót az egydimenziós tömb első elemére. Többdimenziós tömbök esetén az eredmény nem definiált. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Visszaad egy fordított iterátort a fordított tároló első eleméhez. Ez megfelel a nem fordított tároló utolsó elemének. Ha a tároló üres, a visszaadott iterátor egyenlő lesz a [rend()](./rend/)-val. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Visszaad egy fordított iterátort a megfordított tároló első eleméhez. Ez megfelel a nem megfordított tároló utolsó elemének. Ha a tároló üres, a visszaadott iterátor egyenlő [rend()](./rend/)-val. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) speciális változata string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| **bool** [Remove](./remove/)(const T\&) override | Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható. |
| void [RemoveAt](./removeat/)(int) override | Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Visszaad egy fordított iterátort a megfordított tároló utolsó elemét követő elemhez. Ez megfelel a nem megfordított tároló első elemét megelőző elemnek. Ez az elem helykitöltőként szolgál, hozzáférés megkísérlése meghatározatlan viselkedéshez vezet. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Visszaad egy fordított iterátort a megfordított tároló utolsó elemét követő elemhez. Ez megfelel a nem megfordított tároló első elemét megelőző elemnek. Ez az elem helykitöltőként szolgál, hozzáférés megkísérlése meghatározatlan viselkedéshez vezet. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Megváltoztatja a megadott tömb méretét a megadott értékre, vagy a megadott mérettel új tömböt hoz létre. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Megfordítja a megadott tömb elemeit. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Megfordít egy elemtartományt a megadott tömbben. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | A tömb a tárolt mutatókat gyengének tekinti (ha alkalmazható). |
| void [SetValue](./setvalue/)(const T\&, int) | Beállítja a megadott indexű elem értékét. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Az alapértelmezett összehasonlítóval rendezi a megadott tömb elemeit. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Az alapértelmezett összehasonlítóval rendezi a megadott tömb egy elemtartományát. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | A megadott összehasonlítóval rendezi a megadott tömb elemeit. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NINCS MEGVALÓSÍTVA. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | A megadott összehasonlítással rendezi a megadott tömb elemeit. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Két tömböt rendez, az egyik kulcsokat, a másik a hozzájuk tartozó elemeket tartalmazza, a kulcsokat tartalmazó tömb értékei alapján, mely elemeket az operator< használja összehasonlításra. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Két tömböt rendez, az egyik kulcsokat, a másik a hozzájuk tartozó elemeket tartalmazza, a kulcsokat tartalmazó tömb értékei alapján, mely elemeket az alapértelmezett összehasonlító használja. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | A C# [Object.ToString()](../object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Megállapítja, hogy a megadott tömb minden eleme megfelel-e a megadott predikátum által definiált feltételeknek. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) szerkezetet. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Lekéri a jelenlegi tároló begin const iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Lekéri a jelenlegi tároló begin iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Lekéri a jelenlegi tároló end const iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Lekéri a jelenlegi tároló end iterátorának megvalósítását. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Megsemmisítő. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Typedef | Leírás |
| --- | --- |
| [ValueType](./valuetype/) | Álnév a tömb elemeinek típusára. |
| [UnderlyingType](./underlyingtype/) | Álnév a tömb egyes elemeinek típusának ábrázolására használt típusra. |
| [EnumerablePtr](./enumerableptr/) | Álnév a **T** típusú elemeket tartalmazó IEnumerable objektumra mutató megosztott mutató típusra. |
| [EnumeratorPtr](./enumeratorptr/) | Álnév a **T** típusú elemeket tartalmazó IEnumerator objektumra mutató megosztott mutató típusra. |
| [iterator](./iterator/) | Iterátor típus. |
| [const_iterator](./const_iterator/) | Konstans iterátor típus. |
| [reverse_iterator](./reverse_iterator/) | Fordított iterátor típus. |
| [const_reverse_iterator](./const_reverse_iterator/) | Konstans fordított iterátor típus. |

## Megjegyzések

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Létrehozza és feltölti a tömböt.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Kiírja a tömb elemeit.
  Print(arrayPtr);

  // Rendezi a tömb elemeit növekvő sorrendbe.
  Array<int32_t>::Sort(arrayPtr);

  // Kiírja a tömb elemeit.
  Print(arrayPtr);

  // Kiírja a tömb elemeinek számát.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Kiírja az 4-nek megfelelő elem indexét.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Átméretezi a tömböt.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Kiírja a tömb elemeit.
  Print(arrayPtr);

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet állítja elő:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Lásd még

* Osztály [ArrayBase](../arraybase/)
* Osztály [IList](../../system.collections.generic/ilist/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)