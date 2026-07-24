---
title: Calendar
second_title: Aspose.Slides C++ API Referansı
description: "Calendar, tarihlerin nasıl işlendiğini, hesaplandığını, biçimlendirildiğini vb. tanımlayan bir sınıftır. Ayarlayıcı işlemler yalnızca okuma-yazma olmayan nesnelerde etkindir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin bir örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1
url: /tr/system.globalization/calendar/
---
## Calendar sınıfı


[Calendar](./) tarihlerinin nasıl işlendiğini, hesaplandığını, biçimlendirildiğini vb. tanımlayan bir yapıdır. Ayarlayıcı işlemler yalnızca okuma-yazma olmayan nesnelerde etkindir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Calendar : public System::ICloneable
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Zaman noktasına gün ekler. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Zaman noktasına saat ekler. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Zaman noktasına milisaniye ekler. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Zaman noktasına dakika ekler. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Zaman noktasına ay ekler. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Zaman noktasına saniye ekler. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Zaman noktasına hafta ekler. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Zaman noktasına yıl ekler. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | RTTI bilgisi. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Geçerli nesnenin bir kopyasını oluşturur ve ona bir paylaşımlı işaretçi döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Algoritma tipini alır. |
| int [get_CurrentEra](./get_currentera/)() const | Geçerli dönemin indeksini alır. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Geçerli dönemin değerini alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Takvimde mevcut olan dönemlerin listesini alır. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Takvim tanımlayıcısını alır. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Takvimin yalnızca okunabilir olup olmadığını denetler. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Takvim tarafından desteklenen azami zaman noktasını döndürür. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Takvim tarafından desteklenen asgari zaman noktasını döndürür. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | 2 basamaklı bir yıl ile temsil edilebilecek son yılı alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ay gününü alır. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının haftanın gününü alır. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yıl gününü alır. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Belirli bir ayda gün sayısını alır. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Belirli bir ayda gün sayısını alır. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Belirli bir yılda gün sayısını alır. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Belirli bir yılda gün sayısını alır. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının dönemini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saatini alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Belirtilen yıl için artık ayı alır. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Belirtilen yıl için artık ayı alır. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının milisaniyesini alır. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının dakikasını alır. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının ayını alır. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Belirtilen yılda ay sayısını alır. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Belirtilen yılda ay sayısını alır. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının saniyesini alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Belirtilen zaman noktasının yıl içindeki haftasını alır. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Belirtilen zaman noktasının yılını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Günü artık olup olmadığını denetler. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Günü artık olup olmadığını denetler. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ayın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ayın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını denetler. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Yılın artık olup olmadığını denetler. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Yıl, ay, gün ve dönem değerlerini denetler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapısını ilklendirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, yalnızca yeni nesneyi ilklendirir ve alt sınıfların kopya oluşturmasını sağlar. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, yalnızca yeni nesneyi ilklendirir ve alt sınıfların kopya oluşturmasını sağlar. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Takvimin yalnızca okunabilir sürümünü alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özel bir uygulaması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özel bir uygulaması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | 2 basamaklı bir yıl ile temsil edilebilecek son yılı ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını weak pointer (shared yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri weak moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerden oluşturur. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) nesnesini bileşenlerden oluşturur. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | TwoDigitYearMax özelliğini kullanarak yılı 4 basamaklı yıla dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapısını serbest bırakır. |

## İlgili

* Sınıf [ICloneable](../../system/icloneable/)
* AdAlanı [System::Globalization](../)
* Kütüphane [Aspose.Slides](../../)