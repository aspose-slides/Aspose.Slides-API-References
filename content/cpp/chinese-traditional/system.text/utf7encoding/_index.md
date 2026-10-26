---
title: UTF7Encoding
second_title: Aspose.Slides for C++ API 參考
description: "UTF-7 編碼。本類別的物件應僅使用 System::MakeObject() 函式來配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 365
url: /zh-hant/system.text/utf7encoding/
---
## UTF7Encoding 類別


UTF-7 編碼。本類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 克隆編碼物件。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 在兩個編碼之間轉換位元組。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 在兩個編碼之間轉換位元組。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 與物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | 取得 ASCII 編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | 取得標準大端序 Unicode 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | 取得標準大端序 UTF-32 編碼物件。 |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | 取得與郵件代理內容相容的編碼名稱。 |
| virtual int [get_CodePage](../encoding/get_codepage/)() | 取得 [Windows](../../system.windows/) 代碼頁 ID。 |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | 取得解碼器回退。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | 取得預設編碼。 |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | 取得編碼器回退。 |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | 取得人類可讀的編碼名稱。 |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | 取得與郵件代理標頭相容的編碼名稱。 |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | 檢查編碼是否可在瀏覽器中顯示內容。 |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | 檢查編碼是否可在瀏覽器中儲存內容。 |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | 檢查編碼是否可在郵件客戶端中顯示內容。 |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | 檢查編碼是否可在郵件客戶端中儲存內容。 |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | 檢查編碼是否唯讀。 |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | 檢查編碼是否為單位元組。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | 取得 Latin1 編碼。僅供內部使用。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | 取得標準 Unicode 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | 取得標準 UTF-7 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | 取得標準 UTF-8 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | 僅供內部使用，由類別庫使用：未標記且不驗證輸入。 |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | 取得符合 IANA 的編碼名稱。 |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | 取得 [Windows](../../system.windows/) 代碼頁 ID。 |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | 取得編碼字元緩衝所需的字元數。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 取得編碼字元緩衝所需的字元數。 |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | 取得編碼字元緩衝所需的字元數。 |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 取得編碼字元緩衝所需的字元數。 |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | 取得編碼字串所需的字元數。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 取得編碼字元緩衝所需的字元數。 |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | 取得編碼字元緩衝所需的字元數。 |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | 取得將字元緩衝編碼後產生的位元組。 |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | 取得將字元緩衝編碼後產生的位元組。 |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | 取得將字元緩衝編碼後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 取得將字元緩衝編碼後產生的位元組。 |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 取得將字元緩衝編碼後產生的位元組。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 取得將字元緩衝編碼後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | 取得將字元緩衝編碼後產生的位元組。 |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | 取得解碼位元組緩衝所需的字元數。 |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | 取得解碼位元組緩衝所需的字元數。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 取得解碼位元組緩衝所需的字元數。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 取得解碼位元組緩衝所需的字元數。 |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | 取得解碼位元組緩衝所需的字元數。 |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | 取得解碼位元組緩衝後產生的字元。 |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | 取得解碼位元組緩衝後產生的字元。 |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 取得解碼位元組緩衝後產生的字元。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 取得解碼位元組緩衝後產生的字元。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 取得解碼位元組緩衝後產生的字元。 |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | 取得解碼位元組緩衝後產生的字元。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | 取得將請求轉發給此物件的解碼器。 |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | 取得將請求轉發給此物件的編碼器。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | 依名稱取得編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | 依代碼頁取得編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 依代碼頁取得編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 依名稱取得編碼。 |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | 取得已知編碼的清單。 |
| int [GetHashCode](./gethashcode/)() const override | 取得編碼雜湊碼。 |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | 取得編碼指定字元數所需的最大位元組數。 |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | 取得解碼指定位元組數所需的最大字元數。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | 傳回表示編碼的位元組序列（例如 BOM）。 |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | 將位元組緩衝解碼成字串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | 將位元組緩衝解碼成字串。 |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 將位元組緩衝解碼成字串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 將位元組緩衝解碼成字串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 將位元組緩衝解碼成字串。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 將位元組緩衝解碼成字串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 將位元組緩衝解碼成字串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | 將位元組緩衝解碼成字串。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | 將位元組緩衝解碼成字串。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複本建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | 比較編碼參數。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的專門化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的專門化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 設定解碼器回退。 |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | 設定編碼器回退。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共用參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
|  [UTF7Encoding](./utf7encoding/)() | 建構子。 |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | 建構子。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | 預設代碼頁值。 |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | [Windows](../../system.windows/) 用於 UTF-7 代碼頁 ID 的魔術數字。 |

## 另請參閱

* 類別 [Encoding](../encoding/)
* 命名空間 [System::Text](../)
* 函式庫 [Aspose.Slides](../../)