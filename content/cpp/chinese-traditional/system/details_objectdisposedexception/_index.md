---
title: Details_ObjectDisposedException
second_title: Aspose.Slides for C++ API 參考
description: "ObjectDisposedException 會在對已釋放的物件呼叫方法時拋出。絕不要手動建立此類別的實例。請改用 ObjectDisposedException 類別。切勿將 ObjectDisposedException 類別的實例包裝至 System::SmartPtr。"
type: docs
weight: 612
url: /zh-hant/system/details_objectdisposedexception/
---
## Details_ObjectDisposedException 類別


ObjectDisposedException 會在對已釋放的物件呼叫方法時拋出。絕不要手動建立此類別的實例。請改用 ObjectDisposedException 類別。切勿將 ObjectDisposedException 類別的實例包裝至 [System::SmartPtr](../smartptr/)。

```cpp
class Details_ObjectDisposedException : public System::Details_InvalidOperationException
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | 傳回包含自訂例外資料的字典。 |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 傳回一個 32 位元整數值，其為與目前物件所表示例外相關聯的 HRESULT 代碼。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | 傳回表示內部例外之物件的參照。 |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | 傳回包含錯誤描述的字串。 |
| [String](../string/) [get_ObjectName](./get_objectname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | 傳回包含堆疊追蹤的字串。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | 傳回表示最內層例外之 Exception 物件的副本。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件關聯的參照計數資料結構。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定功能。直接呼叫或使用 [LockContext](../lockcontext/) 哨兵物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法的類似功能。啟用自訂型別的複製。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | 設定 HRESULT，一個指派給特定例外的編碼數值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參照計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並傳回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | 傳回目前物件的字串表示形式。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖功能。直接呼叫或使用 [LockContext](../lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual const char * [what](../details_exception/what/)() const | 實作 [what()](../details_exception/what/) 方法，此方法由 [ExceptionWrapper](../exceptionwrapper/) 類別呼叫。儘管此類別未繼承自 std::exception，衍生類別仍可使用保護/私有成員實作其邏輯。將此方法實作搬移至 [ExceptionWrapper](../exceptionwrapper/) 可能會破壞該邏輯。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 另請參閱

* 類別 [Details_InvalidOperationException](../details_invalidoperationexception/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)