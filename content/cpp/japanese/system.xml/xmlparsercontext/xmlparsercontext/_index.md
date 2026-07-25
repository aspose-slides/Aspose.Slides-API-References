---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API リファレンス
description: "指定された XmlNameTable、XmlNamespaceManager、xml:lang、xml:space の値を使用して XmlParserContext クラスの新しいインスタンスを初期化します。"
type: docs
weight: 261
url: /ja/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) コンストラクタ

指定された [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、**xml:lang**、**xml:space** の値を使用して [XmlParserContext](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) を使用して文字列をアトミック化するためのものです。これが **nullptr** の場合、**nsMgr** を構築する際に使用された名前テーブルが代わりに使用されます。アトミック化された文字列の詳細については、[XmlNameTable](../../xmlnametable/) を参照してください。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) を使用して名前空間情報を検索するためのもの、または **nullptr**。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** のスコープです。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** のスコープを示す XmlSpace 値です。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) コンストラクタ

指定された [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、**xml:lang**、**xml:space**、エンコーディングを使用して [XmlParserContext](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) を使用して文字列をアトミック化するためのものです。これが **nullptr** の場合、**nsMgr** を構築する際に使用された名前テーブルが代わりに使用されます。アトミック化された文字列の詳細については、[XmlNameTable](../../xmlnametable/) を参照してください。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) を使用して名前空間情報を検索するためのもの、または **nullptr**。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** のスコープです。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** のスコープを示す XmlSpace 値です。 |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | エンコーディング設定を示す Encoding オブジェクトです。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) コンストラクタ

指定された [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、ベース URI、**xml:lang**、**xml:space**、ドキュメントタイプの値を使用して [XmlParserContext](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) を使用して文字列をアトミック化するためのものです。これが **nullptr** の場合、**nsMgr** を構築する際に使用された名前テーブルが代わりに使用されます。アトミック化された文字列の詳細については、[XmlNameTable](../../xmlnametable/) を参照してください。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) を使用して名前空間情報を検索するためのもの、または **nullptr**。 |
| docTypeName | const [String](../../../system/string/)\& | ドキュメントタイプ宣言の名前です。 |
| pubId | const [String](../../../system/string/)\& | 公開識別子です。 |
| sysId | const [String](../../../system/string/)\& | システム識別子です。 |
| internalSubset | const [String](../../../system/string/)\& | 内部 DTD サブセットです。DTD サブセットはエンティティ解決に使用され、ドキュメントの検証には使用されません。 |
| baseURI | const [String](../../../system/string/)\& | XML フラグメントのベース URI（フラグメントが読み込まれた場所）です。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** のスコープです。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** のスコープを示す XmlSpace 値です。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) コンストラクタ

指定された [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、ベース URI、**xml:lang**、**xml:space**、エンコーディング、ドキュメントタイプの値を使用して [XmlParserContext](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) を使用して文字列をアトミック化するためのものです。これが **nullptr** の場合、**nsMgr** を構築する際に使用された名前テーブルが代わりに使用されます。アトミック化された文字列の詳細については、[XmlNameTable](../../xmlnametable/) を参照してください。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) を使用して名前空間情報を検索するためのもの、または **nullptr**。 |
| docTypeName | const [String](../../../system/string/)\& | ドキュメントタイプ宣言の名前です。 |
| pubId | const [String](../../../system/string/)\& | 公開識別子です。 |
| sysId | const [String](../../../system/string/)\& | システム識別子です。 |
| internalSubset | const [String](../../../system/string/)\& | 内部 DTD サブセットです。DTD はエンティティ解決に使用され、ドキュメントの検証には使用されません。 |
| baseURI | const [String](../../../system/string/)\& | XML フラグメントのベース URI（フラグメントが読み込まれた場所）です。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** のスコープです。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** のスコープを示す XmlSpace 値です。 |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | エンコーディング設定を示す Encoding オブジェクトです。 |

## 参照

* 列挙型 [XmlSpace](../../xmlspace/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNameTable](../../xmlnametable/)
* クラス [XmlNamespaceManager](../../xmlnamespacemanager/)
* クラス [String](../../../system/string/)
* クラス [XmlParserContext](../)
* クラス [Encoding](../../../system.text/encoding/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)