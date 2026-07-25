---
title: XmlSchema
second_title: Aspose.Slides for C++ の API リファレンス
description: World Wide Web Consortium (W3C) および . によって指定された XML スキーマのインメモリ表現です。
type: docs
weight: 79
url: /ja/system.xml.schema/xmlschema/
---
## XmlSchema クラス

XML [Schema](../) のインメモリ表現で、World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) と [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/) で指定されています。

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | XML [Schema](../)[Object](../../system/object/) Model (SOM) を検証用のスキーマ情報にコンパイルします。プログラムで構築された SOM の構文的および意味的構造をチェックするために使用されます。意味的検証はコンパイル時に実行されます。 |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | XML [Schema](../)[Object](../../system/object/) Model (SOM) を検証用のスキーマ情報にコンパイルします。プログラムで構築された SOM の構文的および意味的構造をチェックするために使用されます。意味的検証はコンパイル時に実行されます。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN はどの値とも等しくありませんが、C# スタイルの比較として 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN はどの値とも等しくありませんが、C# スタイルの比較として 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用専用です。 |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | スキーマのターゲット名前空間で宣言された属性の form を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | スキーマコンパイル後のすべてのグローバル属性グループの値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | スキーマコンパイル後のすべての属性の値を返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | **blockDefault** 属性を返します。この属性はスキーマの targetNamespace にある要素および複合型の **block** 属性のデフォルト値を設定します。 |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | スキーマのターゲット名前空間で宣言された要素の form を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | スキーマコンパイル後のすべての要素の値を返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | **finalDefault** 属性を返します。この属性はターゲット名前空間内の要素および複合型の **final** 属性のデフォルト値を設定します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | スキーマコンパイル後のすべてのグループの値を返します。 |
| [String](../../system/string/) [get_Id](./get_id/)() | 文字列 ID を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | 含まれるスキーマおよびインポートされたスキーマのコレクションを返します。 |
| **bool** [get_IsCompiled](./get_iscompiled/)() | スキーマがコンパイルされているかどうかを示します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | スキーマ内のスキーマ要素のコレクションを返し、**schema** 要素レベルで新しい要素型を追加するために使用されます。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** 要素が参照するファイル内の行番号を返します。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** 要素が参照するファイル内の列位置を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | このスキーマオブジェクトで使用する XmlSerializerNamespaces を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | スキーマコンパイル後のすべての表記の値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | この [XmlSchemaObject](../xmlschemaobject/) の親を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | スキーマコンパイル後のすべてのスキーマ型の値を返します。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | スキーマを読み込んだファイルのソース位置を返します。 |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | スキーマのターゲット名前空間の Uniform Resource Identifier (URI) を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | スキーマのターゲット名前空間に属さない修飾属性を返します。 |
| [String](../../system/string/) [get_Version](./get_version/)() | スキーマのバージョンを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の `is` 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | 指定された [IO::TextReader](../../system.io/textreader/) から XML [Schema](../) を読み取ります。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | 指定されたストリームから XML [Schema](../) を読み取ります。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | 指定された [XmlReader](../../system.xml/xmlreader/) から XML [Schema](../) を読み取ります。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | スキーマのターゲット名前空間で宣言された属性の form を設定します。 |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **blockDefault** 属性を設定します。この属性はスキーマの targetNamespace にある要素および複合型の **block** 属性のデフォルト値を設定します。 |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | スキーマのターゲット名前空間で宣言された要素の form を設定します。 |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **finalDefault** 属性を設定します。この属性はターゲット名前空間内の要素および複合型の **final** 属性のデフォルト値を設定します。 |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | 文字列 ID を設定します。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** 要素が参照するファイル内の行番号を設定します。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** 要素が参照するファイル内の列位置を設定します。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | このスキーマオブジェクトで使用する XmlSerializerNamespaces を設定します。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | この [XmlSchemaObject](../xmlschemaobject/) の親を設定します。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | スキーマを読み込んだファイルのソース位置を設定します。 |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | スキーマのターゲット名前空間の Uniform Resource Identifier (URI) を設定します。 |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | スキーマのターゲット名前空間に属さない修飾属性を設定します。 |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | スキーマのバージョンを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | XML [Schema](../) を指定されたデータストリームに書き込みます。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | 指定された [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) を使用して、XML [Schema](../) を指定された Stream に書き込みます。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | XML [Schema](../) を指定された [IO::TextWriter](../../system.io/textwriter/) に書き込みます。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | XML [Schema](../) を指定された TextWriter に書き込みます。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | XML [Schema](../) を指定された [XmlWriter](../../system.xml/xmlwriter/) に書き込みます。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | XML [Schema](../) を指定された [XmlWriter](../../system.xml/xmlwriter/) に書き込みます。 |
|  [XmlSchema](./xmlschema/)() | [XmlSchema](./) クラスの新しいインスタンスを初期化します。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) クラスの新しいインスタンスを初期化します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | XML スキーマインスタンス名前空間です。このフィールドは定数です。 |
| static [Namespace](./namespace/) | XML スキーマ名前空間です。このフィールドは定数です。 |

## Typedefs

| Typedef | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 備考

このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

## 参照

* クラス [XmlSchemaObject](../xmlschemaobject/)
* 名前空間 [System::Xml::Schema](../)
* ライブラリ [Aspose.Slides](../../)