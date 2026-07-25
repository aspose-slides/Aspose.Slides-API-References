---
title: XmlReaderSettings
second_title: Aspose.Slides for C++ API リファレンス
description: "XmlReader::Create メソッドによって作成された XmlReader オブジェクトでサポートする機能のセットを指定します。"
type: docs
weight: 443
url: /ja/system.xml/xmlreadersettings/
---
## XmlReaderSettings クラス

[XmlReader](../xmlreader/) オブジェクトが [XmlReader::Create](../xmlreader/create/) メソッドによって作成された際にサポートする機能のセットを指定します。

```cpp
class XmlReaderSettings : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | [XmlReaderSettings](./) インスタンスのコピーを作成します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用のみです。 |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | 文字チェックを行うかどうかを示す値を返します。 |
| **bool** [get_CloseInput](./get_closeinput/)() | リーダーが閉じられたときに基底ストリームまたは TextReader を閉じるかどうかを示す値を返します。 |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | [XmlReader](../xmlreader/) が準拠する適合レベルを返します。 |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | DTD の処理を決定する値を返します。 |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | コメントを無視するかどうかを示す値を返します。 |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | 処理指示を無視するかどうかを示す値を返します。 |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | 重要でない空白を無視するかどうかを示す値を返します。 |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | [XmlReader](../xmlreader/) オブジェクトの行番号オフセットを返します。 |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | [XmlReader](../xmlreader/) オブジェクトの行位置オフセットを返します。 |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | エンティティ展開により生成される文書内の文字数の最大許容数を示す値を返します。 |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | XML 文書内の文字数の最大許容数を示す値を返します。0 の場合は XML 文書のサイズに制限がありません。0 以外の場合は文字数で最大サイズを指定します。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | アトミック文字列比較に使用される [XmlNameTable](../xmlnametable/) を返します。 |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | 文書型定義 (DTD) の処理を禁止するかどうかを示す値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | スキーマ検証を実行する際に使用する XmlSchemaSet を返します。 |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | スキーマ検証設定を示す値を返します。この設定はスキーマを検証する [XmlReader](../xmlreader/) オブジェクトに適用されます ([XmlReaderSettings::get_ValidationType](./get_validationtype/) の値は [ValidationType::Schema](../validationtype/))。 |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | 読み取り時に [XmlReader](../xmlreader/) が検証または型割り当てを実行するかどうかを示す値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を有効にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を有効にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [Reset](./reset/)() | 設定クラスのメンバーをデフォルト値にリセットします。 |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | 文字チェックを行うかどうかを示す値を設定します。 |
| void [set_CloseInput](./set_closeinput/)(**bool**) | リーダーが閉じられたときに基底ストリームまたは TextReader を閉じるかどうかを示す値を設定します。 |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | [XmlReader](../xmlreader/) が準拠する適合レベルを設定します。 |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | DTD の処理を決定する値を設定します。 |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | コメントを無視するかどうかを示す値を設定します。 |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | 処理指示を無視するかどうかを示す値を設定します。 |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | 重要でない空白を無視するかどうかを示す値を設定します。 |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | [XmlReader](../xmlreader/) オブジェクトの行番号オフセットを設定します。 |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | [XmlReader](../xmlreader/) オブジェクトの行位置オフセットを設定します。 |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | エンティティ展開により生成される文書内の文字数の最大許容数を示す値を設定します。 |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | XML 文書の文字数の最大許容数を示す値を設定します。0 の場合は XML 文書のサイズに制限がありません。0 以外の場合は文字数で最大サイズを指定します。 |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | アトミック文字列比較に使用される [XmlNameTable](../xmlnametable/) を設定します。 |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | 文書型定義 (DTD) の処理を禁止するかどうかを示す値を設定します。 |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | スキーマ検証を実行する際に使用する XmlSchemaSet を設定します。 |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | スキーマ検証設定を示す値を設定します。この設定はスキーマを検証する [XmlReader](../xmlreader/) オブジェクトに適用されます ([XmlReaderSettings::get_ValidationType](./get_validationtype/) の値は [ValidationType::Schema](../validationtype/))。 |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | 読み取り時に [XmlReader](../xmlreader/) が検証または型割り当てを実行するかどうかを示す値を設定します。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | 外部文書へアクセスするために使用される [XmlResolver](../xmlresolver/) を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させて返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | リーダーが検証エラーに遭遇したときに発生するイベントハンドラを追加します。 |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | リーダーが検証エラーに遭遇したときに発生するイベントハンドラを削除します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [XmlReaderSettings](./xmlreadersettings/)() | [XmlReaderSettings](./) クラスの新しいインスタンスを初期化します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型定義

| typedef | 説明 |
| --- | --- |
| [Ptr](./ptr/) | このクラスのインスタンスへの共有ポインタのエイリアスです。 |

## 備考

このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)