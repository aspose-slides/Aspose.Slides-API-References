---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides için C++ API Referansı
description: Kullanıcı tarafından tanımlanan FontFallBack kurallarının bir koleksiyonunu temsil eder
type: docs
weight: 2198
url: /tr/aspose.slides/ifontfallbackrulescollection/
---
## IFontFallBackRulesCollection sınıfı


Represents a collection of FontFallBack rules, defined by user

```cpp
class IFontFallBackRulesCollection : public Aspose::Slides::IGenericCollection<System::SharedPtr<Aspose::Slides::IFontFallBackRule>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRule](../ifontfallbackrule/)\>) | Koleksiyonun sonuna yeni bir FallBack kuralı ekler. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Koleksiyonun (varsa) ilk elemanını işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T'nin bir kopya nesnesi döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Koleksiyonun const nitelikli örneğinin (varsa) ilk elemanını işaret eden yineleyiciyi alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Koleksiyonun (varsa) ilk const nitelikli elemanını işaret eden yineleyiciyi alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Koleksiyonun (varsa) son const nitelikli elemanının hemen sonrasını işaret eden yineleyiciyi alır. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | Koleksiyondaki tüm elemanları belirtilen diziye kopyalar. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Koleksiyonun (varsa) son elemanının hemen sonrasını işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T'nin bir kopya nesnesi döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Koleksiyonun const nitelikli örneğinin (varsa) son elemanının hemen sonrasını işaret eden yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) deyimiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerektiği halde C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerektiği halde C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **int32_t** [get_Count](../igenericcollection/get_count/)() | Koleksiyondaki davranışların sayısını döndürür. Yalnızca-okunur **int32_t**. |
| virtual **bool** [get_IsSynchronized](../igenericcollection/get_issynchronized/)() | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca-okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](../igenericcollection/get_syncroot/)() | Bir senkronizasyon kökü döndürür. Yalnızca-okunur [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.generic/ienumerable/getenumerator/)() | Enumerator'ı alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRule](../ifontfallbackrule/)\> [idx_get](./idx_get/)(**int32_t**) | Belirtilen indeksteki kuralı alır. Yalnızca-okunur [IFontFallBackRule](../ifontfallbackrule/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici fonksiyon uygular. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizide herhangi bir öğenin var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Girdi dizisinin her öğesine bir dönüşüm fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Elemanları belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bir dizinin belirtilen bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Dizideki öğe sayısını (doğrudan sayma yoluyla) döndürür. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Belirtilen indeksdeki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Belirtilen indeksdeki öğeyi döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini, dizi boşsa varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Koşulu sağlayan dizinin ilk öğesini, koşulu sağlayan öğe bulunamazsa varsayılan bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin elemanlarını gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin elemanlarını gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini, dizi boşsa varsayılan bir değer döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine dönüşüm fonksiyonu uygular ve elde edilen maksimum değeri döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine dönüşüm fonksiyonu uygular ve elde edilen minimum değeri döndürür. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Dizinin elemanlarını belirtilen tipe göre filtreler. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin elemanlarını, keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin elemanlarını, keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Bir dizinin elemanlarının sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin elemanlarını dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her öğesini, öğenin indeksini ekleyerek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini projekte eder ve elde edilen dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda ardışık öğeyi atlayıp geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda ardışık öğeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Bir diziden bir dizi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleştirmesi. |
| virtual void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRule](../ifontfallbackrule/)\>) | Koleksiyondan belirli bir FallBack kuralının ilk oluşumunu kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçiye (paylaşılan yerine) ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Mevcut konteyner için begin const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Mevcut konteyner için begin yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Mevcut konteyner için end const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Mevcut konteyner için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [IGenericCollection](../igenericcollection/)
* İsim Uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)