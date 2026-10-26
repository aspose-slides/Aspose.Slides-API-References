---
title: DateTimeFormatInfo
second_title: Aspose.Slides for C++ API 參考
description: "日期與時間格式化參數的集合。此類別的物件只能透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 66
url: /zh-hant/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo 類別


Set of date and time formatting parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 克隆格式資訊。 |
|  [DateTimeFormatInfo](./datetimeformatinfo/)() | 預設建構函式，建立不變格式資訊。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 的規定 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 的規定 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | 取得縮寫星期名稱。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | 取得屬格形式的縮寫月份名稱。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | 取得縮寫月份名稱。 |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | 取得 AM 設定字。 |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | 取得與格式化器關聯的行事曆。 |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | 取得與格式化器關聯的行事曆週規則。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 取得目前執行緒的日期與時間格式化器。 |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | 取得日期分隔符號。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | 取得星期名稱。 |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | 取得一週的第一天。 |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | 取得完整的日期與時間模式。 |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 取得不變的日期與時間格式化器。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 檢查格式化器是否唯讀。 |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | 取得長日期模式。 |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | 取得長時間模式。 |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | 取得月份日期模式。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | 取得屬格形式的月份名稱。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | 取得月份名稱。 |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | 若可用，取得原生行事曆名稱。 |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | 取得 PM 設定字。 |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | 取得 RFC1123 模式。 |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | 取得短日期模式。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | 取得可能的最短星期名稱。 |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | 取得短時間模式。 |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | 取得可排序的日期與時間模式。 |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | 取得時間分隔符號。 |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | 取得通用可排序的日期與時間模式。 |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | 取得年份與月份模式。 |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | 取得縮寫星期名稱。 |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | 取得縮寫年代名稱。 |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | 取得縮寫月份名稱。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | 取得可格式化日期與時間值的所有模式。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | 取得使用指定格式字串可格式化日期與時間值的所有模式。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | 取得星期名稱。 |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | 依名稱取得年代。 |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | 取得年代名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 取得特定類型的格式化器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 取得與格式提供者關聯的格式化器。 |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | 取得閏年月份名稱。 |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | 取得屬格月份名稱。 |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | 取得月份名稱。 |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | 取得指定星期的最短名稱。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述之型別的實例。相當於 C# 'is' 運算子。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | 取得只讀版本的格式化器。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定值。 |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定縮寫星期名稱。 |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定屬格形式的縮寫月份名稱。 |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定縮寫月份名稱。 |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | 設定 AM 設定字。 |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | 設定與格式化器關聯的行事曆。 |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | 設定與格式化器關聯的行事曆週規則。 |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | 設定日期分隔符號。 |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定星期名稱。 |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | 設定一週的第一天。 |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | 設定完整的日期與時間模式。 |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | 設定長日期模式。 |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | 設定長時間模式。 |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | 設定月份日期模式。 |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定屬格形式的月份名稱。 |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定月份名稱。 |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | 設定 PM 設定字。 |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | 設定短日期模式。 |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定可能的最短星期名稱。 |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | 設定短時間模式。 |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | 設定時間分隔符號。 |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | 設定年份與月份模式。 |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | 設定指定格式的模式。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個範本參數設為弱指標（而非共用指標）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 語句的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 類別 [IFormatProvider](../../system/iformatprovider/)
* 類別 [ICloneable](../../system/icloneable/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)