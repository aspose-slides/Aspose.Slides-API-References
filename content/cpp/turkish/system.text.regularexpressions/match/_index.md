---
title: Match
second_title: Aspose.Slides for C++ API Referansı
description: "Dize üzerindeki tek bir düzenli ifade eşleşmesi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına ya da new operatörüyle asla oluşturmamalısınız, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 66
url: /tr/system.text.regularexpressions/match/
---
## Match sınıf

[Single](../../system/single/) dize üzerindeki düzenli ifade eşleşmesi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türden bir örneği yığına veya new operatörü ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi ile sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class Match : public System::Text::RegularExpressions::Group
```

## Yöntemler

| Method | Description |
| --- | --- |
| void [AddCapture](./addcapture/)(const [CapturePtr](../captureptr/)\&) | Yakalamayı eşleşmeye ekler. |
| void [AddGroup](./addgroup/)(const [GroupPtr](../groupptr/)\&) | Grubu eşleşmeye ekler. |
|  [Capture](../capture/capture/)(const [UStringPtr](../ustringptr/)\&, int, int) | Yapıcı. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stilinde kayan nokta karşılaştırması taklit eder; iki NaN eşit kabul edilir, IEC 60559:1989’a göre NaN hiçbir değere eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stilinde kayan nokta karşılaştırması taklit eder; iki NaN eşit kabul edilir, IEC 60559:1989’a göre NaN hiçbir değere eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [CaptureCollectionPtr](../capturecollectionptr/) [get_Captures](../group/get_captures/)() | Kullanılabilir yakalamaları alır. |
| static [MatchPtr](../matchptr/) [get_Empty](./get_empty/)() | Boş eşleşme erişicisi. |
| [GroupCollectionPtr](../groupcollectionptr/) [get_Groups](./get_groups/)() | Grup listesini alır. |
| int [get_Index](../capture/get_index/)() const | Yakalanan alt dizenin indeksini alır. |
| int [get_Length](../capture/get_length/)() const | Yakalanan alt dizenin uzunluğunu alır. |
| **bool** [get_Success](../group/get_success/)() | Bu grup için yakalamanın başarılı olup olmadığını denetler. |
| [String](../../system/string/) [get_Value](../capture/get_value/)() const | Yakalanan alt dizeni alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin karma değerlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
|  [Group](../group/group/)(const [UStringPtr](../ustringptr/)\&, int, int) | Yapıcı. |
|  [Group](../group/group/)() | Boş grup yapıcı. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
|  [Match](./match/)(const [UStringPtr](../ustringptr/)\&, int, int) | Yapıcı. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
| [MatchPtr](../matchptr/) [NextMatch](./nextmatch/)() | Eşleşmeler üzerinde yineleme. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referans olarak değer tipindeki nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumu, string ve nullptr durumu için. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumu, stringler için. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual [String](../../system/string/) [Result](./result/)(const [String](../../system/string/)\&) | Alt eşleşme referanslarını değerleriyle değiştirerek dizgeyi biçimlendirir. |
| void [SetMappedIndexes](./setmappedindexes/)(const std::vector\<int\>\&) |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını bir zayıf gösterici olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki göstericileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](../capture/tostring/)() const override | Yakalanan alt dizeni alır. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Group](../group/)
* Ad alanı [System::Text::RegularExpressions](../)
* Kütüphane [Aspose.Slides](../../)