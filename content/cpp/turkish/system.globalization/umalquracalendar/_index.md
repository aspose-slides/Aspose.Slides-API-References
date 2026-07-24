---
title: UmAlQuraCalendar
second_title: "Aspose.Slides for C++ API Referansı"
description: "Um Al Qura takvimi. Henüz uygulanmadı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 391
url: /tr/system.globalization/umalquracalendar/
---
## UmAlQuraCalendar sınıf

Um Al Qura takvimi. Henüz uygulanmadı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt (stack) üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Mevcut nesnenin bir kopyasını oluşturur ve ona bir paylaşımlı işaretçi döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Algoritma tipini alır. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Mevcut dönemin indeksini alır. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Mevcut dönemin değerini alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Takvimde mevcut dönemlerin listesini alır. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Takvimin yalnızca okunur olup olmadığını denetler. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvim tarafından desteklenen en büyük zaman noktası. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvim tarafından desteklenen en küçük zaman noktası. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 basamaklı bir yıl ile temsil edilebilecek son yılı alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için ayın gününü alır. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Belirtilen zaman noktası için haftanın gününü alır. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için yılın gününü alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Belirli ay içinde gün sayısını alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Belirli ay içinde gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Belirli yıl içinde gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Belirli yıl içinde gün sayısını alır. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için dönemi alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için saatleri alır. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yıl için artık ayı alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI bilgisi. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI bilgisi. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için milisaniyeyi alır. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için dakikayı alır. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için ayı alır. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Belirtilen yılda ay sayısını alır. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Belirtilen yılda ay sayısını alır. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için saniyeyi alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Belirtilen zaman noktası için yılın haftasını alır. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktası için yılı alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
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
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını ilklendirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapısını etkinleştirir. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapısını etkinleştirir. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Takvimin yalnızca okunur sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | String durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | 2 basamakla temsil edilebilecek son yılı ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerden oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerden oluşturur. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax özelliğini kullanarak yılı 4 basamaklı yıla dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
|  [UmAlQuraCalendar](./umalquracalendar/)() | Yapıcı. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidini açma işlemini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Field | Description |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | Mevcut UmAlQura dönemi. |

## Ayrıca Bakınız

* Sınıf [Calendar](../calendar/)
* Ad alanı [System::Globalization](../)
* Kütüphane [Aspose.Slides](../../)