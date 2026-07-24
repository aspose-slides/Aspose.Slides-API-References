---
title: BaseSet
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 92
url: /tr/system.collections.generic/baseset/
---
## BaseSet sınıfı




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++'a özgüdür. |
| void [Add](./add/)(const T\&) override | Ögeyi kümeye ekler. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Const nitelikli koleksiyonun ilk elemanına olan yineleyiciyi alır. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Koleksiyonun ilk elemanını (varsa) işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) bir T kopya nesnesi döndürdüğü için başvurulan nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Koleksiyonun ilk const nitelikli elemanına olan yineleyiciyi alır. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Koleksiyonun sonunun arkasındaki mevcut olmayan const nitelikli eleman için yineleyiciyi alır. |
| void [Clear](./clear/)() override | Kümeye ait tüm öğeleri siler. |
| **bool** [Contains](./contains/)(const T\&) const override | Öğenin kümede mevcut olup olmadığını denetler. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Hash içeriğini mevcut dizi öğelerine kopyalar. |
| [set_t](./set_t/)\& [data](./data/)() | Alttaki veri yapısına erişim sağlayıcı. |
| const [set_t](./set_t/)\& [data](./data/)() const | Alttaki veri yapısına erişim sağlayıcı. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Const nitelikli koleksiyonun sonunun arkasındaki mevcut olmayan bir eleman için yineleyiciyi alır. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Koleksiyonun son elemanından (varsa) hemen sonrasını işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../ienumerable/getenumerator/) bir T kopya nesnesi döndürdüğü için başvurulan nesneyi değiştirmek için kullanılamaz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| int [get_Count](./get_count/)() const override | Kümedeki öğe sayısını alır. |
| virtual int [get_Count](./get_count/)() const | [get_Count()](./get_count/)'in gizlenmesini önler. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Koleksiyonun yalnızca okunur olup olmadığını denetler. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesne ile ilişkili referans sayacı veri yapısını alır. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Sayar oluşturur. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
|  [ICollection](../icollection/icollection/)() | Varsayılan kurucu. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopya kurucu. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Taşıma kurucu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir toplayıcı fonksiyon uygular. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizideki herhangi bir öğenin mevcut olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Giriş dizisindeki her öğe üzerinde bir dönüşüm fonksiyonu çağırarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Öğeleri belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bir dizinin belirtilen değeri içerip içermediğini belirler. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Dizi içinde öğe sayısını döndürür (doğrudan sayma yoluyla hesaplanır). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini döndürür; dizi boşsa varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Koşulu sağlayan dizinin ilk öğesini döndürür; böyle bir öğe bulunamazsa varsayılan değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Dizinin öğelerini gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Dizinin öğelerini gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini döndürür; dizi boşsa varsayılan değer döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genellikle bir dizideki her öğe üzerinde bir dönüşüm fonksiyonunu çağırır ve ortaya çıkan maksimum değeri döndürür. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genellikle bir dizideki her öğe üzerinde bir dönüşüm fonksiyonunu çağırır ve ortaya çıkan minimum değeri döndürür. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen tipe göre süzer. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Bir dizideki öğelerin sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Dizinin öğelerini dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizideki her öğeyi, öğenin indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini projekte eder ve ortaya çıkan dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık öğeyi atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık öğe döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Bir diziden bir dizi (array) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Bir diziden List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre süzer. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Taşıma atama operatörü. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Taşıma atama operatörü. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| **bool** [Remove](./remove/)(const T\&) override | Kümeye ait öğeyi kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), System::BaseTypesInfo\<[System::Object](../../system/object/)\>) | RTTI bilgisi. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| **bool** [TryAdd](./tryadd/)(const T\&) | Kümeye öğe ekler. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut konteyner için begin const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut konteyner için begin yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut konteyner için end const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut konteyner için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [ThisType](./thistype/) | Kendi tipi. |
| [ThisPtr](./thisptr/) | Gösterici tipi. |
| [set_t](./set_t/) | Alttaki veri tipi. |
| [iterator](./iterator/) | Yineleyici tipi. |
| [const_iterator](./const_iterator/) | Const yineleyici tipi. |
| [ValueType](./valuetype/) | Değer tipi. |
| [BaseType](./basetype/) | Uygulanan arayüz. |
| [IEnumerablePtr](./ienumerableptr/) | Enumerable arayüz göstericisi. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** göstericisi. |

## İlgili

* Sınıf [Object](../../system/object/)
* Sınıf [ICollection](../icollection/)
* Ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)