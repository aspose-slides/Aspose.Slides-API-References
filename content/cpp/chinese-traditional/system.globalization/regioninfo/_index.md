---
title: RegionInfo
second_title: Aspose.Slides for C++ API 參考
description: "提供有關區域的資訊。本類別的物件只能使用 System::MakeObject() 函式進行配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用此指標將其作為參數傳遞給函式。"
type: docs
weight: 274
url: /zh-hant/system.globalization/regioninfo/
---
## RegionInfo 類別

Provides information on region. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RegionInfo : public virtual System::Object
```
## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [String](../../system/string/) [get_CurrencyEnglishName](./get_currencyenglishname/)() const | 取得貨幣的英文名稱。 |
| virtual [String](../../system/string/) [get_CurrencyNativeName](./get_currencynativename/)() const | 取得貨幣的本地名稱。 |
| virtual [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | 取得貨幣符號。 |
| static [RegionInfoPtr](../regioninfoptr/) [get_CurrentRegion](./get_currentregion/)() | 取得系統中設定的區域。 |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | 取得完整的區域名稱。 |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | 取得區域的英文名稱。 |
| virtual int [get_GeoId](./get_geoid/)() const | 取得區域的唯一辨識碼。 |
| virtual **bool** [get_IsMetric](./get_ismetric/)() const | 檢查區域是否使用公制系統。 |
| virtual [String](../../system/string/) [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | 取得 ISO 貨幣符號。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | 取得區域名稱。 |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | 取得區域的本地名稱。 |
| virtual [String](../../system/string/) [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | 取得 3 個字母的 ISO 區域代碼。 |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | 取得 3 個字母的 [Windows](../../system.windows/) 區域代碼。 |
| virtual [String](../../system/string/) [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | 取得 2 個字母的 ISO 區域代碼。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| int [GetHashCode](./gethashcode/)() const override | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [RegionInfo](./)\& [operator=](./operator_equal/)(const [RegionInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
|  [RegionInfo](./regioninfo/)(const [String](../../system/string/)\&) | RTTI 資訊。 |
|  [RegionInfo](./regioninfo/)(int) | 建構子。 |
|  [RegionInfo](./regioninfo/)(const [RegionInfo](./)\&) |  |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)