---
title: JapaneseLunisolarCalendar
second_title: Aspose.Slides for C++ API 參考文件
description: "日曆為日本陰陽曆。目前未實作。此類別的物件應僅透過 System::MakeObject() 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因會導致執行時錯誤或斷言失敗。應始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 196
url: /zh-hant/system.globalization/japaneselunisolarcalendar/
---
## JapaneseLunisolarCalendar 類別

Japanese lunisolar calendar. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 將天數加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 將小時加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 將毫秒加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 將分鐘加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 將月份加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 將秒數加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 將週數加入時間點。 |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 將年份加入時間點。 |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 資訊。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 建立目前物件的副本並返回一個 shared pointer。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包含 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包含 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI 資訊。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 取得目前紀元的索引。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 取得目前紀元的值。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | 取得行事曆中存在的紀元清單。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 檢查行事曆是否唯讀。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | 行事曆支援的最大時間點。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | 行事曆支援的最小時間點。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 取得可用兩位數表示的最後一年。 |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | 取得天干。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 取得指定時間點的月份天數。 |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | 取得指定時間點的星期幾。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 取得指定時間點的年度天數。 |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | 取得特定月份的天數。 |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | 取得特定月份的天數。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 取得特定年份的天數。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 取得特定年份的天數。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 取得指定時間點的紀元。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 取得指定時間點的小時。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 取得指定年份的閏月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI 資訊。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI 資訊。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 取得指定時間點的毫秒。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 取得指定時間點的分鐘。 |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 取得指定時間點的月份。 |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | 取得指定年份的月份數。 |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | 取得指定年份的月份數。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 取得指定時間點的秒數。 |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 取得六十甲子循環中的年份。 |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | 取得地支。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 取得指定時間點的週次。 |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | 取得指定時間點的年份。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 檢查該日是否為閏日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 檢查該日是否為閏日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 檢查該日是否為閏日。 |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | 檢查該月是否為閏月。 |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | 檢查該月是否為閏月。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 檢查該年是否為閏年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 檢查該年是否為閏年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 檢查該年是否為閏年。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 檢查年份、月份、日期與紀元的值。 |
|  [JapaneseLunisolarCalendar](./japaneselunisolarcalendar/)() | 建構子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 取得行事曆的唯讀版本。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 設定可用兩位數表示的最後一年。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | 從組件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | 從組件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | 使用 TwoDigitYearMax 屬性將年份轉換為四位數。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static constexpr [JapaneseEra](./japaneseera/) | 目前的日本紀元。 |

## 另見

* 類別 [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)