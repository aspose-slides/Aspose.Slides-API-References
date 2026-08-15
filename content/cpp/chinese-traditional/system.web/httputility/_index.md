---
title: HttpUtility
second_title: Aspose.Slides for C++ API 參考
description: 用於將 URL 部分編碼與解碼為十六進位轉義片段的服務類別。
type: docs
weight: 40
url: /zh-hant/system.web/httputility/
---
## HttpUtility 類別

Service class that encodes and decodes URL parts to and from hex escape fragments.

```cpp
class HttpUtility : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| static [String](../../system/string/) [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&) | 解碼 Html 片段。 |
| static void [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 解碼 Html 片段。 |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&) | 編碼 Html 片段。 |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 編碼 Html 片段。 |
| static void [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 編碼 Html 片段。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對 string 與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對 strings 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/)) | 從字串解碼 URI 片段。 |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | 從字串解碼 URI 片段。 |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 從位元組陣列解碼 URI 片段。 |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 從位元組陣列解碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 從位元組陣列解碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&) | 從位元組字串解碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 從字串解碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 從位元組陣列解碼 URI 片段。 |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/)) | 編碼 URI 片段。 |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/), const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 編碼 URI 片段。 |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 編碼 URI 片段。 |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 編碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&) | 編碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 編碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 編碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 編碼 URI 片段。 |
| static [String](../../system/string/) [UrlEncodeUnicode](./urlencodeunicode/)(const [String](../../system/string/)\&) | 使用 Unicode 編碼 URI 片段。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const [String](../../system/string/)\&) | 使用 Unicode 編碼 URI 片段。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 命名空間 [System::Web](../)
* 程式庫 [Aspose.Slides](../../)