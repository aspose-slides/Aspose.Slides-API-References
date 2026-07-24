---
title: SoapHeaderCollection
second_title: Aspose.Slides for C++ API Referansı
description: SoapHeader sınıfının örneklerinden oluşan bir koleksiyon içerir.
type: docs
weight: 105
url: /tr/system.web.services.protocols/soapheadercollection/
---
## SoapHeaderCollection sınıfı


İçinde [SoapHeader](../soapheader/) sınıfının örneklerinden oluşan bir koleksiyon bulunur.

```cpp
class SoapHeaderCollection : public System::Collections::Generic::List<System::SharedPtr<SoapHeader>>
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | C++'a özgü. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Listedeki sonuna öğe ekler. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Listedeki öğeleri ekler; başlatıcıların çevrilmesi sırasında kullanılır. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Koleksiyondaki (veya kendisindeki) tüm öğeleri mevcut listenin sonuna ekler. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Bu koleksiyona yalnızca okunabilir bir referans alır. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Koleksiyonun ilk öğesine bir yineleyici alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Const niteliğine sahip koleksiyonun ilk öğesine bir yineleyici alır. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Sıralı listede öğeyi arar. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Sıralı listede öğeyi arar. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Sıralı listede öğeyi arar. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Koleksiyonun const niteliğine sahip ilk öğesine bir yineleyici alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Koleksiyonun sonundan sonraki var olmayan const niteliğine sahip bir öğe için yineleyici alır. |
| void [Clear](../../system.collections.generic/list/clear/)() override | Tüm öğeleri siler. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Öğenin listede olup olmadığını denetler. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Farklı bir türe dönüştürülmüş öğelerden bir liste oluşturur. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Liste öğelerini mevcut dizi öğelerine kopyalar. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Tüm öğeleri mevcut dizi öğelerine kopyalar. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Belirtilen indeksten başlayan öğeleri mevcut dizi öğelerine kopyalar. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Koleksiyonun son const niteliğine sahip öğesine (ters sırada ilk) ters bir yineleyici alır. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Koleksiyonun başlangıcından önceki var olmayan const niteliğine sahip bir öğe için ters bir yineleyici alır. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Altta yatan veri yapısına erişim fonksiyonu. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Altta yatan veri yapısına erişim fonksiyonu. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Koleksiyonun sonundan sonraki var olmayan bir öğe için yineleyici alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Koleksiyonun const niteliğine sahip sonundan sonraki var olmayan bir öğe için yineleyici alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, IEC 60559:1989'da NaN'in hiçbir değere, NaN dahil, eşit olmadığı belirtilse de. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, IEC 60559:1989'da NaN'in hiçbir değere, NaN dahil, eşit olmadığı belirtilse de. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan öğenin listede bulunup bulunmadığını denetler. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan öğeyi arar. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan öğeleri arar. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan öğeyi arar. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan öğeyi arar. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan öğeyi arar. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan son öğeyi arar. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Listedeki tüm öğelere eylem uygular. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | Mevcut liste kapasitesini alır. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | Mevcut listedeki öğe sayısını alır. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Koleksiyonun sabit boyutlu olup olmadığını denetler. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Koleksiyonun yalnızca okunabilir olup olmadığını denetler. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkilendirilmiş referans sayacı veri yapısını alır. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Liste öğeleri üzerinden yinelemeye yarayan enumerator alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yöntemi analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | Listenin bir dilimini oluşturur. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Varsayılan kurucu. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopya kurucu. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Taşıma kurucu. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Belirli konumdaki öğeyi alır. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Belirli konumdaki öğeyi ayarlar. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Belirli bir öğenin ilk indeksini alır. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Listede belirli bir öğeyi arar. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Öğeyi belirtilen konuma ekler. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Veri aralığını belirtilen konuma ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Belirtilen nesneyi arar ve tüm listedeki son oluşumun sıfırdan başlayan indeksini döndürür. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | [List](../../system.collections.generic/list/) içinde, ilk öğeden belirtilen indekse kadar uzanan öğe aralığında belirtilen nesneyi arar ve son oluşumun sıfırdan başlayan indeksini döndürür. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | [List](../../system.collections.generic/list/) içinde, belirtilen sayıda öğe içeren ve belirtilen indekste sona eren aralıkta belirtilen nesneyi arar ve son oluşumun sıfırdan başlayan indeksini döndürür. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici fonksiyonu uygular. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizide herhangi bir öğenin mevcut olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Girdi dizisindeki her öğeye bir dönüşüm fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Öğeleri belirtilen türe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bir dizinin belirli bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Dizideki öğe sayısını döndürür (doğrudan sayım yoluyla hesaplanır). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Dizide belirtilen koşulu sağlayan öğe sayısını döndürür. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksdeki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksdeki öğeyi döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini döndürür; dizin boşsa varsayılan bir değer döner. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Bir koşulu sağlayan dizinin ilk öğesini döndürür; böyle bir öğe bulunmazsa varsayılan değer döner. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin öğelerini gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin öğelerini gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini döndürür; dizin boşsa varsayılan bir değer döner. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine bir dönüşüm fonksiyonu uygular ve en büyük elde edilen değeri döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine bir dönüşüm fonksiyonu uygular ve en küçük elde edilen değeri döndürür. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen türe göre filtreler. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector tarafından seçilen anahtar değerlerine göre bir dizinin öğelerini artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector tarafından seçilen anahtar değerlerine göre bir dizinin öğelerini azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Bir dizinin öğelerinin sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin öğelerini dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her öğesini, öğenin indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini projekte eder ve elde edilen dizileri tek bir dizi halinde birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık öğeyi atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık öğeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Bir diziden bir dizi (array) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Bir diziden List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
|  [List](../../system.collections.generic/list/list/)() | Boş bir liste oluşturur. |
|  [List](../../system.collections.generic/list/list/)(int) | Önceden tanımlı kapasiteli bir liste oluşturur. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Kopya kurucu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını (klonlanmasını) sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Taşıma atama operatörü. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Taşıma atama operatörü. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Erişim fonksiyonu. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Erişim fonksiyonu. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Koleksiyonun son öğesine (ters sırada ilk) ters bir yineleyici alır. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Const niteliğine sahip koleksiyonun son öğesine (ters sırada ilk) ters bir yineleyici alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un stringler için özelleştirmesi. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | Listeden belirli öğenin ilk örneğini kaldırır. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan tüm öğeleri kaldırır. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | Belirtilen konumdaki öğeyi kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | Listenin bir dilimini kaldırır. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | Koleksiyonun başlangıcından önceki var olmayan bir öğe için ters bir yineleyici alır. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | Const niteliğine sahip koleksiyonun başlangıcından önceki var olmayan bir öğe için ters bir yineleyici alır. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | Tüm listenin öğe sırasını tersine çevirir. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | Liste diliminin öğe sırasını tersine çevirir. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | Liste kapasitesini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf bir işaretçi olarak ayarlar. Kaplardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [SoapHeaderCollection](./soapheadercollection/)() | [SoapHeaderCollection](./) sınıfının yeni bir örneğini başlatır. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Listedeki öğeleri sıralar. |
| void [Sort](../../system.collections.generic/list/sort/)() | Varsayılan karşılaştırıcıyı kullanarak listede öğeleri sıralar. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Liste dilimindeki öğeleri sıralar. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Listedeki öğeleri sıralar. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | Listeyi diziye dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | Liste kapasitesini boyutuna uydurur. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Koleksiyondaki tüm öğelerin belirtilen koşulu sağlayıp sağlamadığını belirler. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [List](../../system.collections.generic/list/)
* İsim Alanı [System::Web::Services::Protocols](../)
* Kütüphane [Aspose.Slides](../../)