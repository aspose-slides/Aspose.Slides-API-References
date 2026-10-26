---
title: List
second_title: Aspose.Slides for C++ API Referansı
description: List ileri bildirim.
type: docs
weight: 430
url: /tr/system.collections.generic/list/
---
## List sınıfı

[List](./) ileri bildirim.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Eleman türü. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++'a özgü. |
| void [Add](./add/)(const T\&) override | Liste sonuna eleman ekler. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Liste eleman ekler; başlatıcıların çevrilmesinde kullanılır. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Koleksiyondan (veya kendisinden) tüm elemanları mevcut listenin sonuna ekler. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Bu koleksiyona salt okunur referans alır. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Koleksiyonun ilk elemanına iteratör alır. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Sabit nitelikli koleksiyonun ilk elemanına iteratör alır. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Sıralı listede öğeyi arar. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Sıralı listede öğeyi arar. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Sıralı listede öğeyi arar. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Koleksiyonun ilk sabit nitelikli elemanına iteratör alır. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Koleksiyonun sonundan sonraki mevcut olmayan sabit nitelikli eleman için iteratör alır. |
| void [Clear](./clear/)() override | Tüm elemanları siler. |
| **bool** [Contains](./contains/)(const T\&) const override | Listenin içinde öğenin var olup olmadığını kontrol eder. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Farklı türe dönüştürülmüş elemanların bir listesini oluşturur. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Liste elemanlarını mevcut dizi elemanlarına kopyalar. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Tüm elemanları mevcut dizi elemanlarına kopyalar. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Belirtilen indeksden başlayarak elemanları mevcut dizi elemanlarına kopyalar. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Koleksiyonun son sabit nitelikli elemanına (ters sırada ilk) ters iteratör alır. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Koleksiyonun başından önceki mevcut olmayan sabit nitelikli eleman için ters iteratör alır. |
| [vector_t](./vector_t/)\& [data](./data/)() | Alt veri yapısına erişim işlevi. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Alt veri yapısına erişim işlevi. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Koleksiyonun sonundan sonraki mevcut olmayan eleman için iteratör alır. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Sabit nitelikli koleksiyonun sonundan sonraki mevcut olmayan eleman için iteratör alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir, ancak iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir, ancak iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Liste içinde belirli bir koşula uyan elemanın var olup olmadığını kontrol eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan elemanı arar. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan elemanları arar. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan elemanı arar. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan elemanı arar. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan elemanı arar. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan son elemanı arar. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Listedeki tüm elemanlara eylemi uygular. |
| int [get_Capacity](./get_capacity/)() const | Mevcut listenin kapasitesini alır. |
| int [get_Count](./get_count/)() const override | Mevcut listedeki eleman sayısını alır. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Koleksiyonun sabit boyutta olup olmadığını kontrol eder. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Koleksiyonun sadece okunur olup olmadığını kontrol eder. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Liste elemanları üzerinde yineleme yapmak için Enumerator alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Listenin bir dilimini oluşturur. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
|  [ICollection](../icollection/icollection/)() | Varsayılan yapıcı. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopya yapıcı. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Taşıma yapıcı. |
| T [idx_get](./idx_get/)(int) const override | Belirli konumdaki elemanı alır. |
| void [idx_set](./idx_set/)(int, T) override | Belirli konumdaki elemanı ayarlar. |
| int [IndexOf](./indexof/)(const T\&) const override | Belirli öğenin ilk indeksini alır. |
| int [IndexOf](./indexof/)(const T\&, int) const | Listede belirli öğeyi arar. |
| void [Insert](./insert/)(int, const T\&) override | Belirtilen konuma öğeyi ekler. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Belirli konuma veri aralığını ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Belirtilen nesneyi arar ve tüm listede son görülen konumunun sıfır tabanlı indeksini döndürür. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Belirtilen nesneyi arar ve [List](./) içinde, ilk elemandan belirtilen indekse kadar uzanan aralıktaki son görülen konumunun sıfır tabanlı indeksini döndürür. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Belirtilen nesneyi arar ve [List](./) içinde, belirtilen sayıda eleman içeren ve belirtilen indekste sona eren aralıktaki son görülen konumunun sıfır tabanlı indeksini döndürür. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir toplama fonksiyonu uygular. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm elemanların bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bir dizinin herhangi bir eleman içerip içermediğini belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizide herhangi bir elemanın var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Girdi dizisinin her elemanına bir dönüşüm fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Elemanları belirtilen türe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bir dizinin belirli bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Dizi eleman sayısını döndürür (doğrudan sayma ile hesaplanır). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizi eleman sayısını döndürür. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksdeki elemanı döndürür. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksdeki elemanı döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)() | Bir dizinin ilk elemanını döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan bir dizinin ilk elemanını döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Bir dizinin ilk elemanını döndürür; dizi boşsa varsayılan bir değer. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Koşulu sağlayan dizinin ilk elemanını döndürür; bulunamazsa varsayılan değer. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin elemanlarını gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin elemanlarını gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Bir dizinin son elemanını döndürür. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Bir dizinin son elemanını döndürür; dizi boşsa varsayılan bir değer. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her elemanına bir dönüşüm fonksiyonu uygular ve elde edilen maksimum değeri döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her elemanına bir dönüşüm fonksiyonu uygular ve elde edilen minimum değeri döndürür. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Dizi elemanlarını belirtilen türe göre filtreler. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector tarafından seçilen anahtar değerlerine göre bir dizinin elemanlarını artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector tarafından seçilen anahtar değerlerine göre bir dizinin elemanlarını azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Bir dizinin eleman sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin elemanlarını dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her elemanını, elemanın indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her elemanını projekte eder ve ortaya çıkan dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda ardışık elemanı atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda ardışık elemanı döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Bir diziden bir dizi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Bir diziden List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
|  [List](./list/)() | Boş liste oluşturur. |
|  [List](./list/)(int) | Öncedefineli kapasiteyle liste oluşturur. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Kopya yapıcı. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapıcı ile oluşturulmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapıcı ile oluşturulmasını sağlar. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Taşıma atama operatörü. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Taşıma atama operatörü. |
| vector_t::reference [operator[]](./operator[]/)(int) | Erişim işlevi. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Erişim işlevi. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Koleksiyonun son elemanına (ters sırada ilk) ters iteratör alır. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Sabit nitelikli koleksiyonun son elemanına (ters sırada ilk) ters iteratör alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel örneklemesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel örneklemesi. |
| **bool** [Remove](./remove/)(const T\&) override | Listeden belirli bir öğenin ilk örneğini kaldırır. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Belirli bir koşula uyan tüm elemanları kaldırır. |
| void [RemoveAt](./removeat/)(int) override | Belirtilen konumdaki öğeyi kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemoveRange](./removerange/)(int, int) | Listenin bir dilimini kaldırır. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Koleksiyonun başlangıcından önceki mevcut olmayan eleman için ters iteratör alır. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Sabit nitelikli koleksiyonun başlangıcından önceki mevcut olmayan eleman için ters iteratör alır. |
| void [Reverse](./reverse/)() | Tüm listenin eleman sırasını tersine çevirir. |
| void [Reverse](./reverse/)(int, int) | Liste diliminin eleman sırasını tersine çevirir. |
| void [set_Capacity](./set_capacity/)(int) | Listenin kapasitesini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n. şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Listedeki elemanları sıralar. |
| void [Sort](./sort/)() | Listedeki elemanları varsayılan karşılaştırıcı ile sıralar. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Liste dilimindeki elemanları sıralar. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Listedeki elemanları sıralar. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Listeyi diziye dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| void [TrimExcess](./trimexcess/)() | Listenin kapasitesini boyutuna göre ayarlar. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Koleksiyondaki her elemanın belirtilen koşulları karşılayıp karşılamadığını belirler. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için sabit begin iteratörünün uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin iteratörünün uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için sabit end iteratörünün uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end iteratörünün uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [ValueType](./valuetype/) | Bu tip. |
| [BaseType](./basetype/) | Arayüz tipi. |
| [vector_t](./vector_t/) | Alt veri tipi. |
| [iterator](./iterator/) | İteratör tipi. |
| [const_iterator](./const_iterator/) | Sabit iteratör tipi. |
| [reverse_iterator](./reverse_iterator/) | Ters iteratör tipi. |
| [const_reverse_iterator](./const_reverse_iterator/) | Sabit ters iteratör tipi. |
| [IEnumerablePtr](./ienumerableptr/) | Aynı tipe sahip elemanları tutan konteyner. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** tipi. |

## Açıklamalar

[List](./) - çevrilmiş kodda kullanılacak std::vector sarmalayıcısı. Eleman türü için operator == uygulanması gerekir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu ile allocate edilmelidir. Bu tipin bir örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // İlk listeyi oluştur.
  auto list1 = MakeObject<List<int>>();

  // İlk listeyi doldur.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // İlk listeyi sırala.
  // İlk listedeki öğeler: {-5, 1, 3, 8}
  list1->Sort();

  // 2. indeksteki öğeyi kaldır.
  // İlk listedeki öğeler: {-5, 1, 8}
  list1->RemoveAt(2);

  // 1. indekse öğeyi ekle.
  // İlk listedeki öğeler: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // İkinci listeyi oluştur.
  auto list2 = MakeObject<List<int>>();

  // İkinci listeyi doldur.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // İkinci listedeki elemanları birincisine ekle.
  list1->AddRange(list2);

  // İlk listedeki öğeleri yazdır.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
- 5 15 1 8 10 20 30
*/
```

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Sınıf [IList](../ilist/)
* İsim alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)