---
title: XmlSchemaType
second_title: Aspose.Slides for C++ API リファレンス
description: すべての単純型および複合型の基底クラスです。
type: docs
weight: 911
url: /ja/system.xml.schema/xmlschematype/
---
## XmlSchemaType クラス

すべての単純型および複合型の基底クラスです。

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** プロパティを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](./get_baseschematype/)() | コンパイル後のオブジェクト型、または組み込み XML [Schema](../) 定義言語 (XSD) データ型、simpleType 要素、または complexType 要素を返します。これはスキーマコンパイル後のインフォセット値です。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\> [get_BaseXmlSchemaType](./get_basexmlschematype/)() | このスキーマ型の基本型に対するコンパイル後の値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](./get_datatype/)() | 複合型のデータ型に対するコンパイル後の値を返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](./get_derivedby/)() | この要素が基本型からどのように派生したかに関するコンパイル後の情報を返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | さらに派生が許可されているかを示す型派生の最終属性を返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | [XmlSchemaType::get_Final](./get_final/) 値のコンパイル後の解釈を返します。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 文字列 ID を返します。 |
| virtual **bool** [get_IsMixed](./get_ismixed/)() | この型が混在コンテンツモデルを持つかどうかを示す値を返します。この呼び出しは複合型でのみ有効です。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** 要素が参照するファイル内の行番号を返します。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** 要素が参照するファイル内の行位置を返します。 |
| [String](../../system/string/) [get_Name](./get_name/)() | 型の名前を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | このスキーマオブジェクトで使用する XmlSerializerNamespaces を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | この [XmlSchemaObject](../xmlschemaobject/) の親を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | この型の **Name** 属性から構築された型の修飾名を返します。これはスキーマコンパイル後の値です。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | スキーマを読み込んだファイルのソース位置を返します。 |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | 型の XmlTypeCode を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 現在のスキーマのターゲット名前空間に属さない修飾属性を返します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | 指定された複合型の組み込み複合型を表す [XmlSchemaComplexType](../xmlschemacomplextype/) を返します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 修飾名で指定された複合型の組み込み複合型を表す [XmlSchemaComplexType](../xmlschemacomplextype/) を返します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 修飾名で指定された単純型の組み込み単純型を表す [XmlSchemaSimpleType](../xmlschemasimpletype/) を返します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | 指定された単純型の組み込み単純型を表す [XmlSchemaSimpleType](../xmlschemasimpletype/) を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子の類似です。 |
| static **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 指定された派生スキーマ型が指定された基本スキーマ型から派生しているかどうかを示す値を返します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか [LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** プロパティを設定します。 |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | さらに派生が許可されているかを示す型派生の最終属性を設定します。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 文字列 ID を設定します。 |
| virtual void [set_IsMixed](./set_ismixed/)(**bool**) | この型が混在コンテンツモデルを持つかどうかを示す値を設定します。この呼び出しは複合型でのみ有効です。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** 要素が参照するファイル内の行番号を設定します。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** 要素が参照するファイル内の行位置を設定します。 |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | 型の名前を設定します。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | このスキーマオブジェクトで使用する XmlSerializerNamespaces を設定します。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | この [XmlSchemaObject](../xmlschemaobject/) の親を設定します。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | スキーマを読み込んだファイルのソース位置を設定します。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 現在のスキーマのターゲット名前空間に属さない修飾属性を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させて返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか [LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) クラスの新しいインスタンスを初期化します。 |
|  [XmlSchemaType](./xmlschematype/)() | [XmlSchemaType](./) クラスの新しいインスタンスを初期化します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 備考

このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 

## 参照

* クラス [XmlSchemaAnnotated](../xmlschemaannotated/)
* 名前空間 [System::Xml::Schema](../)
* ライブラリ [Aspose.Slides](../../)