---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい XmlDocumentType オブジェクトを返します。
type: docs
weight: 313
url: /ja/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) メソッド

新しい[XmlDocumentType](../../xmldocumenttype/)オブジェクトを返します。

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ドキュメントタイプの名前です。 |
| publicId | const [String](../../../system/string/)\& | ドキュメントタイプのパブリック識別子または **nullptr**。パブリックURIとシステム識別子の両方を指定して、外部DTDサブセットの場所を識別できます。 |
| systemId | const [String](../../../system/string/)\& | ドキュメントタイプのシステム識別子または **nullptr**。外部DTDサブセットのファイル場所のURLを指定します。 |
| internalSubset | const [String](../../../system/string/)\& | ドキュメントタイプのDTD内部サブセットまたは **nullptr**。 |

### 戻り値

新しい[XmlDocumentType](../../xmldocumenttype/)です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlDocumentType](../../xmldocumenttype/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)