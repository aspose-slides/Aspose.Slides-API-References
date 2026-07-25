---
title: XmlTextWriter
second_title: Aspose.Slides for C++ API リファレンス
description: W3C の拡張可能マークアップ言語 (XML) 1.0 および XML の名前空間の勧告に準拠した XML データを含むストリームまたはファイルを高速かつキャッシュなし、順方向のみで生成するライターを表します。
type: docs
weight: 521
url: /ja/system.xml/xmltextwriter/
---
## XmlTextWriter クラス

高速でキャッシュを使用せず、順方向のみの方式で、W3C 拡張可能マークアップ言語 (XML) 1.0 および XML の名前空間に準拠した XML データを含むストリームまたはファイルを生成するライターを表します。

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Close](./close/)() override | このストリームと基になるストリームを閉じます。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | 指定されたファイル名を使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ファイル名と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 指定されたストリームを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ストリームと [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 指定された TextWriter を使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 指定された [Text::StringBuilder](../../system.text/stringbuilder/) を使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/) と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | 指定された [XmlWriter](../xmlwriter/) オブジェクトを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 指定された [XmlWriter](../xmlwriter/) と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](../xmlwriter/) インスタンスを作成します。 |
| void [Dispose](../xmlwriter/dispose/)() override | [XmlWriter](../xmlwriter/) クラスの現在のインスタンスが使用しているすべてのリソースを解放します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| void [Flush](./flush/)() override | バッファの内容を基になるストリームにフラッシュし、さらに基になるストリームもフラッシュします。 |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | 基になるストリームオブジェクトを返します。 |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | 出力がどのようにフォーマットされるかを示します。 |
| **int32_t** [get_Indentation](./get_indentation/)() | [XmlTextWriter::set_Formatting](./set_formatting/) が [Formatting::Indented](../formatting/) に設定されている場合、階層の各レベルで書き込む IndentChars の数を返します。 |
| char16_t [get_IndentChar](./get_indentchar/)() | [XmlTextWriter::set_Formatting](./set_formatting/) が [Formatting::Indented](../formatting/) に設定されている場合、インデントに使用する文字を返します。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 名前空間サポートを行うかどうかを示す値を返します。 |
| char16_t [get_QuoteChar](./get_quotechar/)() | 属性値を引用する際に使用する文字を返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | この [XmlWriter](../xmlwriter/) インスタンスの作成に使用された [XmlWriterSettings](../xmlwritersettings/) オブジェクトを返します。 |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | ライターの状態を返します。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 現在の **xml:lang** スコープを返します。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 現在の **xml:space** スコープを表す XmlSpace を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | 名前空間 URI に対して現在の名前空間スコープで定義された最も近いプレフィックスを返します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | 出力がどのようにフォーマットされるかを示します。 |
| void [set_Indentation](./set_indentation/)(**int32_t**) | [XmlTextWriter::set_Formatting](./set_formatting/) が [Formatting::Indented](../formatting/) に設定されている場合、階層の各レベルで書き込む IndentChars の数を設定します。 |
| void [set_IndentChar](./set_indentchar/)(char16_t) | [XmlTextWriter::set_Formatting](./set_formatting/) が [Formatting::Indented](../formatting/) に設定されている場合、インデントに使用する文字を設定します。 |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 名前空間サポートを行うかどうかを示す値を設定します。 |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | 属性値を引用する際に使用する文字を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、その値を返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 派生クラスでオーバーライドされた場合、[XmlReader](../xmlreader/) の現在位置で見つかったすべての属性を書き出します。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたローカル名、名前空間 URI、値を持つ属性を書き出します。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたローカル名と値の属性を書き出します。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたプレフィックス、ローカル名、名前空間 URI、値の属性を書き出します。 |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 指定されたバイナリバイトを base64 にエンコードし、結果のテキストを書き出します。 |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 指定されたバイナリバイトを binhex にエンコードし、結果のテキストを書き出します。 |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | 指定されたテキストを含む **...** ブロックを書き出します。 |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | 指定された Unicode 文字値の文字実体の生成を強制します。 |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | テキストをバッファごとに書き込みます。 |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | 指定されたテキストを含むコメント **** を書き出します。 |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 指定された名前とオプション属性で DOCTYPE 宣言を書き出します。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたローカル名と値を持つ要素を書き出します。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたローカル名、名前空間 URI、値を持つ要素を書き出します。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたプレフィックス、ローカル名、名前空間 URI、値を持つ要素を書き出します。 |
| void [WriteEndAttribute](./writeendattribute/)() override | 前の [XmlTextWriter::WriteStartAttribute](./writestartattribute/) 呼び出しを閉じます。 |
| void [WriteEndDocument](./writeenddocument/)() override | 開いている要素や属性をすべて閉じ、ライターを Start 状態に戻します。 |
| void [WriteEndElement](./writeendelement/)() override | 1 つの要素を閉じ、対応する名前空間スコープをポップします。 |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | エンティティ参照を **&name**; として書き出します。 |
| void [WriteFullEndElement](./writefullendelement/)() override | 1 つの要素を閉じ、対応する名前空間スコープをポップします。 |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) に従って有効な名前であることを確認しながら、指定された名前を書き出します。 |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) に従って有効な **NmToken** であることを確認しながら、指定された名前を書き出します。 |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 派生クラスでオーバーライドされた場合、リーダーからライターへすべてをコピーし、リーダーを次の兄弟の先頭に移動します。 |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator オブジェクトからライターへすべてをコピーします。XPathNavigator の位置は変更されません。 |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | 名前とテキストの間にスペースを入れた処理命令を次のように書き出します: **<?name text?>**。 |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 名前空間で修飾された名前を書き出します。このメソッドは、指定された名前空間に対してスコープ内のプレフィックスを検索します。 |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 文字バッファから生のマークアップを手動で書き出します。 |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | 文字列から生のマークアップを手動で書き出します。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 属性の開始を記述します。 |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたローカル名と名前空間 URI を持つ属性の開始を書き出します。 |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | 指定されたローカル名を持つ属性の開始を書き出します。 |
| void [WriteStartDocument](./writestartdocument/)() override | バージョン "1.0" の XML 宣言を書き出します。 |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | バージョン "1.0" と standalone 属性を持つ XML 宣言を書き出します。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 指定された開始タグを書き出し、与えられた名前空間とプレフィックスに関連付けます。 |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定された開始タグを書き出し、与えられた名前空間に関連付けます。 |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたローカル名の開始タグを書き出します。 |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | 指定されたテキストコンテンツを書き出します。 |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | サロゲート文字ペアのサロゲート文字実体を生成し、書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | オブジェクトの値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | [Boolean](../../system/boolean/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | [Double](../../system/double/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | 単精度浮動小数点数を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | [Int32](../../system/int32/) の値を書き出します。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | [Int64](../../system/int64/) の値を書き出します。 |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | 指定された空白文字を書き出します。 |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 指定されたストリームとエンコーディングを使用して [XmlTextWriter](./) クラスのインスタンスを作成します。 |
| [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 指定されたファイルを使用して [XmlTextWriter](./) クラスのインスタンスを作成します。 |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 指定された TextWriter を使用して [XmlTextWriter](./) クラスのインスタンスを作成します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 型定義

| 型エイリアス | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 備考

代わりに [XmlWriter](../xmlwriter/) クラスの使用が推奨されます。

このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

## 参照

* クラス [XmlWriter](../xmlwriter/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)