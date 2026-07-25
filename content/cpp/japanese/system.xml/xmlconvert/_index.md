---
title: XmlConvert
second_title: Aspose.Slides for C++ API リファレンス
description: XML 名をエンコードおよびデコードし、実行時型と XML スキーマ定義言語（XSD）型との間の変換メソッドを提供します。データ型を変換する際、返される値はロケールに依存しません。
type: docs
weight: 157
url: /ja/system.xml/xmlconvert/
---
## XmlConvert クラス


Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | 名前をデコードします。このメソッドは XmlConvert::EncodeName(String) および XmlConvert::EncodeLocalName(String) メソッドの逆操作を行います。 |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | 名前を有効な XML ローカル名に変換します。 |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | 名前を有効な XML 名に変換します。 |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | XML 仕様に従って名前が有効かどうかを検証します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | 渡された文字が有効なコロン以外の文字タイプかどうかをチェックします。 |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | 引数の文字が有効な public id 文字であれば渡された文字インスタンスを返し、そうでない場合は **nullptr** を返します。 |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | 渡された文字が有効な開始名文字タイプかどうかをチェックします。 |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | 渡された文字が有効な XML 空白文字かどうかをチェックします。 |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | 渡された文字が有効な XML 文字かどうかをチェックします。 |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | 渡されたサロゲートペア文字が有効な XML 文字かどうかをチェックします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | [String](../../system/string/) を [Boolean](../../system/boolean/) に相当する形に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Byte](../../system/byte/) に相当する形に変換します。 |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Char](../../system/char/) に相当する形に変換します。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [DateTime](../../system/datetime/) に相当する形に変換します。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | [String](../../system/string/) を [DateTime](../../system/datetime/) に相当する形に変換します。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | [String](../../system/string/) を [DateTime](../../system/datetime/) に相当する形に変換します。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | 指定された XmlDateTimeSerializationMode を使用して [String](../../system/string/) を [DateTime](../../system/datetime/) に変換します。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | 提供された [String](../../system/string/) を [DateTimeOffset](../../system/datetimeoffset/) に相当する形に変換します。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 提供された [String](../../system/string/) を [DateTimeOffset](../../system/datetimeoffset/) に相当する形に変換します。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 提供された [String](../../system/string/) を [DateTimeOffset](../../system/datetimeoffset/) に相当する形に変換します。 |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Decimal](../../system/decimal/) に相当する形に変換します。 |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | [String](../../system/string/) を [Double](../../system/double/) に相当する形に変換します。 |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Guid](../../system/guid/) に相当する形に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Int16](../../system/int16/) に相当する形に変換します。 |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Int32](../../system/int32/) に相当する形に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [Int64](../../system/int64/) に相当する形に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [SByte](../../system/sbyte/) に相当する形に変換します。 |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | [String](../../system/string/) を [Single](../../system/single/) に相当する形に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | [Boolean](../../system/boolean/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | [Char](../../system/char/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | [SByte](../../system/sbyte/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | [Int16](../../system/int16/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | [Int32](../../system/int32/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | [Int64](../../system/int64/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | [Byte](../../system/byte/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | [UInt16](../../system/uint16/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | [UInt32](../../system/uint32/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | [UInt64](../../system/uint64/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | [Single](../../system/single/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | [Double](../../system/double/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | [TimeSpan](../../system/timespan/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | [DateTime](../../system/datetime/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | 指定された XmlDateTimeSerializationMode を使用して [DateTime](../../system/datetime/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | 提供された [DateTimeOffset](../../system/datetimeoffset/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | 指定された形式で提供された [DateTimeOffset](../../system/datetimeoffset/) を [String](../../system/string/) に変換します。 |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | [Guid](../../system/guid/) を [String](../../system/string/) に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [TimeSpan](../../system/timespan/) に相当する形に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [UInt16](../../system/uint16/) に相当する形に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [UInt32](../../system/uint32/) に相当する形に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | [String](../../system/string/) を [UInt64](../../system/uint64/) に相当する形に変換します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | W3C 拡張マークアップ言語勧告に従って、名前が有効かどうかを検証します。 |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | W3C 拡張マークアップ言語勧告に従って、名前が有効な **NCName** かどうかを検証します。**NCName** はコロンを含められない名前です。 |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes 勧告に従って、文字列が有効な NMTOKEN かどうかを検証します。 |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | 文字列引数のすべての文字が有効な public id 文字であれば、渡された文字列インスタンスを返します。 |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes 勧告に従って、文字列が有効なトークンかどうかを検証します。 |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | 文字列引数のすべての文字が有効な空白文字であれば、渡された文字列インスタンスを返します。 |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | 文字列引数のすべての文字およびサロゲートペア文字が有効な XML 文字であれば渡された文字列を返し、そうでない場合は最初に見つかった無効な文字に関する情報を含む XmlException がスローされます。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタの別名です。 |

## 関連項目

* クラス [Object](../../system/object/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)