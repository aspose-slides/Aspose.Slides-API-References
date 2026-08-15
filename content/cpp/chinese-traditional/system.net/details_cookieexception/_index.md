---
title: Details_CookieException
second_title: Aspose.Slides for C++ API 參考文件
description: "表示當 CookieContainer 的大小超過 MaxCookieSize 屬性值時拋出的例外。切勿手動建立此類別的實例。請改用 CookieException 類別。切勿將 CookieException 類別的實例包裝成 System::SmartPtr。"
type: docs
weight: 79
url: /zh-hant/system.net/details_cookieexception/
---
## Details_CookieException 類別


表示當 [CookieContainer](../cookiecontainer/) 的大小超過 MaxCookieSize 屬性值時拋出的例外。切勿手動建立此類別的實例。請改用 CookieException 類別。切勿將 CookieException 類別的實例包裝成 [System::SmartPtr](../../system/smartptr/)。

```cpp
class Details_CookieException : public System::Details_FormatException
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Details_CookieException](./details_cookieexception/)() | 建立新實例。 |
|  [Details_CookieException](./details_cookieexception/)(std::nullptr_t) | 建立新實例。 |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/)) | 建立新實例。 |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/), [Exception](../../system/exception/)) | 建立新實例。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | 傳回包含自訂例外資料的字典。 |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 傳回 32 位元整數值，該值為與目前物件所代表的例外相關聯的 HRESULT 代碼。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | 傳回表示內部例外之物件的參照。 |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | 傳回包含錯誤描述的字串。 |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | 傳回包含堆疊追蹤的字串。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | 傳回代表最內層例外之 Exception 物件的副本。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與該物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_formatexception/gettype/)() const override | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| **bool** [Is](../../system/details_formatexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | 設定 HRESULT，這是一個指派給特定例外的編碼數值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | 傳回目前物件的字串表示形式。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_formatexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual const char * [what](../../system/details_exception/what/)() const | 實作 [what()](../../system/details_exception/what/) 方法，此方法由 [ExceptionWrapper](../../system/exceptionwrapper/) 類別呼叫。儘管此類別未繼承自 std::exception，衍生類別仍可使用受保護/私有成員實作其邏輯。將此方法實作移至 [ExceptionWrapper](../../system/exceptionwrapper/) 可能會破壞該邏輯。 |
| virtual  [~Details_CookieException](./~details_cookieexception/)() | 銷毀目前實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Details_FormatException](../../system/details_formatexception/)
* 命名空間 [System::Net](../)
* 函式庫 [Aspose.Slides](../../)