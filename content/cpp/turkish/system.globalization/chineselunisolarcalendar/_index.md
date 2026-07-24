---
title: ChineseLunisolarCalendar
second_title: Aspose.Slides for C++ API Referansı
description: "Çin lunisolar takvimi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneklerini yığıt üzerinde veya new operatörüyle yaratmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr göstergesine sarın ve bu göstergeyi işlevlere argüman olarak geçirin."
type: docs
weight: 27
url: /tr/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar sınıf

Chinese lunisolar calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Zaman noktasına gün ekler. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Zaman noktasına saat ekler. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Zaman noktasına milisaniye ekler. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Zaman noktasına dakika ekler. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Zaman noktasına ay ekler. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Zaman noktasına saniye ekler. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Zaman noktasına hafta ekler. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Zaman noktasına yıl ekler. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI bilgisi. |
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | Varsayılan yapıcı. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Geçerli nesnenin bir kopyasını oluşturur ve ona bir paylaşımlı gösterge döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift duyarlıklı karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI bilgisi. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Geçerli dönemin dizinini alır. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Geçerli dönemin değerini alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Takvimde mevcut dönemlerin listesini alır. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Takvimin yalnızca okunabilir olup olmadığını denetler. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvim tarafından desteklenen en büyük zaman noktası. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvim tarafından desteklenen en küçük zaman noktası. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 basamaklı bir yıl ile temsil edilebilecek son yılı döndürür. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Göksel gövdeyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için ayın gününü alır. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için haftanın gününü alır. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için yılın gününü alır. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Belirli ay için gün sayısını alır. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Belirli ay için gün sayısını alır. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Belirli ay için gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Belirli yıl için gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Belirli yıl için gün sayısını alır. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Belirtilen zaman noktası için dönemi alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özelleştirilmiş nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saatini alır. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yıl için artık ayı alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Belirtilen yıl için artık ayı alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Belirtilen yıl için artık ayı alır. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için milisaniyeyi alır. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için dakikayı alır. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için ayı alır. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Belirtilen yılda ay sayısını alır. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI bilgisi. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI bilgisi. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için saniyeyi alır. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Altmışlık döngüsündeki yılı alır. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Dünyevi dalı alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Belirtilen zaman noktası için yılın haftasını alır. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yılını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipten bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Günün artık olup olmadığını denetler. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Günün artık olup olmadığını denetler. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Günün artık olup olmadığını denetler. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ayın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ayın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ayın artık olup olmadığını denetler. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Yılın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Yılın artık olup olmadığını denetler. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Yıl, ay, gün ve dönem değerlerini denetler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özelleştirilmiş tiplerin kopyalanmasını (klonlanmasını) sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcıyla oluşturulmasını sağlar. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcıyla oluşturulmasını sağlar. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Takvimin yalnızca okunabilir sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2 basamaklı bir yıl ile temsil edilebilecek son yılı ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterge (shared değil) olarak ayarlar. Kapsayıcılardaki gösterge türünü zayıf moda değiştirmeye imkan verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı gösterge ya da ThisProtector kullanılmalı. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı gösterge ya da ThisProtector kullanılmalı. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerden oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerden oluşturur. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax özelliğini kullanarak yılı 4 basamaklı yıla dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı gösterge ya da ThisProtector kullanılmalı. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı gösterge ya da ThisProtector kullanılmalı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | Mevcut Çin dönemi. |

## Bkz

* Sınıf [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* İsim Uzayı [System::Globalization](../)
* Kütüphane [Aspose.Slides](../../)