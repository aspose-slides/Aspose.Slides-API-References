---
title: PersianCalendar
second_title: Aspose.Slides for C++ API 參考
description: "波斯曆。本類別的物件只能使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其傳遞給函式作為參數。"
type: docs
weight: 261
url: /zh-hant/system.globalization/persiancalendar/
---
## PersianCalendar 類別

波斯曆。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將它傳遞給函式作為參數。

```cpp
class PersianCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 建立目前物件的副本並回傳指向它的 shared pointer。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | 取得演算法類型。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 取得目前年代的索引。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 取得目前年代的值。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | 取得曆法中現有的年代清單。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 檢查曆法是否為唯讀。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | 曆法支援的最大時間點。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | 曆法支援的最小時間點。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 取得可由兩位數表示的最後一年。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 取得指定時間點的月份天數。 |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | 取得指定時間點的星期幾。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 取得指定時間點的年度第幾天。 |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 取得特定月份的天數。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | RTTI 資訊。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | RTTI 資訊。 |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | 取得特定年份的天數。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | 取得特定年份的天數。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | 取得特定年份的天數。 |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | 取得指定時間點的年代。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 取得指定時間點的小時。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 取得指定年份的閏月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 取得指定年份的閏月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 取得指定年份的閏月。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 取得指定時間點的毫秒。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 取得指定時間點的分鐘。 |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 取得指定時間點的月份。 |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 取得指定年份的月份數。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | 取得指定年份的月份數。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | 取得指定年份的月份數。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 取得指定時間點的秒數。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 取得指定時間點的年度第幾週。 |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 取得指定時間點的年份。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 檢查該天是否為閏日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 檢查該天是否為閏日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 檢查該天是否為閏日。 |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | 檢查該月份是否為閏月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 檢查該月份是否為閏月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 檢查該月份是否為閏月。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 檢查該年份是否為閏年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 檢查該年份是否為閏年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 檢查該年份是否為閏年。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 檢查年、月、日與年代的值。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
|  [PersianCalendar](./persiancalendar/)() | 建構子。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 取得曆法的唯讀版。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 以指定值減少 shared reference 計數。 |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 設定可由兩位數表示的最後一年。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非 shared）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前 shared reference 計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增 shared reference 計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳 shared reference 計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | 從零件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | 從零件建構 [DateTime](../../system/datetime/) 物件。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | 使用 TwoDigitYearMax 屬性將年份轉換為四位數。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static constexpr [PersianEra](./persianera/) | 目前波斯年代。 |

## 另請參閱

* 類別 [Calendar](../calendar/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)