---
title: XmlSchemaElement
second_title: Aspose.Slides for C++ APIリファレンス
description: World Wide Web Consortium (W3C) が定める XML スキーマの element 要素を表します。このクラスはすべての粒子タイプの基底クラスであり、XML ドキュメント内の要素を記述するために使用されます。
type: docs
weight: 365
url: /ja/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement クラス

Represents the **element** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is the base class for all particle types and is used to describe an element in an XML document.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないからです。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないからです。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** プロパティを返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | **Block** 派生を返します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | **Block** 値のコンパイル後解釈を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | 要素に対する制約のコレクションを返します。 |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | 要素の内容が単純型、または要素の内容が **textOnly** の場合、要素のデフォルト値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | 要素の [XmlSchemaElement::get_SchemaType](./get_schematype/) または [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) 値に基づいて、要素の型を表す [XmlSchemaType](../xmlschematype/) オブジェクトを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | [XmlSchemaElement](./) または [XmlSchemaElement](./) に基づくオブジェクトを返します。このオブジェクトは **ElementType** 値のコンパイル後解釈を保持します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | **Final** 値を返し、これ以上の派生が許可されないことを示します。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | **Final** 値のコンパイル後解釈を返します。 |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | 固定値を返します。 |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | 要素の形態を返します。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 文字列 ID を返します。 |
| **bool** [get_IsAbstract](./get_isabstract/)() | 要素がインスタンス文書で使用できるかどうかを示す情報を返します。 |
| **bool** [get_IsNillable](./get_isnillable/)() | 要素がインスタンスデータで **xsi:nil** を使用できるかどうかを示す情報を返します。明示的な nil 値を要素に割り当てることが可能かを示します。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** 要素が参照するファイル内の行番号を返します。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** 要素が参照するファイルの行位置を返します。 |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | 粒子が出現できる最大回数を返します。 |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | 数値を文字列として返します。粒子が出現できる最大回数です。 |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | 粒子が出現できる最小回数を返します。 |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | 数値を文字列として返します。粒子が出現できる最小回数です。 |
| [String](../../system/string/) [get_Name](./get_name/)() | 要素の名前を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | このスキーマオブジェクトで使用する XmlSerializerNamespaces を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | この [XmlSchemaObject](../xmlschemaobject/) の親を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | 指定された要素の実際の完全修飾名を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | このスキーマ（または指定された名前空間で示される別のスキーマ）で宣言された要素の参照名を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | 要素の型を返します。複合型または単純型のいずれかです。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | このスキーマ、または指定された名前空間で示される別のスキーマで定義された組み込みデータ型の名前を返します。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | スキーマをロードしたファイルのソース位置を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | この要素によって置き換えられる要素の名前を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 現在のスキーマの対象名前空間に属さない修飾属性を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** プロパティを設定します。 |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **Block** 派生を設定します。 |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | 要素の内容が単純型、または **textOnly** の場合、デフォルト値を設定します。 |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **Final** 値を設定し、これ以上派生できないことを示します。 |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | 固定値を設定します。 |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | 要素の形態を設定します。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 文字列 ID を設定します。 |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | 要素がインスタンス文書で使用できるかどうかを示す情報を設定します。 |
| void [set_IsNillable](./set_isnillable/)(**bool**) | **xsi:nil** がインスタンスデータで発生できるかどうかを示す情報を設定します。要素に明示的な nil 値を割り当てられるかどうかを示します。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** 要素が参照するファイルの行番号を設定します。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** 要素が参照するファイルの行位置を設定します。 |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | 粒子が出現できる最大回数を設定します。 |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | 数値を文字列として設定します。粒子が出現できる最大回数です。 |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | 粒子が出現できる最小回数を設定します。 |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | 数値を文字列として設定します。粒子が出現できる最小回数です。 |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | 要素の名前を設定します。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | このスキーマオブジェクトで使用する XmlSerializerNamespaces を設定します。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | この [XmlSchemaObject](../xmlschemaobject/) の親を設定します。 |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | このスキーマ（または指定された名前空間で示される別のスキーマ）で宣言された要素の参照名を設定します。 |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | 要素の型を設定します。複合型または単純型のいずれかです。 |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | このスキーマ、または指定された名前空間で示される別のスキーマで定義された組み込みデータ型の名前を設定します。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | スキーマをロードしたファイルのソース位置を設定します。 |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | この要素によって置き換えられる要素の名前を設定します。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 現在のスキーマの対象名前空間に属さない修飾属性を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させて返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [XmlSchemaElement](./xmlschemaelement/)() | [XmlSchemaElement](./) クラスの新しいインスタンスを初期化します。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) クラスの新しいインスタンスを初期化します。 |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | [XmlSchemaParticle](../xmlschemaparticle/) クラスの新しいインスタンスを初期化します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## typedef

| typedef | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 備考

このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。 

## 参照

* クラス [XmlSchemaParticle](../xmlschemaparticle/)
* 名前空間 [System::Xml::Schema](../)
* ライブラリ [Aspose.Slides](../../)