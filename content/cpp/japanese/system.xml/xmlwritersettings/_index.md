---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API リファレンス
description: "XmlWriter::Create メソッドで作成された XmlWriter オブジェクトでサポートする機能のセットを指定します。"
type: docs
weight: 586
url: /ja/system.xml/xmlwritersettings/
---
## XmlWriterSettings クラス

[XmlWriter](../xmlwriter/) オブジェクトが [XmlWriter::Create](../xmlwriter/create/) メソッドで作成された際にサポートすべき機能のセットを指定します。

```cpp
class XmlWriterSettings : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | [XmlWriterSettings](./) インスタンスのコピーを作成します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | XML ライターが文書内のすべての文字が W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) の "2.2 Characters" セクションに準拠しているかをチェックすべきかを示す値を返します。 |
| **bool** [get_CloseOutput](./get_closeoutput/)() | [XmlWriter::Close](../xmlwriter/close/) メソッドが呼び出されたときに [XmlWriter](../xmlwriter/) が基礎となるストリームまたは TextWriter も閉じるかどうかを示す値を返します。 |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | XML ライターが XML 出力の準拠レベルをチェックする際のレベルを返します。 |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | [XmlWriter](../xmlwriter/) が URI 属性をエスケープしないかどうかを示す値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 使用するテキストエンコーディングの型を返します。 |
| **bool** [get_Indent](./get_indent/)() | 要素をインデントするかどうかを示す値を返します。 |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | インデント時に使用する文字列を返します。この設定は [XmlWriterSettings::set_Indent](./set_indent/) の値が **true** に設定されている場合に使用されます。 |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | [XmlWriter](../xmlwriter/) が XML コンテンツを書き込む際に重複する名前空間宣言を削除すべきかを示す値を返します。デフォルトの動作は、ライターの名前空間リゾルバに存在するすべての名前空間宣言を出力することです。 |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | 改行に使用する文字列を返します。 |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | 出力の改行を正規化するかどうかを示す値を返します。 |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | 属性を新しい行に書き込むかどうかを示す値を返します。 |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | XML 宣言を省略するかどうかを示す値を返します。 |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | [XmlWriter](../xmlwriter/) 出力をシリアライズするために使用される方法を返します。 |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | [XmlWriter::Close](../xmlwriter/close/) メソッドが呼び出されたときに [XmlWriter](../xmlwriter/) が未閉じの要素タグすべてに閉じタグを追加するかどうかを示す値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [Reset](./reset/)() | 設定クラスのメンバーをデフォルト値にリセットします。 |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | XML ライターが文書内のすべての文字が W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) の "2.2 Characters" セクションに準拠しているかをチェックすべきかを示す値を設定します。 |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | [XmlWriter::Close](../xmlwriter/close/) メソッドが呼び出されたときに [XmlWriter](../xmlwriter/) が基礎となるストリームまたは TextWriter も閉じるかどうかを示す値を設定します。 |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | XML ライターが XML 出力の準拠レベルをチェックするレベルを設定します。 |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | [XmlWriter](../xmlwriter/) が URI 属性をエスケープしないかどうかを示す値を設定します。 |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | 使用するテキストエンコーディングの型を設定します。 |
| void [set_Indent](./set_indent/)(**bool**) | 要素をインデントするかどうかを示す値を設定します。 |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | インデント時に使用する文字列を設定します。この設定は [XmlWriterSettings::set_Indent](./set_indent/) の値が **true** に設定されている場合に使用されます。 |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | [XmlWriter](../xmlwriter/) が XML コンテンツを書き込む際に重複する名前空間宣言を削除すべきかを示す値を設定します。デフォルトの動作は、ライターの名前空間リゾルバに存在するすべての名前空間宣言を出力することです。 |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | 改行に使用する文字列を設定します。 |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | 出力の改行を正規化するかどうかを示す値を設定します。 |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | 属性を新しい行に書き込むかどうかを示す値を設定します。 |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | XML 宣言を省略するかどうかを示す値を設定します。 |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | [XmlWriter::Close](../xmlwriter/close/) メソッドが呼び出されたときに [XmlWriter](../xmlwriter/) が未閉じの要素タグすべてに閉じタグを追加するかどうかを示す値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のアンロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [XmlWriterSettings](./xmlwritersettings/)() | [XmlWriterSettings](./) クラスの新しいインスタンスを初期化します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型定義

| Typedef | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 備考

このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)