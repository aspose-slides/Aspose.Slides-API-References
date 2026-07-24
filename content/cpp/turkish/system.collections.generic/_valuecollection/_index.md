---
title: _ValueCollection
second_title: Aspose.Slides için C++ API Referansı
description: "Dictionary'nin değer koleksiyonu. Referans koleksiyonu, hiçbir şey kopyalamaz. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde ya da operator new ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 27
url: /tr/system.collections.generic/_valuecollection/
---
## _ValueCollection sınıfı

[Dictionary](../dictionary/) değerlerinin koleksiyonu. Referans koleksiyonu, hiçbir şey kopyalamaz. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde ya da operator new kullanarak asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi argüman olarak fonksiyonlara geçirin.

```cpp
template<typename Dict>class _ValueCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::mapped_type>
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
|  [_ValueCollection](./_valuecollection/)(const typename Dict::Ptr\&) | Belirtilen sözlüğe referans veren koleksiyonu başlatır. |
| void [Add](../ikvcollection/add/)(const T\&) override | Öğeyi konteynere ekler. |
|  [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr\&) | Koleksiyon oluşturur. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Koleksiyonun (varsa) ilk öğesini gösteren yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) bir T kopya-nesnesi döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Koleksiyonun const nitelikli örneğinin (varsa) ilk öğesini gösteren yineleyiciyi alır. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Koleksiyonun (varsa) ilk const nitelikli öğesini gösteren yineleyiciyi alır. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Koleksiyonun (varsa) son const nitelikli öğesinin hemen sonrasını gösteren yineleyiciyi alır. |
| void [Clear](../ikvcollection/clear/)() override | Tüm öğeleri konteynerden siler. |
| **bool** [Contains](./contains/)(const [TValue](./tvalue/)\&) const override | Öğenin konteynerde mevcut olup olmadığını denetler. |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | Verileri mevcut dizi öğelerine kopyalar. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Koleksiyonun (varsa) son öğesinin hemen sonrasını gösteren yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) bir T kopya-nesnesi döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Koleksiyonun const nitelikli örneğinin (varsa) son öğesinin hemen sonrasını gösteren yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift nokta kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| int [get_Count](../basekvcollection/get_count/)() const override | Öğelerin sayısını alır. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Koleksiyonun sabit boyutlu olup olmadığını denetler. |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | Konteynerin sadece okunur olup olmadığını denetler. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[TValue](./tvalue/)\>\> [GetEnumerator](./getenumerator/)() override | Değerler üzerinden yineleyen enumeratoru alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
|  [ICollection](../icollection/icollection/)() | Varsayılan kurucu. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopya kurucu. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Taşıma kurucu. |
| [TValue](./tvalue/) [idx_get](./idx_get/)(int) const override | [IList](../ilist/) metodunu uygular. Desteklenmez. |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | Ayarlayıcı işlev. |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | Öğenin konteynerdeki indeksini alır. |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | Öğeyi belirtilen konuma ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici fonksiyon uygular. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizinin tüm öğelerinin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizide herhangi bir öğenin var olup olmadığını ya da bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Giriş dizisinin her öğesine bir dönüşüm işlevi uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Öğeleri belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bir dizinin belirli bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Dizi içindeki öğe sayısını döndürür (doğrudan sayım yoluyla hesaplanır). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksdeki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksdeki öğeyi döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan bir dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini, dizi boşsa varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Bir koşulu sağlayan dizinin ilk öğesini, bulunamazsa varsayılan bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin öğelerini gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin öğelerini gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini, dizi boşsa varsayılan bir değer döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine bir dönüşüm işlevi çağırır ve elde edilen en büyük değeri döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine bir dönüşüm işlevi çağırır ve elde edilen en küçük değeri döndürür. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen tipe göre filtreler. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin öğelerini keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin öğelerini keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Bir dizinin öğelerinin sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin öğelerini dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her öğesini, öğenin indeksini ekleyerek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini projekte eder ve ortaya çıkan dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başından belirtilen sayıda ardışık öğeyi atlar ve kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Bir dizinin başından belirtilen sayıda ardışık öğeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Bir diziden bir dizi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekten hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Taşıma atama operatörü. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Taşıma atama operatörü. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumunun string ve nullptr durumunda uygulanması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumunun stringler için uygulanması. |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | Öğeyi konteynerden kaldırır. |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | Belirtilen konumdaki öğeyi kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | Derlemeyi etkinleştirir, fakat bu yapı veriye sahip olmadığından aslında bir şey yapmaz. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyiminin kilidi açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut konteyner için const begin yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut konteyner için begin yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut konteyner için const end yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut konteyner için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [TValue](./tvalue/) | Değer tipi. |

## Bkz.

* Sınıf [BaseKVCollection](../basekvcollection/)
* Ad Alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)