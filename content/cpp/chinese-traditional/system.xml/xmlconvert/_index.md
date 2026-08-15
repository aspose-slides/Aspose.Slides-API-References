---
title: XmlConvert
second_title: Aspose.Slides for C++ API 參考文件
description: 編碼和解碼 XML 名稱，並提供在執行階段類型與 XML 架構定義語言 (XSD) 類型之間轉換的方法。轉換資料類型時，返回的值不受語系影響。
type: docs
weight: 157
url: /zh-hant/system.xml/xmlconvert/
---
## XmlConvert 類別

對 XML 名稱進行編碼和解碼，並提供在執行階段類型與 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 類型之間轉換的方法。轉換資料類型時，返回的值不受語系影響。

```cpp
class XmlConvert : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | 解碼名稱。此方法執行 XmlConvert::EncodeName(String) 與 XmlConvert::EncodeLocalName(String) 方法的相反操作。 |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | 將名稱轉換為有效的 XML 本地名稱。 |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | 將名稱轉換為有效的 XML 名稱。 |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | 驗證名稱符合 XML 規範的有效性。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | 檢查傳入的字元是否為有效的非冒號字元類型。 |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | 如果參數中的字元是有效的公共 ID 字元，則返回傳入的字元實例，否則返回 **nullptr**。 |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | 檢查傳入的字元是否為有效的開始名稱字元類型。 |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | 檢查傳入的字元是否為有效的 XML 空白字元。 |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | 檢查傳入的字元是否為有效的 XML 字元。 |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | 檢查傳入的代理配對字元是否為有效的 XML 字元。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | 將 [String](../../system/string/) 轉換為等同的 [Boolean](../../system/boolean/)。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Byte](../../system/byte/)。 |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Char](../../system/char/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [DateTime](../../system/datetime/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [DateTime](../../system/datetime/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 將 [String](../../system/string/) 轉換為等同的 [DateTime](../../system/datetime/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | 使用指定的 XmlDateTimeSerializationMode，將 [String](../../system/string/) 轉換為 [DateTime](../../system/datetime/)。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | 將提供的 [String](../../system/string/) 轉換為等同的 [DateTimeOffset](../../system/datetimeoffset/)。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將提供的 [String](../../system/string/) 轉換為等同的 [DateTimeOffset](../../system/datetimeoffset/)。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 將提供的 [String](../../system/string/) 轉換為等同的 [DateTimeOffset](../../system/datetimeoffset/)。 |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Decimal](../../system/decimal/)。 |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | 將 [String](../../system/string/) 轉換為等同的 [Double](../../system/double/)。 |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Guid](../../system/guid/)。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Int16](../../system/int16/)。 |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Int32](../../system/int32/)。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [Int64](../../system/int64/)。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [SByte](../../system/sbyte/)。 |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | 將 [String](../../system/string/) 轉換為等同的 [Single](../../system/single/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | 將 [Boolean](../../system/boolean/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | 將 [Char](../../system/char/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | 將 [Decimal](../../system/decimal/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | 將 [SByte](../../system/sbyte/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | 將 [Int16](../../system/int16/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | 將 [Int32](../../system/int32/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | 將 [Int64](../../system/int64/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | 將 [Byte](../../system/byte/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | 將 [UInt16](../../system/uint16/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | 將 [UInt32](../../system/uint32/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | 將 [UInt64](../../system/uint64/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | 將 [Single](../../system/single/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | 將 [Double](../../system/double/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | 將 [TimeSpan](../../system/timespan/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | 將 [DateTime](../../system/datetime/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | 將 [DateTime](../../system/datetime/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | 使用指定的 XmlDateTimeSerializationMode，將 [DateTime](../../system/datetime/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | 將提供的 [DateTimeOffset](../../system/datetimeoffset/) 轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | 將提供的 [DateTimeOffset](../../system/datetimeoffset/) 依指定格式轉換為 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | 將 [Guid](../../system/guid/) 轉換為 [String](../../system/string/)。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [TimeSpan](../../system/timespan/)。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [UInt16](../../system/uint16/)。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [UInt32](../../system/uint32/)。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | 將 [String](../../system/string/) 轉換為等同的 [UInt64](../../system/uint64/)。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | 驗證名稱是否符合 W3C 擴充標記語言（XML）建議的有效名稱。 |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | 驗證名稱是否符合 W3C 擴充標記語言建議的有效 **NCName**。**NCName** 為不能包含冒號的名稱。 |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | 驗證字串是否符合 W3C XML [Schema](../../system.xml.schema/) 第 2 部分：資料型別建議的有效 NMTOKEN。 |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | 如果字串參數中的所有字元都是有效的公共 ID 字元，則返回傳入的字串實例。 |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | 驗證字串是否符合 W3C XML [Schema](../../system.xml.schema/) 第 2 部分：資料型別建議的有效 token。 |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | 如果字串參數中的所有字元都是有效的空白字元，則返回傳入的字串實例。 |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | 如果字串參數中的所有字元及代理配對字元皆為有效的 XML 字元，則返回傳入的字串；否則拋出 XmlException，並提供第一個無效字元的資訊。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 另見

* 類別 [Object](../../system/object/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)