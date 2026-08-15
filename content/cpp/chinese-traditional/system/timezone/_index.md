---
title: TimeZone
second_title: Aspose.Slides for C++ API 參考
description: "表示一個時區。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 1327
url: /zh-hant/system/timezone/
---
## TimeZone 類別

表示一個時區。此類別的物件應僅使用 [System::MakeObject()](../makeobject/) 函式來配置。永遠不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class TimeZone : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 比較 C# 風格的參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 比較 C# 風格的值類型物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | 傳回代表目前時區的 [TimeZone](./) 類別的新執行個體。 |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | 傳回目前物件所代表之時區的夏令時間名稱。 |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | 傳回目前物件所代表之時區的標準時間名稱。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | 傳回特定年份的夏令時間期間。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | 傳回指定本地時間的 UTC 偏移量。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否代表由 targetType 所描述的類型實例。相當於 C# 'is' 運算子。 |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | 判斷由指定的 [DateTime](../datetime/) 物件所表示的日期時間值是否落在目前 [TimeZone](./) 物件所代表時區的夏令時間範圍內。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 相當於 C# [Object.ToString()](../object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 建構。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [Object](../object/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)