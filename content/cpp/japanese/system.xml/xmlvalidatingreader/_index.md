---
title: XmlValidatingReader
second_title: Aspose.Slides for C++ API リファレンス
description: ドキュメント型定義 (DTD)、XML-Data Reduced (XDR) スキーマ、XML Schema 定義言語 (XSD) バリデーションを提供するリーダーを表します。
type: docs
weight: 547
url: /ja/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader クラス

DTD、XML-Data Reduced (XDR) スキーマ、および XML [Schema](../../system.xml.schema/) 定義言語 (XSD) の検証を提供するリーダーを表します。

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Close](./close/)() override | [XmlReader::get_ReadState](../xmlreader/get_readstate/) を Closed に変更します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 指定された URI で新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 指定された URI と設定を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 指定された URI、設定、および解析用のコンテキスト情報を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 指定されたストリームとデフォルト設定を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 指定されたストリームと設定で新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 指定されたストリーム、ベース URI、設定を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 指定されたストリーム、設定、解析用コンテキスト情報を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 指定されたテキストリーダーを使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 指定されたテキストリーダーと設定を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 指定されたテキストリーダー、設定、ベース URI を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 指定されたテキストリーダー、設定、解析用コンテキスト情報を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 指定された XML リーダーと設定を使用して新しい [XmlReader](../xmlreader/) インスタンスを作成します。 |
| void [Dispose](../xmlreader/dispose/)() override | 現在の [XmlReader](../xmlreader/) クラスのインスタンスが使用しているすべてのリソースを解放します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途限定です。 |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 現在のノードの属性数を返します。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 現在のノードのベース URI を返します。 |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlValidatingReader](./) がバイナリコンテンツ読み取りメソッドを実装しているかどうかを示す値を返します。 |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | [XmlReader](../xmlreader/) が [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) メソッドを実装しているかどうかを示す値を返します。 |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | このリーダーがエンティティを解析および解決できるかどうかを示す値を返します。 |
| **int32_t** [get_Depth](./get_depth/)() override | XML ドキュメント内で現在のノードの深さを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | ドキュメントのエンコーディング属性を返します。 |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | リーダーがエンティティを処理する方法を指定する値を返します。 |
| **bool** [get_EOF](./get_eof/)() override | リーダーがストリームの末尾に位置しているかどうかを示す値を返します。 |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | 現在のノードが属性を持っているかどうかを示す値を返します。 |
| **bool** [get_HasValue](./get_hasvalue/)() override | 現在のノードが [String::Empty](../../system/string/empty/) 以外の [XmlValidatingReader::get_Value](./get_value/) を持つことができるかどうかを示す値を返します。 |
| **bool** [get_IsDefault](./get_isdefault/)() override | 現在のノードが DTD またはスキーマで定義されたデフォルト値から生成された属性であるかどうかを示す値を返します。 |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 現在のノードが空要素かどうかを示す値を返します（例: **<MyElement/>**）。 |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | 現在の行番号を返します。 |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | 現在の行位置を返します。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 現在のノードのローカル名を返します。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 現在のノードの修飾名を返します。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 名前空間サポートを行うかどうかを示す値を返します。 |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | リーダーが位置しているノードの名前空間 Uniform Resource Identifier (URI)（World Wide [Web](../../system.web/) Consortium (W3C) の名前空間仕様で定義）を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | この実装に関連付けられた [XmlNameTable](../xmlnametable/) を返します。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 現在のノードのタイプを返します。 |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 現在のノードに関連付けられた名前空間プレフィックスを返します。 |
| char16_t [get_QuoteChar](./get_quotechar/)() override | 属性ノードの値を囲む引用符文字を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | この [XmlValidatingReader](./) を構築するために使用された [XmlReader](../xmlreader/) を返します。 |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | リーダーの状態を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | スキーマ検証の結果、現在のノードに割り当てられたスキーマ情報を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | 検証に使用する XmlSchemaCollection を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | スキーマタイプオブジェクトを返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | この [XmlReader](../xmlreader/) インスタンスの作成に使用された [XmlReaderSettings](../xmlreadersettings/) オブジェクトを返します。 |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | 実行する検証のタイプを示す値を返します。 |
| [String](../../system/string/) [get_Value](./get_value/)() override | 現在のノードのテキスト値を返します。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 現在のノードのタイプを返します。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 現在の **xml:lang** スコープを返します。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 現在の **xml:space** スコープを返します。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 指定された名前の属性値を返します。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 指定されたローカル名と名前空間 Uniform Resource Identifier (URI) を持つ属性の値を返します。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 指定されたインデックスの属性値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| **bool** [HasLineInfo](./haslineinfo/)() override | クラスが行情報を返すことができるかどうかを示す値を返します。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 派生クラスでオーバーライドされた場合、指定されたインデックスの属性値を取得します。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_Name](../xmlreader/get_name/) 値を持つ属性の値を取得します。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_LocalName](../xmlreader/get_localname/) と [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 値を持つ属性の値を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 文字列引数が有効な XML 名であるかどうかを示す値を返します。 |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 文字列引数が有効な XML 名トークンであるかどうかを示す値を返します。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグかどうかをテストします。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグであり、見つかった要素の [XmlReader::get_Name](../xmlreader/get_name/) 値が指定された引数と一致するかどうかをテストします。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグであり、見つかった要素の [XmlReader::get_LocalName](../xmlreader/get_localname/) と [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) の値が指定された文字列と一致するかどうかをテストします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 現在の要素のスコープで名前空間プレフィックスを解決します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローンを可能にします。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 指定された名前の属性へ移動します。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 指定されたローカル名と名前空間 Uniform Resource Identifier (URI) を持つ属性へ移動します。 |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 指定されたインデックスの属性へ移動します。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 現在のノードがコンテンツノード（空白以外のテキスト、**CDATA**、**Element**、**EndElement**、**EntityReference**、または **EndEntity**）かどうかをチェックします。コンテンツノードでない場合、リーダーは次のコンテンツノードまたはファイルの終端までスキップします。次のタイプのノードはスキップされます: **ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace**、または **SignificantWhitespace**。 |
| **bool** [MoveToElement](./movetoelement/)() override | 現在の属性ノードを含む要素へ移動します。 |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 最初の属性へ移動します。 |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 次の属性へ移動します。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| **bool** [Read](./read/)() override | ストリームから次のノードを読み取ります。 |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 属性値を 1 つ以上の **[Text](../../system.text/)**、**EntityReference**、または **EndEntity** ノードに解析します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 指定された型のオブジェクトとしてコンテンツを読み取ります。 |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | コンテンツを読み取り、Base64 デコードされたバイナリバイトを返します。 |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | コンテンツを読み取り、BinHex デコードされたバイナリバイトを返します。 |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | 現在位置のテキストコンテンツを [Boolean](../../system/boolean/) として読み取ります。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | 現在位置のテキストコンテンツを [DateTime](../../system/datetime/) オブジェクトとして読み取ります。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | 現在位置のテキストコンテンツを [DateTimeOffset](../../system/datetimeoffset/) オブジェクトとして読み取ります。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | 現在位置のテキストコンテンツを [Decimal](../../system/decimal/) オブジェクトとして読み取ります。 |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | 現在位置のテキストコンテンツを倍精度浮動小数点数として読み取ります。 |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | 現在位置のテキストコンテンツを単精度浮動小数点数として読み取ります。 |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | 現在位置のテキストコンテンツを 32 ビット符号付き整数として読み取ります。 |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | 現在位置のテキストコンテンツを 64 ビット符号付き整数として読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | 現在位置のテキストコンテンツを [Object](../../system/object/) として読み取ります。 |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | 現在位置のテキストコンテンツを [String](../../system/string/) オブジェクトとして読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 要求された型として要素コンテンツを読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、要求された型として要素コンテンツを読み取ります。 |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 要素を読み取り、Base64 コンテンツをデコードします。 |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 要素を読み取り、BinHex コンテンツをデコードします。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | 現在の要素を読み取り、内容を [Boolean](../../system/boolean/) オブジェクトとして返します。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を [Boolean](../../system/boolean/) オブジェクトとして返します。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | 現在の要素を読み取り、内容を [DateTime](../../system/datetime/) オブジェクトとして返します。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を [DateTime](../../system/datetime/) オブジェクトとして返します。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | 現在の要素を読み取り、内容を [Decimal](../../system/decimal/) オブジェクトとして返します。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を [Decimal](../../system/decimal/) オブジェクトとして返します。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | 現在の要素を読み取り、内容を倍精度浮動小数点数として返します。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を倍精度浮動小数点数として返します。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | 現在の要素を読み取り、内容を単精度浮動小数点数として返します。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を単精度浮動小数点数として返します。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | 現在の要素を読み取り、内容を 32 ビット符号付き整数として返します。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を 32 ビット符号付き整数として返します。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | 現在の要素を読み取り、内容を 64 ビット符号付き整数として返します。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を 64 ビット符号付き整数として返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | 現在の要素を読み取り、内容を [Object](../../system/object/) として返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を [Object](../../system/object/) として返します。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | 現在の要素を読み取り、内容を [String](../../system/string/) オブジェクトとして返します。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取り、内容を [String](../../system/string/) オブジェクトとして返します。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | テキストのみの要素を読み取ります。ただし、よりシンプルに操作できるため、代わりに [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) メソッドの使用が推奨されます。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | テキストのみの要素を読み取る前に、見つかった要素の [XmlReader::get_Name](../xmlreader/get_name/) 値が指定された文字列と一致することを確認します。ただし、よりシンプルに操作できるため、代わりに [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) メソッドの使用が推奨されます。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | テキストのみの要素を読み取る前に、見つかった要素の [XmlReader::get_LocalName](../xmlreader/get_localname/) と [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) の値が指定された文字列と一致することを確認します。ただし、よりシンプルに操作できるため、代わりに [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) メソッドの使用が推奨されます。 |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | 現在のコンテンツノードがエンドタグであることを確認し、リーダーを次のノードへ進めます。 |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | 派生クラスでオーバーライドされた場合、マークアップを含むすべてのコンテンツを文字列として読み取ります。 |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | 派生クラスでオーバーライドされた場合、このノードとそのすべての子ノードを表すマークアップを含むコンテンツを読み取ります。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | 現在のノードが要素であることを確認し、リーダーを次のノードへ進めます。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | 現在のコンテンツノードが指定された [XmlReader::get_Name](../xmlreader/get_name/) 値を持つ要素であることを確認し、リーダーを次のノードへ進めます。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 現在のコンテンツノードが指定された [XmlReader::get_LocalName](../xmlreader/get_localname/) と [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) の値を持つ要素であることを確認し、リーダーを次のノードへ進めます。 |
| [String](../../system/string/) [ReadString](./readstring/)() override | 要素またはテキストノードの内容を文字列として読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | 現在のノードおよびすべての子孫を読み取るために使用できる新しい [XmlReader](../xmlreader/) インスタンスを返します。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/) を指定された修飾名を持つ次の子孫要素へ進めます。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) を指定されたローカル名と名前空間URIを持つ次の子孫要素へ進めます。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | 指定された修飾名を持つ要素が見つかるまで読み取ります。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIを持つ要素が見つかるまで読み取ります。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/) を指定された修飾名を持つ次の兄弟要素へ進めます。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) を指定されたローカル名と名前空間URIを持つ次の兄弟要素へ進めます。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | 指定された XML [Schema](../../system.xml.schema/) 定義言語（XSD）型の実行時型を返します。 |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | XML ドキュメントに埋め込まれた大きなテキストストリームを読み取ります。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** ノードのエンティティ参照を解決します。 |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | リーダーがエンティティを処理する方法を指定する値を設定します。 |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 名前空間サポートを行うかどうかを示す値を設定します。 |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | 実行する検証の種類を示す値を設定します。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | [XmlResolver](../xmlresolver/) を設定し、外部文書型定義（DTD）およびスキーマロケーション参照の解決に使用します。また、XML [Schema](../../system.xml.schema/) 定義言語（XSD）スキーマで見つかったインポートまたはインクルード要素の処理にも [XmlResolver](../xmlresolver/) が使用されます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [Skip](../xmlreader/skip/)() | 現在のノードの子要素をスキップします。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | 文書型定義（DTD）、XML-Data Reduced（XDR）スキーマ、XML [Schema](../../system.xml.schema/) 定義言語（XSD）スキーマの検証エラー情報を受信するためのイベントハンドラを追加します。 |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | 文書型定義（DTD）、XML-Data Reduced（XDR）スキーマ、XML [Schema](../../system.xml.schema/) 定義言語（XSD）スキーマの検証エラー情報を受信するためのイベントハンドラを削除します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | [XmlValidatingReader](./) クラスの新しいインスタンスを初期化し、与えられた [XmlReader](../xmlreader/) から返されるコンテンツを検証します。 |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | [XmlValidatingReader](./) クラスの新しいインスタンスを、指定された値で初期化します。 |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | [XmlValidatingReader](./) クラスの新しいインスタンスを、指定された値で初期化します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 型定義

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |
## 備考

廃止予定
:   このクラスは廃止されました。検証可能な XML リーダーを作成するには、[XmlReaderSettings](../xmlreadersettings/) クラスと [XmlReader::Create](../xmlreader/create/) メソッドの使用が推奨されます。
このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡して使用してください。

## 参照

* クラス [XmlReader](../xmlreader/)
* クラス [IXmlLineInfo](../ixmllineinfo/)
* クラス [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)