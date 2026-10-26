---
title: XmlReader
second_title: Aspose.Slides for C++ API リファレンス
description: XML データへの高速で非キャッシュ、前方限定のアクセスを提供するリーダーを表します。
type: docs
weight: 430
url: /ja/system.xml/xmlreader/
---
## XmlReader クラス

高速でキャッシュされない、前方のみのアクセスを提供する XML データのリーダーを表します。

```cpp
class XmlReader : public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [Close](./close/)() | 派生クラスでオーバーライドされた場合、[XmlReader::get_ReadState](./get_readstate/)を[ReadState::Closed](../readstate/)に変更します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 指定された URI で新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 指定された URI と設定を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 指定された URI、設定、および解析用のコンテキスト情報を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 指定されたストリームをデフォルト設定で使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 指定されたストリームと設定で新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 指定されたストリーム、ベース URI、設定を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 指定されたストリーム、設定、解析用コンテキスト情報を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 指定されたテキストリーダーを使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 指定されたテキストリーダーと設定を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 指定されたテキストリーダー、設定、ベース URI を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 指定されたテキストリーダー、設定、解析用コンテキスト情報を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 指定された XML リーダーと設定を使用して新しい [XmlReader](./) インスタンスを作成します。 |
| void [Dispose](./dispose/)() override | [XmlReader](./) クラスの現在のインスタンスが使用しているすべてのリソースを解放します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | 派生クラスでオーバーライドされた場合、現在のノードの属性数を取得します。 |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 派生クラスでオーバーライドされた場合、現在のノードのベース URI を取得します。 |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | [XmlReader](./) がバイナリコンテンツ読み取りメソッドを実装しているかどうかを示す値を返します。 |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | [XmlReader](./) が [XmlReader::ReadValueChunk](./readvaluechunk/) メソッドを実装しているかどうかを示す値を返します。 |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | このリーダーがエンティティを解析および解決できるかどうかを示す値を返します。 |
| virtual **int32_t** [get_Depth](./get_depth/)() | 派生クラスでオーバーライドされた場合、XML ドキュメント内で現在のノードの深さを取得します。 |
| virtual **bool** [get_EOF](./get_eof/)() | 派生クラスでオーバーライドされた場合、リーダーがストリームの末尾に位置しているかどうかを示す値を取得します。 |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 現在のノードに属性があるかどうかを示す値を返します。 |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | 派生クラスでオーバーライドされた場合、現在のノードが [XmlReader::get_Value](./get_value/) の値を持てるかどうかを示す値を取得します。 |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | 派生クラスでオーバーライドされた場合、現在のノードが DTD またはスキーマで定義されたデフォルト値から生成された属性かどうかを示す値を取得します。 |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 派生クラスでオーバーライドされた場合、現在のノードが空要素かどうかを示す値を取得します（例: **<MyElement/>**）。 |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 派生クラスでオーバーライドされた場合、現在のノードのローカル名を取得します。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 派生クラスでオーバーライドされた場合、現在のノードの完全修飾名を取得します。 |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 派生クラスでオーバーライドされた場合、リーダーが位置しているノードの名前空間 URI（W3C 名前空間仕様で定義）を取得します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 派生クラスでオーバーライドされた場合、この実装に関連付けられた [XmlNameTable](../xmlnametable/) を取得します。 |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | 派生クラスでオーバーライドされた場合、現在のノードのタイプを取得します。 |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 派生クラスでオーバーライドされた場合、現在のノードに関連付けられた名前空間プレフィックスを取得します。 |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | 派生クラスでオーバーライドされた場合、属性ノードの値を囲む引用符文字を取得します。 |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | 派生クラスでオーバーライドされた場合、リーダーの状態を取得します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | スキーマ検証の結果、現在のノードに割り当てられたスキーマ情報を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | この [XmlReader](./) インスタンスを作成するために使用された [XmlReaderSettings](../xmlreadersettings/) オブジェクトを返します。 |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | 派生クラスでオーバーライドされた場合、現在のノードのテキスト値を取得します。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | 現在のノードの型を返します。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 派生クラスでオーバーライドされた場合、現在の **xml:lang** スコープを取得します。 |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 派生クラスでオーバーライドされた場合、現在の **xml:space** スコープを取得します。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_Name](./get_name/) 値を持つ属性の値を取得します。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 派生クラスでオーバーラドされた場合、指定された [XmlReader::get_LocalName](./get_localname/) と [XmlReader::get_NamespaceURI](./get_namespaceuri/) の値を持つ属性の値を取得します。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | 派生クラスでオーバーライドされた場合、指定されたインデックスの属性の値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | 派生クラスでオーバーライドされた場合、指定されたインデックスの属性の値を取得します。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_Name](./get_name/) の値を持つ属性の値を取得します。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_LocalName](./get_localname/) と [XmlReader::get_NamespaceURI](./get_namespaceuri/) の値を持つ属性の値を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。 |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | 文字列引数が有効な XML 名かどうかを示す値を返します。 |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | 文字列引数が有効な XML 名トークンかどうかを示す値を返します。 |
| virtual **bool** [IsStartElement](./isstartelement/)() | [XmlReader::MoveToContent](./movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグかどうかをテストします。 |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](./movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグであり、見つかった要素の [XmlReader::get_Name](./get_name/) 値が指定された引数と一致するかどうかをテストします。 |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](./movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグであり、見つかった要素の [XmlReader::get_LocalName](./get_localname/) と [XmlReader::get_NamespaceURI](./get_namespaceuri/) の値が指定された文字列と一致するかどうかをテストします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、現在の要素のスコープ内で名前空間プレフィックスを解決します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_Name](./get_name/) の値を持つ属性に移動します。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された [XmlReader::get_LocalName](./get_localname/) と [XmlReader::get_NamespaceURI](./get_namespaceuri/) の値を持つ属性に移動します。 |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | 派生クラスでオーバーライドされた場合、指定されたインデックスの属性に移動します。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | 現在のノードがコンテンツ（空白以外のテキスト、**CDATA**、**Element**、**EndElement**、**EntityReference**、または **EndEntity**）ノードかどうかをチェックします。コンテンツノードでない場合、リーダーは次のコンテンツノードまたはファイル末尾までスキップします。次のタイプのノードをスキップします：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace**、または **SignificantWhitespace**。 |
| virtual **bool** [MoveToElement](./movetoelement/)() | 派生クラスでオーバーライドされた場合、現在の属性ノードを含む要素に移動します。 |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 派生クラスでオーバーライドされた場合、最初の属性に移動します。 |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 派生クラスでオーバーライドされた場合、次の属性に移動します。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| virtual **bool** [Read](./read/)() | 派生クラスでオーバーライドされた場合、ストリームから次のノードを読み取ります。 |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | 派生クラスでオーバーライドされた場合、属性値を1つまたは複数の **[Text](../../system.text/)**、**EntityReference**、または **EndEntity** ノードに解析します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 指定された型のオブジェクトとしてコンテンツを読み取ります。 |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | コンテンツを読み取り、Base64 デコードされたバイナリバイトを返します。 |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | コンテンツを読み取り、**BinHex** デコードされたバイナリバイトを返します。 |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | 現在位置のテキストコンテンツを [Boolean](../../system/boolean/) として読み取ります。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | 現在位置のテキストコンテンツを[DateTime](../../system/datetime/)オブジェクトとして読み取ります。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | 現在位置のテキストコンテンツを[DateTimeOffset](../../system/datetimeoffset/)オブジェクトとして読み取ります。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | 現在位置のテキストコンテンツを[Decimal](../../system/decimal/)オブジェクトとして読み取ります。 |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | 現在位置のテキストコンテンツを**double**精度の浮動小数点数として読み取ります。 |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | 現在位置のテキストコンテンツを**float**単精度浮動小数点数として読み取ります。 |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | 現在位置のテキストコンテンツを**int32_t**（32ビット符号付き整数）として読み取ります。 |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | 現在位置のテキストコンテンツを**int64_t**（64ビット符号付き整数）として読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | 現在位置のテキストコンテンツを[Object](../../system/object/)として読み取ります。 |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | 現在位置のテキストコンテンツを[String](../../system/string/)オブジェクトとして読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 要素のコンテンツを要求された型として読み取ります。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、要求された型として要素のコンテンツを読み取ります。 |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 要素を読み取り、**Base64** コンテンツをデコードします。 |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 要素を読み取り、**BinHex** コンテンツをデコードします。 |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | 現在の要素を読み取り、内容を[Boolean](../../system/boolean/)オブジェクトとして返します。 |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を[Boolean](../../system/boolean/)オブジェクトとして返します。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | 現在の要素を読み取り、内容を[DateTime](../../system/datetime/)オブジェクトとして返します。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を[DateTime](../../system/datetime/)オブジェクトとして返します。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | 現在の要素を読み取り、内容を[Decimal](../../system/decimal/)オブジェクトとして返します。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を[Decimal](../../system/decimal/)オブジェクトとして返します。 |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | 現在の要素を読み取り、内容を**double**精度の浮動小数点数として返します。 |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を**double**精度の浮動小数点数として返します。 |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | 現在の要素を読み取り、内容を**float**単精度浮動小数点数として返します。 |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を**float**単精度浮動小数点数として返します。 |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | 現在の要素を読み取り、内容を32ビット符号付き整数として返します。 |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を32ビット符号付き整数として返します。 |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | 現在の要素を読み取り、内容を64ビット符号付き整数として返します。 |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を64ビット符号付き整数として返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | 現在の要素を読み取り、内容を[Object](../../system/object/)として返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を[Object](../../system/object/)として返します。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | 現在の要素を読み取り、内容を[String](../../system/string/)オブジェクトとして返します。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIが現在の要素と一致することを確認し、現在の要素を読み取って内容を[String](../../system/string/)オブジェクトとして返します。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | テキストのみの要素を読み取ります。ただし、[XmlReader::ReadElementContentAsString](./readelementcontentasstring/) メソッドを使用することが推奨されます。こちらの方が操作を簡潔に処理できます。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | 指定された文字列と一致する[XmlReader::get_Name](./get_name/)値を持つ要素が見つかったことを確認してからテキストのみの要素を読み取ります。ただし、[XmlReader::ReadElementContentAsString](./readelementcontentasstring/) メソッドを使用することが推奨されます。こちらの方が操作を簡潔に処理できます。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 指定された文字列と一致する[XmlReader::get_LocalName](./get_localname/)および[XmlReader::get_NamespaceURI](./get_namespaceuri/)値を持つ要素が見つかったことを確認してからテキストのみの要素を読み取ります。ただし、[XmlReader::ReadElementContentAsString](./readelementcontentasstring/) メソッドを使用することが推奨されます。こちらの方が操作を簡潔に処理できます。 |
| virtual void [ReadEndElement](./readendelement/)() | 現在のコンテンツノードが終了タグであることを確認し、リーダーを次のノードに進めます。 |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | 派生クラスでオーバーライドされた場合、マークアップを含むすべてのコンテンツを文字列として読み取ります。 |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | 派生クラスでオーバーライドされた場合、このノードとすべての子ノードを表すマークアップを含むコンテンツを読み取ります。 |
| virtual void [ReadStartElement](./readstartelement/)() | 現在のノードが要素であることを確認し、リーダーを次のノードに進めます。 |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | 現在のコンテンツノードが指定された[XmlReader::get_Name](./get_name/)値を持つ要素であることを確認し、リーダーを次のノードに進めます。 |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 現在のコンテンツノードが指定された[XmlReader::get_LocalName](./get_localname/)および[XmlReader::get_NamespaceURI](./get_namespaceuri/)値を持つ要素であることを確認し、リーダーを次のノードに進めます。 |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | 派生クラスでオーバーライドされた場合、要素またはテキストノードの内容を文字列として読み取ります。ただし、[XmlReader::ReadElementContentAsString](./readelementcontentasstring/) メソッドを使用することが推奨されます。こちらの方が操作を簡潔に処理できます。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | 現在のノードおよびすべての子孫ノードを読み取るために使用できる新しい[XmlReader](./)インスタンスを返します。 |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | [XmlReader](./) を指定された修飾名を持つ次の子孫要素へ進めます。 |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](./) を指定されたローカル名と名前空間URIを持つ次の子孫要素へ進めます。 |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | 指定された修飾名を持つ要素が見つかるまで読み取ります。 |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIを持つ要素が見つかるまで読み取ります。 |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | [XmlReader](./) を指定された修飾名を持つ次の兄弟要素へ進めます。 |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](./) を指定されたローカル名と名前空間URIを持つ次の兄弟要素へ進めます。 |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | XML ドキュメントに埋め込まれた大きなテキストストリームを読み取ります。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| virtual void [ResolveEntity](./resolveentity/)() | 派生クラスでオーバーライドされた場合、**EntityReference** ノードのエンティティ参照を解決します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [Skip](./skip/)() | 現在のノードの子要素をスキップします。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 型定義

| 型定義 | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |
## 参照

* クラス [IDisposable](../../system/idisposable/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)