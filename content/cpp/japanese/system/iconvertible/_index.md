---
title: IConvertible
second_title: Aspose.Slides for C++ API リファレンス
description: "実装された参照型または値型の値を、同等の値を持つ共通言語ランタイム型に変換するメソッドを定義します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生する可能性があります。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 937
url: /ja/system/iconvertible/
---
## IConvertible クラス

実装された参照型または値型の値を、同等の値を持つ共通言語ランタイム型に変換するメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class IConvertible : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../object/gettype/) 呼び出しの類似です。 |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | このインスタンスの型コードを返します。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロック処理を実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|   [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|   [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照で比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の [Boolean](../boolean/) 値に変換します。 |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 8 ビット uint32_teger に変換します。 |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の Unicode 文字に変換します。 |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の [System::DateTime](../datetime/) に変換します。 |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の [System::Decimal](../decimal/) 数値に変換します。 |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の倍精度浮動小数点数に変換します。 |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 16 ビット符号付き整数に変換します。 |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 32 ビット符号付き整数に変換します。 |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 64 ビット符号付き整数に変換します。 |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 8 ビット符号付き整数に変換します。 |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の単精度浮動小数点数に変換します。 |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の [System::String](../string/) に変換します。 |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](../object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定された System::Type の [System::Object](../object/) に変換します（同等の値を持ち、指定されたカルチャ固有の書式情報を使用）。 |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 16 ビット uint32_teger に変換します。 |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 32 ビット uint32_teger に変換します。 |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して同等の 64 ビット uint32_teger に変換します。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 構文を実装します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../object/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)