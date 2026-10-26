---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: "指定された XmlNode::get_Name を持つ最初の子要素を返します。"
type: docs
weight: 586
url: /ja/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) メソッド

指定された[XmlNode::get_Name](../get_name/)を持つ最初の子要素を返します。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 取得する要素の修飾名。 |

### 戻り値

指定された名前に一致する最初の[XmlElement](../../xmlelement/)。一致しない場合は **nullptr** を返します。

## XmlNode::idx_get(String, String) メソッド

指定された[XmlNode::get_LocalName](../get_localname/)と[XmlNode::get_NamespaceURI](../get_namespaceuri/)の値を持つ最初の子要素を返します。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 要素のローカル名。 |
| ns | [String](../../../system/string/) | 要素の名前空間URI。 |

### 戻り値

一致する**localname**と**ns**を持つ最初の[XmlElement](../../xmlelement/)。一致しない場合は **nullptr** を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlElement](../../xmlelement/)
* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)