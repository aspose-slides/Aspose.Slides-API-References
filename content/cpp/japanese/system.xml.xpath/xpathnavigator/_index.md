---
title: XPathNavigator
second_title: Aspose.Slides for C++ APIリファレンス
description: XML データのナビゲートおよび編集のためのカーソルモデルを提供します。
type: docs
weight: 66
url: /ja/system.xml.xpath/xpathnavigator/
---
## XPathNavigator クラス

XML データのナビゲートと編集のためのカーサーモデルを提供します。

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | 現在のノードの子ノードリストの末尾に1つ以上の新しい子ノードを作成するために使用される[XmlWriter](../../system.xml/xmlwriter/)オブジェクトを返します。 |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | 指定されたXMLデータ文字列を使用して、現在のノードの子ノードリストの末尾に新しい子ノードを作成します。 |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 指定された[XmlReader](../../system.xml/xmlreader/)オブジェクトのXML内容を使用して、現在のノードの子ノードリストの末尾に新しい子ノードを作成します。 |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 指定された[XPathNavigator](./)のノードを使用して、現在のノードの子ノードリストの末尾に新しい子ノードを作成します。 |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 指定された名前空間プレフィックス、ローカル名、および名前空間URIとその値を使用して、現在のノードの子ノードリストの末尾に新しい子要素ノードを作成します。 |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | [XPathNavigator](./)内のXMLデータが提供されたXML[Schema](../../system.xml.schema/)定義言語（XSD）スキーマに適合しているか検証します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | 派生クラスでオーバーライドされた場合、この[XPathNavigator](./)と同じノードに位置する新しい[XPathNavigator](./)を作成します。 |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 現在の[XPathNavigator](./)の位置と指定された[XPathNavigator](./)の位置を比較します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | [XPath](../)式を表す文字列をコンパイルし、[XPathExpression](../xpathexpression/)オブジェクトを返します。 |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 指定された名前空間プレフィックス、ローカル名、名前空間URIとその値を使用して、現在の要素ノードに属性ノードを作成します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | 現在の要素に新しい属性を作成するために使用される[XmlWriter](../../system.xml/xmlwriter/)オブジェクトを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | [XPathNavigator](./)のコピーを返します。 |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 現在のノードから指定されたノードまでの兄弟ノードの範囲を削除します。 |
| virtual void [DeleteSelf](./deleteself/)() | 現在のノードとその子ノードを削除します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C#[Object.Equals](../../system/object/equals/)のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C#スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C#スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989によればNaNは任意の値（NaNを含む）と等しくないにもかかわらず、C#スタイルの浮動小数点比較をエミュレートし、2つのNaNを等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989によればNaNは任意の値（NaNを含む）と等しくないにもかかわらず、C#スタイルの浮動小数点比較をエミュレートし、2つのNaNを等しいとみなします。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | 指定された[XPath](../)式を評価し、型付き結果を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 指定された[XPath](../)式を評価し、[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)オブジェクトを使用して[XPath](../)式内の名前空間プレフィックスを解決し、型付き結果を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | [XPathExpression](../xpathexpression/)を評価し、型付き結果を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | 提供されたコンテキストを使用して[XPathExpression](../xpathexpression/)を評価し、型付き結果を返します。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 派生クラスでオーバーライドされた場合、現在のノードのベースURIを取得します。 |
| virtual **bool** [get_CanEdit](./get_canedit/)() | [XPathNavigator](./)が基礎となるXMLデータを編集できるかどうかを示す値を返します。 |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 現在のノードが属性を持つかどうかを示す値を返します。 |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | 現在のノードが子ノードを持つかどうかを示す値を返します。 |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | 現在のノードの子ノードを表すマークアップを返します。 |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 派生クラスでオーバーライドされた場合、現在のノードが終了タグのない空要素かどうかを示す値を取得します。 |
| **bool** [get_IsNode](./get_isnode/)() override | 現在のノードが[XPath](../)ノードを表すかどうかを示す値を返します。 |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 派生クラスでオーバーライドされた場合、名前空間プレフィックスなしで現在のノードの[XPathNavigator::get_Name](./get_name/)を取得します。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 派生クラスでオーバーライドされた場合、現在のノードの修飾名を取得します。 |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 派生クラスでオーバーライドされた場合、現在のノードの名前空間URIを取得します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | 派生クラスでオーバーライドされた場合、[XPathNavigator](./)の[XmlNameTable](../../system.xml/xmlnametable/)を取得します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | [XPathNavigator](./)オブジェクトの等価比較に使用される[Collections::IEqualityComparer](../../system.collections/iequalitycomparer/)を返します。 |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | 派生クラスでオーバーライドされた場合、現在のノードのXPathNodeTypeを取得します。 |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | 現在のノードとその子ノードの開始タグと終了タグを表すマークアップを返します。 |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 派生クラスでオーバーライドされた場合、現在のノードに関連付けられた名前空間プレフィックスを取得します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | スキーマ検証の結果として現在のノードに割り当てられたスキーマ情報を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | 現在のノードを最適な型のボックス化オブジェクトとして返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | [XPathNavigator](./)実装で使用され、ストア上の「仮想化」XMLビューを提供し、基礎となるオブジェクトへのアクセスを提供します。 |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | 派生クラスでオーバーライドされた場合、アイテムの**string**値を取得します。 |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | 現在のノードの値を[Boolean](../../system/boolean/)として返します。 |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | 現在のノードの値を[DateTime](../../system/datetime/)として返します。 |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | 現在のノードの値を[Double](../../system/double/)として返します。 |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | 現在のノードの値を[Int32](../../system/int32/)として返します。 |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | 現在のノードの値を[Int64](../../system/int64/)として返します。 |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | 現在のノードの型を返します。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 現在のノードの**xml:lang**スコープを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | 現在のノードのXmlSchemaType情報を返します。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIを持つ属性の値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C#[Object.GetHashCode()](../../system/object/gethashcode/)メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | 指定されたローカル名に対応する名前空間ノードの値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | 現在のノードのスコープ内名前空間を返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C#[System.Object.GetType()](../../system/object/gettype/)呼び出しの類似です。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | 現在選択されているノードの後に新しい兄弟ノードを作成するために使用される[XmlWriter](../../system.xml/xmlwriter/)オブジェクトを返します。 |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | 指定されたXML文字列を使用して、現在選択されているノードの後に新しい兄弟ノードを作成します。 |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 指定された[XmlReader](../../system.xml/xmlreader/)オブジェクトのXML内容を使用して、現在選択されているノードの後に新しい兄弟ノードを作成します。 |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 指定された[XPathNavigator](./)オブジェクトのノードを使用して、現在選択されているノードの後に新しい兄弟ノードを作成します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | 現在選択されているノードの前に新しい兄弟ノードを作成するために使用される[XmlWriter](../../system.xml/xmlwriter/)オブジェクトを返します。 |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | 指定されたXML文字列を使用して、現在選択されているノードの前に新しい兄弟ノードを作成します。 |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 指定された[XmlReader](../../system.xml/xmlreader/)オブジェクトのXML内容を使用して、現在選択されているノードの前に新しい兄弟ノードを作成します。 |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 指定された[XPathNavigator](./)のノードを使用して、現在選択されているノードの前に新しい兄弟ノードを作成します。 |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 指定された名前空間プレフィックス、ローカル名、名前空間URIとその値を使用して、現在のノードの後に新しい兄弟要素を作成します。 |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 指定された名前空間プレフィックス、ローカル名、名前空間URIとその値を使用して、現在のノードの前に新しい兄弟要素を作成します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトがtargetTypeで記述された型のインスタンスであるかをチェックします。C#の'is'演算子の類似です。 |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 指定された[XPathNavigator](./)が現在の[XPathNavigator](./)の子孫かどうかを判定します。 |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 派生クラスでオーバーライドされた場合、現在の[XPathNavigator](./)が指定された[XPathNavigator](./)と同じ位置にあるかどうかを判定します。 |
| void [Lock](../../system/object/lock/)() | C#のlock()ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/)センティリーオブジェクトを使用します。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 指定されたプレフィックスの名前空間URIを返します。 |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | 指定された名前空間URIに対して宣言されたプレフィックスを返します。 |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 現在のノードが指定された[XPathExpression](../xpathexpression/)に一致するかどうかを判定します。 |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | 現在のノードが指定された[XPath](../)式に一致するかどうかを判定します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C#[Object.MemberwiseClone()](../../system/object/memberwiseclone/)メソッドの類似です。カスタム型のクローンを可能にします。 |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 派生クラスでオーバーライドされた場合、[XPathNavigator](./)を指定された[XPathNavigator](./)と同じ位置に移動します。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)を一致するローカル名と名前空間URIを持つ属性へ移動します。 |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)を指定されたローカル名と名前空間URIを持つ子ノードへ移動します。 |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)を指定されたXPathNodeTypeの子ノードへ移動します。 |
| virtual **bool** [MoveToFirst](./movetofirst/)() | [XPathNavigator](./)を現在のノードの最初の兄弟ノードへ移動します。 |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 派生クラスでオーバーライドされた場合、[XPathNavigator](./)を現在のノードの最初の属性へ移動します。 |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | 派生クラスでオーバーライドされた場合、[XPathNavigator](./)を現在のノードの最初の子ノードへ移動します。 |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 派生クラスでオーバーライドされた場合、[XPathNavigator](./)を指定されたXPathNamespaceScopeに一致する最初の名前空間ノードへ移動します。 |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | 現在のノードの最初の名前空間ノードへ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | 文書順で指定されたローカル名と名前空間URIを持つ要素へ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 文書順で、指定されたローカル名と名前空間URIを持つ要素へ、指定された境界まで[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | 文書順で指定されたXPathNodeTypeの次の要素へ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 文書順で、指定されたXPathNodeTypeの次の要素へ、指定された境界まで[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、タイプが**ID**の属性を持ち、その値が指定された[String](../../system/string/)と一致するノードへ移動します。 |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | 指定された名前空間プレフィックスを持つ名前空間ノードへ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToNext](./movetonext/)() | 派生クラスでオーバーライドされた場合、現在のノードの次の兄弟ノードへ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | 指定されたローカル名と名前空間URIを持つ次の兄弟ノードへ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | 現在のノードの次の兄弟ノードで、指定されたXPathNodeTypeと一致するものへ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 派生クラスでオーバーライドされた場合、次の属性へ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 派生クラスでオーバーライドされた場合、指定されたXPathNamespaceScopeに一致する次の名前空間ノードへ[XPathNavigator](./)を移動します。 |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | [XPathNavigator](./)を次の名前空間ノードへ移動します。 |
| virtual **bool** [MoveToParent](./movetoparent/)() | 派生クラスでオーバーライドされた場合、現在のノードの親ノードへ[XPathNavigator](./)を移動します。 |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | 派生クラスでオーバーライドされた場合、現在のノードの前の兄弟ノードへ[XPathNavigator](./)を移動します。 |
| virtual void [MoveToRoot](./movetoroot/)() | [XPathNavigator](./)を現在のノードが所属するルートノードへ移動します。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | 現在のノードの子ノードリストの先頭に新しい子ノードを作成するために使用される[XmlWriter](../../system.xml/xmlwriter/)オブジェクトを返します。 |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | 指定されたXML文字列を使用して、現在のノードの子ノードリストの先頭に新しい子ノードを作成します。 |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 指定された[XmlReader](../../system.xml/xmlreader/)オブジェクトのXML内容を使用して、現在のノードの子ノードリストの先頭に新しい子ノードを作成します。 |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 指定された[XPathNavigator](./)オブジェクト内のノードを使用して、現在のノードの子ノードリストの先頭に新しい子ノードを作成します。 |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 指定された名前空間プレフィックス、ローカル名、名前空間URIとその値を使用して、現在のノードの子ノードリストの先頭に新しい子要素を作成します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | 現在のノードとその子ノードを含む[XmlReader](../../system.xml/xmlreader/)オブジェクトを返します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトをnullptrと参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)の文字列とnullptrの場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 現在のノードから指定されたノードまでの兄弟ノードの範囲を置き換えます。 |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | 指定された文字列の内容で現在のノードを置き換えます。 |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 指定された[XmlReader](../../system.xml/xmlreader/)オブジェクトの内容で現在のノードを置き換えます。 |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 指定された[XPathNavigator](./)オブジェクトの内容で現在のノードを置き換えます。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | 指定された[XPath](../)式を使用してノードセットを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 指定された[XPath](../)式と名前空間プレフィックス解決のために指定された[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)オブジェクトを使用してノードセットを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 指定された[XPathExpression](../xpathexpression/)を使用してノードセットを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | 現在のノードのXPathNodeTypeと一致するすべての祖先ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | 現在のノードの指定されたローカル名と名前空間URIを持つすべての祖先ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | 現在のノードのXPathNodeTypeと一致するすべての子ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | 現在のノードの指定されたローカル名と名前空間URIを持つすべての子ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | 現在のノードのXPathNodeTypeと一致するすべての子孫ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | 現在のノードの指定されたローカル名と名前空間URIを持つすべての子孫ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | 指定された[XPath](../)クエリを使用して[XPathNavigator](./)内の単一ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 指定された[XPath](../)クエリと名前空間プレフィックス解決のために指定された[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)オブジェクトを使用して、[XPathNavigator](./)オブジェクト内の単一ノードを選択します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 指定された[XPathExpression](../xpathexpression/)オブジェクトを使用して[XPathNavigator](./)内の単一ノードを選択します。 |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | 現在のノードの子ノードを表すマークアップを設定します。 |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | 現在のノードとその子ノードの開始タグと終了タグを表すマークアップを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n番目のテンプレート引数を弱ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 現在のノードの型付けされた値を設定します。 |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | 現在のノードの値を設定します。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたはThisProtectorを使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたはThisProtectorを使用してください。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 現在のノードのテキスト値を返します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | 指定された[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)オブジェクトで名前空間プレフィックスを解決し、指定された型として現在のノードの値を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | アイテムの値を指定された型で返します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたはThisProtectorを使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたはThisProtectorを使用してください。 |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | 現在のノードとその子ノードを指定された[XmlWriter](../../system.xml/xmlwriter/)オブジェクトにストリームします。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 参照

* クラス [XPathItem](../xpathitem/)
* クラス [IXPathNavigable](../ixpathnavigable/)
* クラス [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* 名前空間 [System::Xml::XPath](../)
* ライブラリ [Aspose.Slides](../../)