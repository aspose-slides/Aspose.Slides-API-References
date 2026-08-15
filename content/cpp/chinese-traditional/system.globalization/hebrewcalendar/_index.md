---
title: HebrewCalendar
second_title: Aspose.Slides for C++ API 參考文件
description: "希伯來日曆。此類別的物件應僅使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 144
url: /zh-hant/system.globalization/hebrewcalendar/
---
## HebrewCalendar 類別

Hebrew calendar. 此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class HebrewCalendar : public System::Globalization::Calendar
```

## 方法

| 方法 | 描述 |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 建立目前物件的副本，並回傳指向它的共享指標。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | 取得演算法類型。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 取得目前時代的索引。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 取得目前時代的值。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | 取得日曆中存在的時代清單。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 檢查日曆是否唯讀。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | 日曆支援的最大時間點。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | 日曆支援的最小時間點。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 取得可用兩位數表示的最後一年。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的引用計數資料結構。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 取得指定時間點的月份天數。 |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | 取得指定時間點的星期幾。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 取得指定時間點的年度天數。 |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 取得特定月份的天數。 |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | 取得特定月份的天數。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 取得特定年份的天數。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 取得特定年份的天數。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 取得指定時間點的時代。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似實作。啟用自訂物件的雜湊。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 取得指定時間點的小時。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 取得指定年份的閏月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI 資訊。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI 資訊。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 取得指定時間點的毫秒。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 取得指定時間點的分鐘。 |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | 取得指定時間點的月份。 |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 取得指定年份的月份數。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | 取得指定年份的月份數。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | 取得指定年份的月份數。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 取得指定時間點的秒數。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。類似 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 取得指定時間點的年度週次。 |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 取得指定時間點的年份。 |
|  [HebrewCalendar](./hebrewcalendar/)() | 建構子。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。類似 C# 的 'is' 運算子。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) override | 檢查該日是否為閏日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 檢查該日是否為閏日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 檢查該日是否為閏日。 |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) override | 檢查該月是否為閏月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 檢查該月是否為閏月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 檢查該月是否為閏月。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) override | 檢查該年是否為閏年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 檢查該年是否為閏年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 檢查該年是否為閏年。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 檢查年份、月份、日期與時代的值。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似實作。啟用克隆自訂類型。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只會初始化新物件並允許子類別的拷貝建構。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何內容，只會初始化新物件並允許子類別的拷貝建構。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 取得日曆的唯讀版本。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享引用計數。 |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | 設定可用兩位數表示的最後一年。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享引用計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | 從元件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | 從元件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | 從元件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | 使用 TwoDigitYearMax 屬性將年份轉換為四位數。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類似實作。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static constexpr [HebrewEra](./hebrewera/) | 目前的希伯來時代。 |

## 參見

* 類別 [Calendar](../calendar/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)