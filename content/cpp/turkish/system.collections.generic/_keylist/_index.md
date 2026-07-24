---
title: _KeyList
second_title: Aspose.Slides için C++ API Referansı
description: "Sözlüğün anahtarlarının listesini uygular. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün bir örneğini yığına (stack) veya new operatörüyle asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 14
url: /tr/system.collections.generic/_keylist/
---
## _KeyList sınıf

Sözlüğün anahtarlarının listesini uygular. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün bir örneğini yığına (stack) veya new operatörüyle asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename Dict>class _KeyList : public System::Collections::Generic::_KeyCollection<Dict>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) tipi. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [_KeyCollection](../_keycollection/_keycollection/)(const typename Dict::Ptr&) | Belirtilen sözlüğe referans veren koleksiyonu başlatır. |
|  [_KeyList](./_keylist/)(const typename Dict::Ptr&) | Belirtilen sözlüğe referans veren koleksiyonu başlatır. |
| void [Add](../ikvcollection/add/)(const T&) override | Öğeyi kapsayıcıya ekler. |
|  [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr&) | Koleksiyon oluşturur. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Koleksiyondaki (varsa) ilk öğeyi gösteren yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) T'nin bir kopya-nesnesini döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Koleksiyonun const nitelikli örneğinde (varsa) ilk öğeyi gösteren yineleyiciyi alır. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Koleksiyondaki (varsa) ilk const nitelikli öğeyi gösteren yineleyiciyi alır. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Koleksiyondaki (varsa) son const nitelikli öğenin hemen sonrasını gösteren yineleyiciyi alır. |
| void [Clear](../ikvcollection/clear/)() override | Kapsayıcıdaki tüm öğeleri siler. |
| **bool** [Contains](./contains/)(const [TKey](../_keycollection/tkey/)&) const override | Belirtilen anahtarın koleksiyonda mevcut olup olmadığını kontrol eder. |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)<KV>, int) override | Verileri mevcut dizi öğelerine kopyalar. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Koleksiyondaki (varsa) son öğenin hemen sonrasını gösteren yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) T'nin bir kopya-nesnesini döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Koleksiyonun const nitelikli örneğinde (varsa) son öğenin hemen sonrasını gösteren yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmaması gerektiği halde iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmaması gerektiği halde iki NaN'ın eşit kabul edildiği C# tarzı çift duyarlıklı (double) karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Yalnızca dahili amaçlar için. |
| int [get_Count](../basekvcollection/get_count/)() const override | Öğe sayısını alır. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Koleksiyonun sabit boyutlu olup olmadığını kontrol eder. |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | Kapsayıcının sadece okunur olup olmadığını kontrol eder. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerator](../ienumerator/)<[TKey](../_keycollection/tkey/)>> [GetEnumerator](../_keycollection/getenumerator/)() override | Anahtarlar üzerinde yineleme yapan sayacı alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
|  [ICollection](../icollection/icollection/)() | Varsayılan yapıcı. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Kopya yapıcı. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Taşıma yapıcı. |
| [TKey](../_keycollection/tkey/) [idx_get](./idx_get/)(int) const override | Belirtilen konumdaki anahtarı alır. |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | Ayarlayıcı işlev. |
| int [IndexOf](../ikvcollection/indexof/)(const T&) const override | Öğenin kapsayıcıdaki indeksini alır. |
| void [Insert](../ikvcollection/insert/)(int, const T&) override | Öğeyi belirtilen konuma ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Bir dizi üzerinde bir biriktirici fonksiyon uygular. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Bir dizide herhangi bir öğenin var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Giriş dizisinin her öğesine bir dönüşüm fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Ögeleri belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bir dizinin belirtilen değeri içerip içermediğini belirler. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Dizideki öğe sayısını (doğrudan sayım yoluyla) döndürür. |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Belirtilen koşulu sağlayan dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini döndürür; dizi boşsa varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Koşulu sağlayan dizinin ilk öğesini döndürür; bulunamazsa varsayılan bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Bir dizinin öğelerini gruplar. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Bir dizinin öğelerini gruplar. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini döndürür; dizi boşsa varsayılan bir değer döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Genel bir dizinin her öğesine dönüşüm fonksiyonu uygular ve en büyük elde edilen değeri döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Genel bir dizinin her öğesine dönüşüm fonksiyonu uygular ve en küçük elde edilen değeri döndürür. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen tipe göre filtreler. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Bir dizinin öğelerinin sırasını ters çevirir. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Bir dizinin öğelerini dönüştürür. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Bir dizinin her öğesini, öğenin indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | Bir dizinin her öğesini yansıtarak elde edilen dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık öğeyi atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık öğeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Bir diziden bir dizi (array) oluşturur. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapıları başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya inşasını sağlar. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Taşıma atama operatörü. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Taşıma atama operatörü. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya inşasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| **bool** [Remove](../ikvcollection/remove/)(const T&) override | Öğeyi kapsayıcıdan kaldırır. |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | Belirtilen konumdaki öğeyi kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | Derlemeyi etkinleştirir, ancak bu yapı veri sahip olmadığı için gerçekte bir şey yapmaz. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyiminin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| System::Details::VirtualizedIteratorBase<[TKey](../_keycollection/tkey/)> * [virtualizeBeginConstIterator](../_keycollection/virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase<[TKey](../_keycollection/tkey/)> * [virtualizeBeginIterator](../_keycollection/virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase<[TKey](../_keycollection/tkey/)> * [virtualizeEndConstIterator](../_keycollection/virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase<[TKey](../_keycollection/tkey/)> * [virtualizeEndIterator](../_keycollection/virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Tip Tanımlamaları

| Tip Tanımı | Açıklama |
| --- | --- |
| [TKey](./tkey/) | Anahtar tipi. |

## İlgili

* Sınıf [_KeyCollection](../_keycollection/)
* Ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)