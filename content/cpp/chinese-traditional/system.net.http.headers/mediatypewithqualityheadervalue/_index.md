---
title: MediaTypeWithQualityHeaderValue
second_title: Aspose.Slides for C++ API 參考
description: "表示在 'Content-Type' 標頭的值中具有額外品質因子的 MIME 類型。此類別的物件只能使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 157
url: /zh-hant/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue 類別

表示在 **'Content-Type'** 標頭的值中具有額外品質因子的 MIME 類型。本類別的物件只能透過 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將本類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](../mediatypeheadervalue/equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [String](../../system/string/) [get_CharSet](../mediatypeheadervalue/get_charset/)() | 取得字元集。 |
| [String](../../system/string/) [get_MediaType](../mediatypeheadervalue/get_mediatype/)() | 取得 media-type 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](../mediatypeheadervalue/get_parameters/)() | 傳回 media-type 標頭的值參數。 |
| [Nullable](../../system/nullable/)\<**double**\> [get_Quality](./get_quality/)() | 取得品質值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](../mediatypeheadervalue/gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊功能。 |
| static **int32_t** [GetMediaTypeLength](../mediatypeheadervalue/getmediatypelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | 將傳入字串從指定索引轉換為 [MediaTypeHeaderValue](../mediatypeheadervalue/) 類別的實例。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 描述的類型實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
|  [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)() | 建構新實例。 |
|  [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)([String](../../system/string/)) | 建構新實例。 |
|  [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | 建構新實例。 |
|  [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/)) | 建構新實例。 |
|  [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/), **double**) | 建構新實例。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 將傳入字串轉換為 [MediaTypeWithQualityHeaderValue](./) 類別的實例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的專門化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的專門化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [set_CharSet](../mediatypeheadervalue/set_charset/)([String](../../system/string/)) | 設定字元集。 |
| void [set_MediaType](../mediatypeheadervalue/set_mediatype/)([String](../../system/string/)) | 設定 media-type 標頭的值。 |
| void [set_Quality](./set_quality/)([Nullable](../../system/nullable/)\<**double**\>) | 設定品質值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共用指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](../mediatypeheadervalue/tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉換為字串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\>\&) | 嘗試將傳入字串轉換為 [MediaTypeWithQualityHeaderValue](./) 類別的實例。 |
| static **bool** [TryParse](../mediatypeheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | 嘗試將傳入字串轉換為 [MediaTypeHeaderValue](../mediatypeheadervalue/) 類別的實例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [MediaTypeHeaderValue](../mediatypeheadervalue/)
* 命名空間 [System::Net::Http::Headers](../)
* 函式庫 [Aspose.Slides](../../)