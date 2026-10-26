---
title: WriteNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、リーダーからライターへすべてをコピーし、リーダーを次の兄弟要素の先頭に移動します。
type: docs
weight: 430
url: /ja/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) メソッド

派生クラスでオーバーライドされた場合、リーダーからライターへすべてをコピーし、リーダーを次の兄弟要素の先頭に移動します。

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) を読み取るためのものです。 |
| defattr | **bool** | **true** で [XmlReader](../../xmlreader/) からデフォルト属性をコピーし、**false** でコピーしません。 |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) メソッド

XPathNavigator オブジェクトからライターへすべてをコピーします。XPathNavigator の位置は変更されません。

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | コピー元となる XPathNavigator。 |
| defattr | **bool** | **true** でデフォルト属性をコピーし、**false** でコピーしません。 |

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlReader](../../xmlreader/)
* クラス [XmlWriter](../)
* クラス [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)