---
title: MediaTypeHeaderValue
second_title: Aspose.Slides for C++ API 參考
description: "代表在 'Content-Type' 標頭值中的 MIME 類型。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。永遠將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 144
url: /zh-hant/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue 類別


表示「Content-Type」標頭值中的 MIME 類型。此類別的物件僅應使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行期錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將它作為參數傳遞給函式。

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 比較物件時使用 C# [Object.Equals](../../system/object/equals/) 語意。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比較物件時使用 C# [Object.Equals](../../system/object/equals/) 語意。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 並不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 並不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [String](../../system/string/) [get_CharSet](./get_charset/)() | 取得字元集。 |
| [String](../../system/string/) [get_MediaType](./get_mediatype/)() | 取得媒體類型標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | 傳回媒體類型標頭的值參數。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| static **int32_t** [GetMediaTypeLength](./getmediatypelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\>\&) | 將傳入的字串從指定索引轉換為 [MediaTypeHeaderValue](./) 類別的實例。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
|  [MediaTypeHeaderValue](./mediatypeheadervalue/)() | 建立新實例。 |
|  [MediaTypeHeaderValue](./mediatypeheadervalue/)([String](../../system/string/)) | 建立新實例。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 將傳入的字串轉換為 [MediaTypeHeaderValue](./) 類別的實例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_CharSet](./set_charset/)([String](../../system/string/)) | 設定字元集。 |
| void [set_MediaType](./set_mediatype/)([String](../../system/string/)) | 設定媒體類型標頭的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\>\&) | 嘗試將傳入的字串轉換為 [MediaTypeHeaderValue](./) 類別的實例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ICloneable](../../system/icloneable/)
* 命名空間 [System::Net::Http::Headers](../)
* 函式庫 [Aspose.Slides](../../)