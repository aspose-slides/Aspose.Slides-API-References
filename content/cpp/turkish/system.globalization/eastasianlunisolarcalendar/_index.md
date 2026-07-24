---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides for C++ API Referansı
description: "Doğu Asya lunisolar takvimi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığında ya da operator new ile oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya assertion hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 105
url: /tr/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar sınıfı

Doğu Asya lunisolar takvimi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığında ya da operator new ile oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya assertion hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Günleri zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Saatleri zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Milisaniyeleri zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Dakikaları zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Ayları zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Saniyeleri zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Haftaları zaman noktasına ekler. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Yılları zaman noktasına ekler. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI bilgisi. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Mevcut nesnenin bir kopyasını oluşturur ve ona bir shared pointer döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit olmasa da iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit olmasa da iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | RTTI bilgisi. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Mevcut çağın indeksini alır. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Mevcut çağın değerini alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Takvimde mevcut çağların listesini alır. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Takvim tanımlayıcısını alır. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Takvimin sadece okunabilir olup olmadığını denetler. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | Takvim tarafından desteklenen en büyük zaman noktasını alır. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | Takvim tarafından desteklenen en küçük zaman noktasını alır. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 basamaklı bir sayı ile temsil edilebilecek son yılı alır. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Göksel gövdeyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ay gününü alır. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının haftanın gününü alır. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yıl gününü alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Belirli ayın gün sayısını alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Belirli ayın gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Belirli yılın gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Belirli yılın gün sayısını alır. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının çağını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash’lenmesini sağlar. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saatlerini alır. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Belirtilen yılın artık ayını alır. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Belirtilen yılın artık ayını alır. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının milisaniyelerini alır. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının dakikalarını alır. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ayını alır. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Belirtilen yılın ay sayısını alır. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Belirtilen yılın ay sayısını alır. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saniyelerini alır. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 60’lık döngüdeki yılı alır. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Yerel dalı alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Belirtilen zaman noktasının haftasını alır. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yılını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını denetler. C# ‘is’ operatörünün benzeri. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Günün artık olup olmadığını denetler. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Günün artık olup olmadığını denetler. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Ayın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Ayın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Yılın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Yılın artık olup olmadığını denetler. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Yıl, ay, gün ve çağ değerlerini denetler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) savunma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Takvimin sadece okunabilir sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)’nin dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)’nin dize durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2 basamaklı bir sayı ile temsil edilebilecek son yılı ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n’inci şablon bağımsız değişkeni zayıf işaretçi (shared yerine) olarak ayarlar. İşaretçilerin konteynerlerde zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerinden oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerinden oluşturur. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Yılı TwoDigitYearMax özelliğini kullanarak 4 basamaklı yıla dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string’e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) savunma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |
## Ayrıca Bakınız

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)