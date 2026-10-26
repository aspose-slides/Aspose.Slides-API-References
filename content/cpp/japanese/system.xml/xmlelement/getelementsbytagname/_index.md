---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API リファレンス
description: "指定された XmlElement::get_Name に一致するすべての子孫要素のリストを含む XmlNodeList を返します。"
type: docs
weight: 287
url: /ja/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) method


指定された[XmlElement::get_Name](../get_name/)に一致するすべての子孫要素のリストを含む[XmlNodeList](../../xmlnodelist/)を返します。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 一致させる名前タグです。これは修飾名です。一致するノードの **get_Name** の値と照合されます。アスタリスク (*) はすべてのタグに一致する特別な値です。 |

### 戻り値

一致するノードのリストを含む[XmlNodeList](../../xmlnodelist/)。一致するノードがない場合、リストは空です。

## XmlElement::GetElementsByTagName(String, String) method


指定された[XmlElement::get_LocalName](../get_localname/)と[XmlElement::get_NamespaceURI](../get_namespaceuri/)の値に一致するすべての子孫要素のリストを含む[XmlNodeList](../../xmlnodelist/)を返します。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 一致させるローカル名です。アスタリスク (*) はすべてのタグに一致する特別な値です。 |
| namespaceURI | [String](../../../system/string/) | 一致させる名前空間 URI です。 |

### 戻り値

一致するノードのリストを含む[XmlNodeList](../../xmlnodelist/)。一致するノードがない場合、リストは空です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNodeList](../../xmlnodelist/)
* クラス [String](../../../system/string/)
* クラス [XmlElement](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)