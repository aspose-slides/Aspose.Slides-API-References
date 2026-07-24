---
title: CommentCollection
second_title: Aspose.Slides for C++ API Referansı
description: Bir yazarın yorumlarının koleksiyonunu temsil eder.
type: docs
weight: 456
url: /tr/aspose.slides/commentcollection/
---
## CommentCollection sınıfı

Bir yazarın yorumlarının koleksiyonunu temsil eder.

```cpp
class CommentCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::CommentAuthor>>,
                          public Aspose::Slides::ICommentCollection
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [AddComment](./addcomment/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::Drawing::PointF](../../system.drawing/pointf/), [System::DateTime](../../system/datetime/)) override | Koleksiyonun sonuna yeni bir yorum ekler. |
| [System::SharedPtr](../../system/sharedptr/)\<[IModernComment](../imoderncomment/)\> [AddModernComment](./addmoderncomment/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, [System::Drawing::PointF](../../system.drawing/pointf/), [System::DateTime](../../system/datetime/)) override | Koleksiyonun sonuna yeni modern bir yorum ekler. |
| [iterator](./iterator/) [begin](./begin/)() | Koleksiyonda (varsa) ilk öğeye işaret eden yineleyiciyi alır. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Koleksiyonun const nitelikli örneğinde (varsa) ilk öğeye işaret eden yineleyiciyi alır. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Koleksiyonda (varsa) const nitelikli ilk öğeye işaret eden yineleyiciyi alır. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Koleksiyondaki son const nitelikli öğenin hemen sonrasına işaret eden yineleyiciyi alır. |
| void [Clear](./clear/)() override | Koleksiyondan tüm yorumları kaldırır. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\>, **int32_t**) override | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [iterator](./iterator/) [end](./end/)() | Koleksiyondaki son öğenin hemen sonrasına işaret eden yineleyiciyi alır. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Koleksiyonun const nitelikli örneğinde (varsa) son öğenin hemen sonrasına işaret eden yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipinde nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipinde nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [FindCommentByIdx](./findcommentbyidx/)(**int32_t**) | Koleksiyonda yorumları indeksine göre bulur. |
| **int32_t** [get_Count](./get_count/)() override | Koleksiyonda gerçekte bulunan öğe sayısını alır. Yalnızca-okunur **int32_t**. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca-okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | Bir senkronizasyon kökü döndürür. Yalnızca-okunur [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\>\> [GetEnumerator](./getenumerator/)() override | Koleksiyonu yineleyen bir enumerator döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogı. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogı. |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [idx_get](./idx_get/)(**int32_t**) override | Belirtilen indeksdeki öğeyi alır. Yalnızca-okunur [Comment](../comment/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [InsertComment](./insertcomment/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::Drawing::PointF](../../system.drawing/pointf/), [System::DateTime](../../system/datetime/)) override | Belirtilen indekste koleksiyona yeni bir yorum ekler. |
| [System::SharedPtr](../../system/sharedptr/)\<[IModernComment](../imoderncomment/)\> [InsertModernComment](./insertmoderncomment/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, [System::Drawing::PointF](../../system.drawing/pointf/), [System::DateTime](../../system/datetime/)) override | Belirtilen indekste koleksiyona yeni modern bir yorum ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTür (targetType) tarafından tanımlanan tipin bir örneğini temsil edip etmediğini kontrol eder. C# 'is' operatörünün analogu. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici fonksiyon uygular. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizinin tüm öğelerinin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizide herhangi bir öğenin var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Giriş dizisinin her öğesine bir dönüştürme fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Öğeleri belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bir dizinin belirtilen bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Dizi içinde (doğrudan sayma yoluyla hesaplanır) öğe sayısını döndürür. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan bir dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini, dizi boşsa varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Bir koşulu sağlayan dizinin ilk öğesini, böyle bir öğe bulunamazsa varsayılan bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin öğelerini gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin öğelerini gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini, dizi boşsa varsayılan bir değer döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine bir dönüştürme fonksiyonu uygular ve elde edilen maksimum değeri döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizinin her öğesine bir dönüştürme fonksiyonu uygular ve elde edilen minimum değeri döndürür. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen tipe göre filtreler. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Bir dizinin öğelerinin sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin öğelerini dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her öğesini, öğenin indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini projeler ve ortaya çıkan dizileri tek bir diziye birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda ardışık öğeyi atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda ardışık öğeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Bir diziden bir dizi (array) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogı. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | Koleksiyonda belirtilen yorumun ilk gerçekleşimini kaldırır. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'inci şablon argümanını zayıf bir işaretçi olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının güncel değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [ToArray](./toarray/)() override | Tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogı. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Koleksiyonun const nitelikli örneğinde (varsa) ilk öğeye işaret eden yineleyiciyi alır. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Koleksiyonda (varsa) ilk öğeye işaret eden yineleyiciyi alır. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Koleksiyonun const nitelikli örneğinde (varsa) son öğenin hemen sonrasına işaret eden yineleyiciyi alır. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | Koleksiyondaki son öğenin hemen sonrasına işaret eden yineleyiciyi alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Description |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | Mevcut koleksiyonda yineleyici tipleri olarak kullanılan bir koleksiyon türü. |
| [iterator](./iterator/) | Yineleyici tipi. |
| [const_iterator](./const_iterator/) | Const yineleyici tipi. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Sanal (virtual) öğe tipi. |
| [virtualized_iterator](./virtualized_iterator/) | Sanal tip. |

## Ayrıca

* Sınıf [DomObject](../domobject/)
* Sınıf [ICommentCollection](../icommentcollection/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)