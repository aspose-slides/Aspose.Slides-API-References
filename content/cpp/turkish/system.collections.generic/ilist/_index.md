---
title: IList
second_title: Aspose.Slides for C++ API Referansı
description: "Elemanların indeksli konteynerinin arabirimi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığında veya new operatörüyle asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 339
url: /tr/system.collections.generic/ilist/
---
## IList sınıf

İndeksli eleman kapsayıcısının arabirimi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığında veya new operatörüyle asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Eleman tipi. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T\&) | Koleksiyona eleman ekler. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Koleksiyonun (varsa) ilk elemanına işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) bir T kopya-nesnesi döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Koleksiyonun const nitelikli örneğinin (varsa) ilk elemanına işaret eden yineleyiciyi alır. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Koleksiyonun (varsa) ilk const nitelikli elemanına işaret eden yineleyiciyi alır. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Koleksiyonun (varsa) son const nitelikli elemanından hemen sonra işaret eden yineleyiciyi alır. |
| virtual void [Clear](../icollection/clear/)() | Koleksiyondaki tüm elemanları siler. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Elemanın koleksiyonda mevcut olup olmadığını kontrol eder. |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Koleksiyon elemanlarının tümünü mevcut dizi elemanlarına kopyalar. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Koleksiyonun (varsa) son elemanından hemen sonra işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) bir T kopya-nesnesi döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Koleksiyonun const nitelikli örneğinin (varsa) son elemanından hemen sonra işaret eden yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiğine göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türündeki nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı çift nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual int [get_Count](../icollection/get_count/)() const | Koleksiyondaki eleman sayısını alır. |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() | Koleksiyonun sabit boyutlu olup olmadığını kontrol eder. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Koleksiyonun sadece okunur olup olmadığını kontrol eder. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | Yineleyiciyi alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [ICollection](../icollection/icollection/)() | Varsayılan yapıcı. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopya yapıcı. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Taşıma yapıcı. |
| virtual T [idx_get](./idx_get/)(int) const | Belirtilen indeksteki elemanı alır. |
| virtual void [idx_set](./idx_set/)(int, T) | Belirtilen indeksteki elemanı ayarlar. |
| virtual int [IndexOf](./indexof/)(const T\&) const | Elemanın konteynerdeki ilk göründüğü indeksi alır. |
| virtual void [Insert](./insert/)(int, const T\&) | Elemanı belirtilen konuma ekler, diğer elemanları kaydırır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici işlev uygular. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm elemanların bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bir dizinin herhangi bir eleman içerip içermediğini belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizideki herhangi bir elemanın var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Girdi dizisinin her elemanına bir dönüştürme işlevi uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Elemanları belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bir dizinin belirtilen bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Dizideki eleman sayısını döndürür (doğrudan sayma ile hesaplanır). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki eleman sayısını döndürür. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksteki elemanı döndürür. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksteki elemanı döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)() | Bir dizinin ilk elemanını döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizinin ilk elemanını döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Bir dizinin ilk elemanını, dizi boşsa varsayılan bir değerle birlikte döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Bir koşulu sağlayan dizinin ilk elemanını, böyle bir eleman bulunamazsa varsayılan değerle birlikte döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin elemanlarını gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin elemanlarını gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Bir dizinin son elemanını döndürür. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Bir dizinin son elemanını, dizi boşsa varsayılan bir değerle birlikte döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizideki her elemana bir dönüştürme işlevi uygular ve en büyük sonucu döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizideki her elemana bir dönüştürme işlevi uygular ve en küçük sonucu döndürür. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Dizinin elemanlarını belirtilen tipe göre süzer. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin elemanlarını keySelector ile seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin elemanlarını keySelector ile seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Bir dizideki elemanların sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin elemanlarını dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her elemanını, elemanın indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her elemanını yansıtır ve elde edilen dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başından belirli sayıda ardışık elemanı atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Bir dizinin başından belirli sayıda ardışık elemanı döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Bir diziden bir dizi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Belirtilen koşula göre bir diziyi süzer. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Taşıma atama operatörü. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Taşıma atama operatörü. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özel türevi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özel türevi. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Koleksiyondan elemanı siler. |
| virtual void [RemoveAt](./removeat/)(int) | Belirtilen indeksteki elemanı kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Mevcut kapsayıcının begin const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Mevcut kapsayıcının begin yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Mevcut kapsayıcının end const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Mevcut kapsayıcının end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımlamaları

| Tip Tanımı | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | Temel tip. |
| [ThisType](./thistype/) | Bu tip. |
| [ValueType](./valuetype/) | Değer tipi. |

## Ayrıca Bakınız

* Sınıf [ICollection](../icollection/)
* İsim Uzayı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)