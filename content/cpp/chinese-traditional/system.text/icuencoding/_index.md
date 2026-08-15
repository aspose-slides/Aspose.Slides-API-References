---
title: ICUEncoding
second_title: "Aspose.Slides for C++ API 參考"
description: "基於 ICU 的編碼實作。僅供內部使用。此類別的物件只能使用 System::MakeObject() 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。必須將此類別包裝成 System::SmartPtr 指標，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 300
url: /zh-hant/system.text/icuencoding/
---
## ICUEncoding 類別


ICU 為基礎的編碼實作。供內部使用。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式來配置。切記不要在堆疊上或使用 operator new 建立此型別的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class ICUEncoding : public System::Text::Encoding
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | 複製編碼物件。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 在兩種編碼之間轉換位元組。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 在兩種編碼之間轉換位元組。 |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 比較編碼。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管依 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管依 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部用途。 |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | 取得 ASCII 編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | 取得標準的大端序 Unicode 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | 取得標準的大端序 UTF-32 編碼物件。 |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | 取得郵件代理程式正文相容的編碼名稱。 |
| virtual int [get_CodePage](../encoding/get_codepage/)() | 取得 [Windows](../../system.windows/) 代碼頁 ID。 |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | 取得解碼器回退。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | 取得預設編碼。 |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | 取得編碼器回退。 |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | 取得人類可讀的編碼名稱。 |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | 取得郵件代理程式標頭相容的編碼名稱。 |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | 檢查編碼是否可在瀏覽器中顯示內容。 |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | 檢查編碼是否可在瀏覽器中儲存內容。 |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | 檢查編碼是否可在郵件客戶端中顯示內容。 |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | 檢查編碼是否可在郵件客戶端中儲存內容。 |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | 檢查編碼是否為唯讀。 |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | 檢查編碼是否為單位元組。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | 取得 Latin1 編碼。供內部使用。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | 取得標準 Unicode 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | 取得標準 UTF-7 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | 取得標準 UTF-8 編碼物件。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | 僅供內部使用，由類別函式庫使用：未標記且不驗證輸入。 |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | 取得與 IANA 相容的編碼名稱。 |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | 取得 [Windows](../../system.windows/) 代碼頁 ID。 |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | 取得編碼字元緩衝區所需的字元數。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI。 |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | RTTI。 |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | 取得編碼字元緩衝區後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 取得編碼字元緩衝區後產生的位元組。 |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 取得編碼字元緩衝區後產生的位元組。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 取得編碼字元緩衝區後產生的位元組。 |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | 取得編碼字元緩衝區後產生的位元組。 |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | 取得解碼位元組緩衝區所需的字元數。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 取得解碼位元組緩衝區所需的字元數。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 取得解碼位元組緩衝區所需的字元數。 |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | 取得解碼位元組緩衝區所需的字元數。 |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | 取得解碼位元組緩衝區後產生的字元。 |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 取得解碼位元組緩衝區後產生的字元。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 取得解碼位元組緩衝區後產生的字元。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 取得解碼位元組緩衝區後產生的字元。 |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | 取得解碼位元組緩衝區後產生的字元。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | 取得將請求轉發至此物件的解碼器。 |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | 取得將請求轉發至此物件的編碼器。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | 依名稱取得編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | 依代碼頁取得編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 依代碼頁取得編碼。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 依名稱取得編碼。 |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | 取得已知編碼的清單。 |
| int [GetHashCode](../encoding/gethashcode/)() const override | 對編碼進行雜湊。 |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | 取得編碼指定字元數所需的最大位元組數。 |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | 取得解碼指定位元組數所需的最大字元數。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | 返回表示編碼的位元組序列（例如 BOM）。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | 將位元組緩衝區解碼為字串。 |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 將位元組緩衝區解碼為字串。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 將位元組緩衝區解碼為字串。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 將位元組緩衝區解碼為字串。 |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 將位元組緩衝區解碼為字串。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 將位元組緩衝區解碼為字串。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | 將位元組緩衝區解碼為字串。 |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | 將位元組緩衝區解碼為字串。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | 建構子。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的型別實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 把守物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | 使用代碼頁比較編碼。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 為字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 為字串情況的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定值。 |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 設定解碼器回退。 |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | 設定編碼器回退。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共用）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共用參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共用參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 把守物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | 預設代碼頁值。 |

## 另請參閱

* 類別 [Encoding](../encoding/)
* 命名空間 [System::Text](../)
* 函式庫 [Aspose.Slides](../../)