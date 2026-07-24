---
title: CultureInfo
second_title: Aspose.Slides for C++ API Referansı
description: "Kültüre özgü değerler ve algoritmaların koleksiyonu. Ayarlayıcı işlemler yalnızca okunamayan olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 53
url: /tr/system.globalization/cultureinfo/
---
## CultureInfo sınıfı

Kültüre özgü değerler ve algoritmaların koleksiyonu. Ayarlayıcı işlemler yalnızca yalnızca okunamayan olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçmek için kullanın.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Önbelleğe alınmış kültür bilgilerini yeniler. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Kültür bilgilerini kopyalar. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | İsimle kültür oluşturur. |
| explicit  [CultureInfo](./cultureinfo/)(int) | RTTI bilgisi. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Yapılandırıcı. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Yapılandırıcı. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Yapılandırıcı. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Her zaman ArgumentNullException fırlatır. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Nesneleri karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamıyla karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Kültür tarafından kullanılan takvimi alır. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Kültür kurallarına uyumlu dize karşılaştırıcıyı alır. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Mevcut kültürü tanımlayan kültür tiplerinin bit düzeyinde birleşimini alır. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Mevcut iş parçacığı için ayarlanmış kültürü alır. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Mevcut iş parçacığının UI kültürünü alır. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Tarih biçim bilgilerini alır. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Mevcut uygulama alanındaki varsayılan kültürü alır. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Mevcut uygulama alanındaki varsayılan UI kültürünü alır. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Kültürün görüntüleme adını alır. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Kültürün İngilizce adını alır. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Bir dil için RFC 4646 adını alır. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | İşletim sistemiyle kurulu kültürü alır. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Değişmez kültürü alır. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Kültürün nötr olup olmadığını denetler. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Kültür nesnesinin sadece okunur olup olmadığını denetler. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Etkin giriş yerel kimliğini alır. |
| virtual int [get_LCID](./get_lcid/)() const | Kültür kimliğini alır. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Kültür adını alır. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Kültürün yerel adını alır. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Sayı biçim bilgilerini alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Kültürle kullanılabilecek takvimlerin listesi. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Üst kültürü alır. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Kültür tarafından kullanılan metin parametrelerini alır. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Üç harfli ISO 639-2 dil kodunu alır. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | [Windows](../../system.windows/) API'sinde tanımlanan dilin üç harfli kodunu alır. |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Kültürle ilişkili iki harfli ISO dil adını alır. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | [CultureInfo](./)'nin kullanıcı seçili kültür ayarlarını kullanıp kullanmadığını gösteren bir bayrak alır. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Konsol uygulamaları için uygun alternatif kültürü alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | İsmiyle kültürü alır. CreateSpecificCulture ile aynı. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | İsmiyle kültürü alır. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Kimliğiyle kültürü alır. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Kullanımdan kaldırılmış. Belirtilen RFC 4646 dil etiketiyle sadece okunur [CultureInfo](./) nesnesi alır. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Belirtilen türlere ait kültürleri alır. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Belirli bir tip için biçim nesnesini alır. |
| int [GetHashCode](./gethashcode/)() const override | Nesne karma kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| **bool** [IsInherited](./isinherited/)() const | Kalıtım bayrağını alır. SADECE DAHİLİ KULLANIM İÇİN. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Kültür parametrelerini karşılaştırır. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Kültürün sadece okunur bir versiyonunu alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans üzerinden karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Mevcut iş parçacığı için kültürü ayarlar. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Mevcut iş parçacığının UI kültürünü ayarlar. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Tarih biçim bilgilerini ayarlar. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Mevcut uygulama alanında varsayılan kültürü ayarlar. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Mevcut uygulama alanında varsayılan UI kültürünü ayarlar. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Sayı biçim bilgilerini alır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Konteynerlerde işaretçileri zayıf moda geçirmeyi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalı; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalı; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Kültürü dizeye dönüştürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırılabilir veya [LockContext](../../system/lockcontext/) gözcü nesnesi kullanılabilir. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalı; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalı; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Sınıf [IFormatProvider](../../system/iformatprovider/)
* Sınıf [ICloneable](../../system/icloneable/)
* Ad alanı [System::Globalization](../)
* Kütüphane [Aspose.Slides](../../)