---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前に一致するすべての子孫要素のリストを含む XmlNodeList を返します。
type: docs
weight: 443
url: /ja/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) メソッド

[XmlNodeList](../../xmlnodelist/) を返します。このコレクションは、指定された名前に一致するすべての子孫要素のリストを含みます。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 一致させる修飾名です。マッチするノードの **get_Name** の値と比較されます。特別な値 **"*"** はすべてのタグに一致します。 |

### 戻り値

[XmlNodeList](../../xmlnodelist/) は、一致するすべてのノードのリストを含みます。**name** に一致するノードがない場合、返されるコレクションは空になります。

## XmlDocument::GetElementsByTagName(String, String) メソッド

[XmlNodeList](../../xmlnodelist/) を返します。このコレクションは、指定された [XmlDocument::get_LocalName](../get_localname/) と [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) に一致するすべての子孫要素のリストを含みます。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 一致させる LocalName です。特別な値 **"*"** はすべてのタグに一致します。 |
| namespaceURI | [String](../../../system/string/) | 一致させる NamespaceURI。 |

### 戻り値

[XmlNodeList](../../xmlnodelist/) は、一致するすべてのノードのリストを含みます。指定された **localName** と **namespaceURI** に一致するノードがない場合、返されるコレクションは空になります。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNodeList](../../xmlnodelist/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)