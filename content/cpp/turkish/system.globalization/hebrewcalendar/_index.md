---
title: HebrewCalendar
second_title: Aspose.Slides for C++ API Referansı
description: "İbranice takvim. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün bir örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisi içinde tutun ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 144
url: /tr/system.globalization/hebrewcalendar/
---
## HebrewCalendar sınıfı

Hebrew takvimi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün bir örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içinde tutun ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class HebrewCalendar : public System::Globalization::Calendar
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına gün ekler. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına saat ekler. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Bir zaman noktasına milisaniye ekler. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına dakika ekler. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına ay ekler. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına saniye ekler. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına hafta ekler. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Bir zaman noktasına yıl ekler. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI bilgisi. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Mevcut nesnenin bir kopyasını oluşturur ve ona paylaşımlı bir işaretçi döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) mantığıyla karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmasa da iki NaN'ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmasa da iki NaN'ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç kullanım içindir. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Algoritma tipini alır. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Mevcut çağın indeksini alır. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Mevcut çağın değerini alır. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Takvimde mevcut olan çağların listesini alır. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Takvimin yalnızca okunabilir olup olmadığını kontrol eder. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvim tarafından desteklenen en büyük zaman noktasını alır. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvim tarafından desteklenen en küçük zaman noktasını alır. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 basamaklı bir sayı ile temsil edilebilecek son yılı alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ay gününü alır. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Belirtilen zaman noktasının haftanın gününü alır. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yıl gününü alır. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Belirli bir ayın gün sayısını alır. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Belirli bir ayın gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Belirli bir yılın gün sayısını alır. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Belirli bir yılın gün sayısını alır. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Belirtilen zaman noktasının çağını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saatini alır. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yılın artık ayını alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI bilgisi. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI bilgisi. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının milisaniyesini alır. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının dakikasını alır. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Belirtilen zaman noktasının ayını alır. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Belirtilen yıldaki ay sayısını alır. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Belirtilen yıldaki ay sayısını alır. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Belirtilen yıldaki ay sayısını alır. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saniyesini alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğudur. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Belirtilen zaman noktasının yılın haftasını alır. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yılını alır. |
|  [HebrewCalendar](./hebrewcalendar/)() | Yapıcı. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğudur. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Günün artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ayın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ayın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ayın artık olup olmadığını kontrol eder. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Yılın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını kontrol eder. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Yılın artık olup olmadığını kontrol eder. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Çağ, ay, gün ve yıl değerlerini kontrol eder. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme mantığını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğudur. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarının ilklendirilmesini yapar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi ilklendirir ve alt sınıfların kopya yapılandırılmasını mümkün kılar. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi ilklendirir ve alt sınıfların kopya yapılandırılmasını mümkün kılar. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Takvimin yalnızca okunabilir sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | String durumları için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | 2 basamaklı bir sayı ile temsil edilebilecek son yılı ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-inci şablon bağımsız değişkeni zayıf bir işaretçi olarak ayarlar (paylaşımlı yerine). Kolleksiyonlardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Bileşenlerden [DateTime](../../system/datetime/) nesnesi oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Bileşenlerden [DateTime](../../system/datetime/) nesnesi oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Bileşenlerden [DateTime](../../system/datetime/) nesnesi oluşturur. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax özelliğini kullanarak yılı 4 basamaklı yıla dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesinin uygulanması. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi kaldırma mantığını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [HebrewEra](./hebrewera/) | Mevcut Hebrew çağı. |

## İlgili

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)