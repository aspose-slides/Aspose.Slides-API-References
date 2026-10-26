---
title: NumberFormatInfo
second_title: Aspose.Slides için C++ API Referansı
description: "Sayıların nasıl biçimlendirileceği hakkında bilgi tutar. Ayarlama işlemleri yalnızca yalnızca-okunur olmayan nesnelerde etkindir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına veya new operatörüyle oluşturmaktan kaçının; aksi takdirde çalışma zamanı hataları ve/veya tutma hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 248
url: /tr/system.globalization/numberformatinfo/
---
## NumberFormatInfo sınıfı

Sayıların nasıl biçimlendirileceği hakkında bilgi tutar. Ayarlama işlemleri yalnızca yalnızca-okunur olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına veya new operatörüyle oluşturmaktan kaçının; aksi takdirde çalışma zamanı hataları ve/veya tutma hataları ortaya çıkar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Metotlar

| Method | Açıklama |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Biçim bilgisini kopyalar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Para birimi ondalık basamak sayısını alır. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Para birimi ondalık ayırıcıyı alır. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Para birimi grup ayırıcıyı alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Grup başına para birimi ondalık basamak sayısını alır. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Para birimi negatif desenini alır. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Para birimi pozitif desenini alır. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Para birimi sembolünü alır. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Mevcut iş parçacığının kültür tanımlı sayı biçim bilgilerini alır. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Bir rakamın şeklini nasıl göstereceğini belirten bir değeri alır. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Değişmez kültür tanımlı sayı biçim bilgisini alır. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Biçimin yalnızca okunur olup olmadığını denetler. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Not-a-Number (NaN) sembolünü alır. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Rakam sembollerini (0'dan 9'a) alır. |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Negatif sonsuzluk sembolünü alır. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Negatif işareti alır. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Ondalık basamak sayısını alır. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Ondalık ayırıcıyı alır. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Sayı grup ayırıcıyı alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Grup başına rakam sayısını alır. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Sayı negatif desenini alır. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Yüzde değerlerinde ondalık basamak sayısını alır. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Yüzde değerlerinde ondalık ayırıcıyı alır. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Yüzde değerlerinde grup ayırıcıyı alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Yüzde değeri grubunda rakam sayısını alır. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Yüzde negatif desenini alır. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Yüzde pozitif desenini alır. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Yüzde sembolünü alır. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Permil sembolünü alır. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Pozitif sonsuzluk sembolünü alır. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Pozitif işareti alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Belirli tipte biçimlendiriciyi alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Biçim sağlayıcıyla ilişkili biçimlendiriciyi alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [NumberFormatInfo](./numberformatinfo/)() | Varsayılan yapıcı (değişmez [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarının başlangıç değerlerini ayarlar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Biçimlendiricinin yalnızca okunur sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Para birimi ondalık basamak sayısını ayarlar. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Para birimi ondalık ayırıcıyı ayarlar. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Para birimi grup ayırıcıyı ayarlar. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Grup başına para birimi ondalık basamak sayısını ayarlar. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Para birimi negatif desenini ayarlar. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Para birimi pozitif desenini ayarlar. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Para birimi sembolünü ayarlar. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Bir rakamın şeklini nasıl göstereceğini belirten bir değeri ayarlar. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Not-a-Number (NaN) sembolünü ayarlar. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Rakam sembollerini (0'dan 9'a) ayarlar. |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Negatif sonsuzluk sembolünü ayarlar. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Negatif işareti ayarlar. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Ondalık basamak sayısını ayarlar. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Ondalık ayırıcıyı ayarlar. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Sayı grup ayırıcıyı ayarlar. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Grup başına rakam sayısını ayarlar. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Sayı negatif desenini ayarlar. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Yüzde değerlerinde ondalık basamak sayısını ayarlar. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Yüzde değerlerinde ondalık ayırıcıyı ayarlar. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Yüzde değerlerinde grup ayırıcıyı ayarlar. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Yüzde değeri grubunda rakam sayısını ayarlar. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Yüzde negatif desenini ayarlar. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Yüzde pozitif desenini ayarlar. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Yüzde sembolünü ayarlar. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Permil sembolünü ayarlar. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Pozitif sonsuzluk sembolünü ayarlar. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Pozitif işareti ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstergeleri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Object](../../system/object/)
* Sınıf [IFormatProvider](../../system/iformatprovider/)
* Sınıf [ICloneable](../../system/icloneable/)
* Ad alanı [System::Globalization](../)
* Kütüphane [Aspose.Slides](../../)