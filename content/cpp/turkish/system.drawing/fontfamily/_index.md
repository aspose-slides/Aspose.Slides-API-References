---
title: FontFamily
second_title: Aspose.Slides için C++ API Referansı
description: "Benzer temel tasarıma sahip bir grup tip yüzünü temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya operator new ile oluşturmaktan kaçının; çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 105
url: /tr/system.drawing/fontfamily/
---
## FontFamily sınıfı

Benzer temel tasarıma sahip bir grup tip yüzünü temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığında veya operator new ile oluşturmaktan kaçının, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class FontFamily : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [Clone](./clone/)() | Mevcut [FontFamily](./) nesnesinin bir kopyasını döndürür. |
| void [Dispose](./dispose/)() | Mevcut nesne tarafından edinilen tüm işletim sistemi kaynaklarını serbest bırakır. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Mevcut ve belirtilen nesnelerin aynı olup olmadığını belirler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir, ancak burada iki NaN eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir, ancak burada iki NaN eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [FontFamily](./fontfamily/)(const [String](../../system/string/)\&) | [FontFamily](./) sınıfının belirtilen adla bir yazı tipi ailesini temsil eden yeni bir örneğini oluşturur. |
| [FontFamily](./fontfamily/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::FontCollection](../../system.drawing.text/fontcollection/)\>\&) | Belirtilen FontCollection içinde belirtilen adla yeni bir [FontFamily](./) örneği oluşturur. |
| [FontFamily](./fontfamily/)([Text::GenericFontFamilies](../../system.drawing.text/genericfontfamilies/)) | Belirtilen genel yazı tipi ailesinden yeni bir [FontFamily](./) örneği oluşturur. |
| static [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\>\> [get_Families](./get_families/)() | Mevcut grafik bağlamıyla ilişkili tüm [FontFamily](./) nesnelerini içeren bir dizi döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericMonospace](./get_genericmonospace/)() | Genel Monospace yazı tipi ailesini temsil eden bir [FontFamily](./) nesnesi döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSansSerif](./get_genericsansserif/)() | Genel Sans Serif yazı tipi ailesini temsil eden bir [FontFamily](./) nesnesi döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSerif](./get_genericserif/)() | Genel Serif yazı tipi ailesini temsil eden bir [FontFamily](./) nesnesi döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Mevcut nesne tarafından temsil edilen yazı tipi ailesinin adını döndürür. |
| int [GetCellAscent](./getcellascent/)([FontStyle](../fontstyle/)) | Belirtilen yazı tipi stili için mevcut nesne tarafından temsil edilen yazı tipi ailesinin hücre yükselişini döndürür. |
| int [GetCellDescent](./getcelldescent/)([FontStyle](../fontstyle/)) | Belirtilen yazı tipi stili için mevcut nesne tarafından temsil edilen yazı tipi ailesinin hücre alçalmasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| int [GetEmHeight](./getemheight/)([FontStyle](../fontstyle/)) | Belirtilen stil için em kare yüksekliğini yazı tipi tasarım birimlerinde döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin karmasını (hash) etkinleştirir. |
| int [GetLineSpacing](./getlinespacing/)([FontStyle](../fontstyle/)) | Belirtilen yazı tipi stili için mevcut nesne tarafından temsil edilen yazı tipi ailesinin satır aralığını döndürür. |
| [String](../../system/string/) [GetName](./getname/)(int) const | Mevcut nesne tarafından temsil edilen yazı tipi ailesinin adını döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneğini temsil edip etmediğini kontrol eder. C# 'is' operatörünün benzeri. |
| **bool** [IsStyleAvailable](./isstyleavailable/)([FontStyle](../fontstyle/)) | Belirtilen yazı tipi stilinin mevcut olup olmadığını belirler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin kopyalanmasını etkinleştirir. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [~FontFamily](./~fontfamily/)() | Yıkıcı. |
| virtual [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)