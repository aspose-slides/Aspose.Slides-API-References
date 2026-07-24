---
title: Regex
second_title: Aspose.Slides için C++ API Referansı
description: "C# benzeri sözdizimini izleyen düzenli ifade. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığıt (stack) üzerinde ya da new operatörüyle asla oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 92
url: /tr/system.text.regularexpressions/regex/
---
## Regex sınıfı

C# benzeri sözdizimini izleyen düzenli ifade. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığına (stack) üzerinde ya da new operatörünü kullanarak asla oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class Regex : public System::Object
```

## Metotlar

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift duyarlı kayan nokta karşılaştırmasını taklit eder. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Dizgiyi desenin bir parçası olarak kullanmak için özel karakterleri kaçış karakteriyle işler. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [TimeSpan](../../system/timespan/) [get_MatchTimeout](./get_matchtimeout/)() | Eşleşme zaman aşımını alır. |
| [RegexOptions](../regexoptions/) [get_Options](./get_options/)() | Regex seçeneklerini alır. |
| **bool** [get_RightToLeft](./get_righttoleft/)() | Eşleşmenin sağdan sola modda yapılıp yapılmadığını denetler. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, int) | Regex'i dizeye karşı eşleştirir. |
| static **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int) | Dizenin desene uyup uymadığını denetler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&) | Regex'i dizeye karşı eşleştirir. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, int, int) | Regex'i dizeye karşı eşleştirir. |
| static [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Dizeyi ve deseni eşleştirir. |
| [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, int) | Verilen dizede regex'in tüm eşleşmelerini tekrar tekrar eşleştirerek alır. |
| static [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Dize ve desen arasındaki tüm eşleşmeleri alır. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını (klonlanmasını) sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hali. |
|  [Regex](./regex/)() | Boş regex oluşturur. |
|  [Regex](./regex/)(const [String](../../system/string/)\&) | Yapıcı. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Yapıcı. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Yapıcı. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Regex'in dizedeki tüm eşleşmelerini yerine koyma dizesiyle değiştirir. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *) | Regex'in dizedeki tüm eşleşmelerini yerine koyma dizesiyle değiştirir. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *, const char_t *) | Regex'in dizedeki tüm eşleşmelerini yerine koyma dizesiyle değiştirir. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const char_t *) | Regex'in dizedeki tüm eşleşmelerini yerine koyma dizesiyle değiştirir. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | Dizedeki tüm eşleşmeleri delege tarafından oluşturulan yerine koyma dizeleriyle değiştirir. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int) | Dizedeki tüm eşleşmeleri delege tarafından oluşturulan yerine koyma dizeleriyle değiştirir. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int, int) | Dizedeki tüm eşleşmeleri delege tarafından oluşturulan yerine koyma dizeleriyle değiştirir. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, [RegexOptions](../regexoptions/)) | Dizedeki tüm eşleşmeleri delege tarafından oluşturulan yerine koyma dizeleriyle değiştirir (statik fonksiyon). |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Regex'in dizedeki tüm eşleşmelerini yerine koyma dizesiyle değiştirir. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) | Dizedeki alt dizeleri değiştirir. Henüz uygulanmadı. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Dizedeki alt dizeleri değiştirir. Henüz uygulanmadı. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Regex eşleşmelerini değiştirir. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | Regex eşleşmelerini değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (shared yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&) | Dizeyi regex eşleşmelerine göre bölüştürür. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int) | Dizeyi regex eşleşmelerine göre bölüştürür. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int, int) | Girdi dizesini, [Regex](./) yapıcısında belirtilen düzenli ifadeyle tanımlanan konumlardaki eşleşmelerle, belirtilen maksimum sayıda bölerek bir alt dizi dizisine ayırır. Düzenli ifade deseninin araması, girdi dizesindeki belirtilen karakter konumundan başlar. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Dizeyi regexp ile bölüştürür. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Dizeyi regexp ile bölüştürür. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Regex'i dizeye dönüştürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| static [String](../../system/string/) [Unescape](./unescape/)(const [String](../../system/string/)\&) | Desenin bir parçası olarak kullanılan dizgedeki özel karakterlerin kaçışlarını kaldırır. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Field | Description |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Zaman aşımı nedeniyle eşleşme kesintisini devre dışı bırakmak için kullanılan özel zaman aşımı değeri. |

## See Also

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Text::RegularExpressions](../)
* Kütüphane [Aspose.Slides](../../)