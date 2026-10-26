---
title: XmlWriter
second_title: Aspose.Slides for C++ API リファレンス
description: XML データを含むストリームまたはファイルを生成するための、迅速でキャッシュしない前方専用の方法を提供するライターを表します。
type: docs
weight: 573
url: /ja/system.xml/xmlwriter/
---
## XmlWriter クラス

XML データを含むストリームまたはファイルを生成するための、速く、キャッシュせず、前方専用の方法を提供するライターを表します。

```cpp
class XmlWriter : public System::IDisposable
```

## メソッド

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | 派生クラスでオーバーライドされた場合、このストリームと基になるストリームを閉じます。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 指定されたファイル名を使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ファイル名と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 指定されたストリームを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | ストリームと [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 指定された TextWriter を使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 指定された [Text::StringBuilder](../../system.text/stringbuilder/) を使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/) と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | 指定された [XmlWriter](./) オブジェクトを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 指定された [XmlWriter](./) と [XmlWriterSettings](../xmlwritersettings/) オブジェクトを使用して新しい [XmlWriter](./) インスタンスを作成します。 |
| void [Dispose](./dispose/)() override | 現在の [XmlWriter](./) クラスのインスタンスが使用しているすべてのリソースを解放します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| virtual void [Flush](./flush/)() | 派生クラスでオーバーライドされた場合、バッファ内のデータを基になるストリームへフラッシュし、さらに基になるストリームもフラッシュします。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | この [XmlWriter](./) インスタンスの作成に使用された [XmlWriterSettings](../xmlwritersettings/) オブジェクトを返します。 |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | 派生クラスでオーバーライドされた場合、ライターの状態を取得します。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 派生クラスでオーバーライドされた場合、現在の **xml:lang** スコープを取得します。 |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 派生クラスでオーバーライドされた場合、現在の **xml:space** スコープを表す XmlSpace を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントによるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、現在の名前空間スコープで名前空間 URI に対して定義された最も近いプレフィックスを返します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|   [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱いモードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 派生クラスでオーバーライドされた場合、[XmlReader](../xmlreader/) の現在位置にあるすべての属性を書き出します。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたローカル名、名前空間 URI、値を持つ属性を書き込みます。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたローカル名と値を持つ属性を書き出します。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたプレフィックス、ローカル名、名前空間 URI、値を持つ属性を書き出します。 |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 派生クラスでオーバーライドされた場合、指定されたバイナリバイトを Base64 にエンコードし、結果のテキストを書き出します。 |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 派生クラスでオーバーライドされた場合、指定されたバイナリバイトを **BinHex** にエンコードし、結果のテキストを書き出します。 |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定されたテキストを含む **...** ブロックを書き出します。 |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | 派生クラスでオーバーライドされた場合、指定された Unicode 文字値の文字エンティティ生成を強制します。 |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 派生クラスでオーバーライドされた場合、テキストをバッファ単位で書き込みます。 |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定されたテキストを含むコメント **** を書き出します。 |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定された名前と任意の属性で DOCTYPE 宣言を書き込みます。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたローカル名と値を持つ要素を書き込みます。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたローカル名、名前空間 URI、値を持つ要素を書き込みます。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたプレフィックス、ローカル名、名前空間 URI、値を持つ要素を書き込みます。 |
| virtual void [WriteEndAttribute](./writeendattribute/)() | 派生クラスでオーバーライドされた場合、直前の XmlWriter::WriteStartAttribute(String,String) 呼び出しを閉じます。 |
| virtual void [WriteEndDocument](./writeenddocument/)() | 派生クラスでオーバーライドされた場合、開いている要素や属性をすべて閉じ、ライターを開始状態に戻します。 |
| virtual void [WriteEndElement](./writeendelement/)() | 派生クラスでオーバーライドされた場合、1つの要素を閉じ、対応する名前空間スコープをポップします。 |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、エンティティ参照として **&name**; を書き出します。 |
| virtual void [WriteFullEndElement](./writefullendelement/)() | 派生クラスでオーバーライドされた場合、1つの要素を閉じ、対応する名前空間スコープをポップします。 |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定された名前を書き出します。その名前が W3C XML 1.0 推奨 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) に従い有効であることを保証します。 |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定された名前を書き出します。その名前が W3C XML 1.0 推奨 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) に従い有効な NmToken であることを保証します。 |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 派生クラスでオーバーライドされた場合、リーダーからライターへすべてをコピーし、リーダーを次の兄弟要素の開始位置へ移動します。 |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator オブジェクトからライターへすべてをコピーします。XPathNavigator の位置は変更されません。 |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | 派生クラスでオーバーライドされた場合、名前とテキストの間にスペースを入れた処理指示子 **<?name text?>** を書き出します。 |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、名前空間で修飾された名前を書き出します。このメソッドは、指定された名前空間に対してスコープ内のプレフィックスを検索します。 |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 派生クラスでオーバーライドされた場合、文字バッファから生のマークアップを手動で書き出します。 |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、文字列から生のマークアップを手動で書き出します。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたローカル名と名前空間 URI を持つ属性の開始を書き込みます。 |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたプレフィックス、ローカル名、名前空間 URI を持つ属性の開始を書き込みます。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | 指定されたローカル名を持つ属性の開始を書き込みます。 |
| virtual void [WriteStartDocument](./writestartdocument/)() | 派生クラスでオーバーライドされた場合、バージョン "1.0" の XML 宣言を書き込みます。 |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | 派生クラスでオーバーライドされた場合、バージョン "1.0" と standalone 属性を持つ XML 宣言を書き込みます。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定された開始タグを書き込み、与えられた名前空間に関連付けます。 |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定された開始タグを書き込み、与えられた名前空間とプレフィックスに関連付けます。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたローカル名の開始タグを書き出します。 |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | 派生クラスでオーバーライドされた場合、指定されたテキストコンテンツを書き込みます。 |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | 派生クラスでオーバーライドされた場合、サロゲート文字ペアのサロゲート文字エンティティを生成し、書き込みます。 |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | オブジェクトの値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)(**bool**) | [Boolean](../../system/boolean/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)(**double**) | [Double](../../system/double/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)(**float**) | 単精度浮動小数点数を書き込みます。 |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | [Int32](../../system/int32/) の値を書き込みます。 |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | [Int64](../../system/int64/) の値を書き込みます。 |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | 派生クラスでオーバーライドされた場合、指定された空白文字を書き出します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## typedef

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタの別名です。 |

## 参照

* クラス [IDisposable](../../system/idisposable/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)