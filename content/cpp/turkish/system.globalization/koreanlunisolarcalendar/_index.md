---
title: KoreanLunisolarCalendar
second_title: Aspose.Slides for C++ API Referansı
description: "Kore lunisolar takvimi. Henüz uygulanmadı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılararak allocate edilmelidir. Bu tipin örneğini yığında (stack) veya operator new ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 235
url: /tr/system.globalization/koreanlunisolarcalendar/
---
## KoreanLunisolarCalendar sınıfı


Kore lunisolar takvimi. Henüz uygulanmadı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Yığını (stack) üzerinde ya da operator new kullanarak bu tipin örneğini asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class KoreanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Yöntemler

| Method | Description |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Mevcut nesnenin bir kopyasını oluşturur ve ona bir shared pointer döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’in hiçbir değere eşit olmamasına rağmen iki NaN’in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’in hiçbir değere eşit olmamasına rağmen iki NaN’in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI bilgisi. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Mevcut dönemin indeksini alır. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Mevcut dönemin değerini alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Takvimde mevcut olan dönemlerin listesini alır. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Takvimin yalnızca okunabilir olup olmadığını kontrol eder. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvimin desteklediği en büyük zaman noktasını alır. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvimin desteklediği en küçük zaman noktasını alır. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 basamaklı bir sayı ile temsil edilebilecek son yılı alır. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Göksel gövdeyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ay gününü alır. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının haftanın gününü alır. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yıl gününü alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Belirli bir ayın gün sayısını alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Belirli bir ayın gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Belirli bir yılın gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Belirli bir yılın gün sayısını alır. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının dönemini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash’lenmesini sağlar. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saatini alır. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yılın artık ayını alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI bilgisi. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI bilgisi. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının milisaniyesini alır. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının dakikasını alır. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ayını alır. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Belirtilen yıldaki ay sayısını alır. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Belirtilen yıldaki ay sayısını alır. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saniyesini alır. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Sexagenary döngüsündeki yılı alır. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Dünya dalga koşulunu alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Belirtilen zaman noktasının yıl içindeki haftasını alır. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yılını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef türüyle aynı olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) override | Günün artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Ayın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Ayın artık olup olmadığını kontrol eder. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) override | Yılın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Yılın artık olup olmadığını kontrol eder. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Yıl, ay, gün ve dönem değerlerini kontrol eder. |
|  [KoreanLunisolarCalendar](./koreanlunisolarcalendar/)() | Yapıcı. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Takvimin yalnızca okunabilir sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) için string ve nullptr durumunun özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) için string durumunun özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2 basamaklı bir sayı ile temsil edilebilecek son yılı ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (shared yerine). Kapsayıcılardaki işaretçileri zayıf moda geçirir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector’ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector’ı kullanın. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Bileşenlerden [DateTime](../../system/datetime/) nesnesi oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Bileşenlerden [DateTime](../../system/datetime/) nesnesi oluşturur. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Yılı TwoDigitYearMax özelliğini kullanarak 4 basamaklı yıla dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesneleri dizeye dönüştürmeyi sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector’ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector’ı çalıştırın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Alanlar

| Field | Description |
| --- | --- |
| static constexpr [GregorianEra](./gregorianera/) | Mevcut gregorian dönemi. |
## Ayrıca Bakınız

* Class [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)