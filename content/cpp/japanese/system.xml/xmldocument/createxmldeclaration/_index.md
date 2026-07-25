---
title: CreateXmlDeclaration()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値で XmlDeclaration ノードを作成します。
type: docs
weight: 378
url: /ja/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String&, const String&, const String&) メソッド

指定された値で [XmlDeclaration](../../xmldeclaration/) ノードを作成します。

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | バージョンは "1.0" である必要があります。 |
| encoding | const [String](../../../system/string/)\& | エンコーディング属性の値です。これは [XmlDocument](../) をファイルまたはストリームに保存する際に使用されるエンコーディングであり、したがって [Text::Encoding](../../../system.text/encoding/) クラスがサポートする文字列に設定する必要があります。そうしないと "XmlDocument::Save(String)" が失敗します。これが **nullptr** または [String::Empty](../../../system/string/empty/) の場合、[XmlDocument::Save](../save/) メソッドは XML 宣言にエンコーディング属性を書き込まず、デフォルトのエンコーディング UTF-8 が使用されます。 |
| standalone | const [String](../../../system/string/)\& | 値は "yes" または "no" のいずれかである必要があります。これが **nullptr** または [String::Empty](../../../system/string/empty/) の場合、[XmlDocument::Save](../save/) メソッドは XML 宣言に standalone 属性を書き込みません。 |

### 戻り値

新しい [XmlDeclaration](../../xmldeclaration/) ノードです。

## 備考

注: [XmlDocument](../) が TextWriter または [XmlTextWriter](../../xmltextwriter/) のいずれかに保存された場合、このエンコーディング値は破棄されます。その代わりに TextWriter または [XmlTextWriter](../../xmltextwriter/) のエンコーディングが使用されます。これにより、書き出された XML を正しいエンコーディングで再度読み取ることが保証されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlDeclaration](../../xmldeclaration/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)