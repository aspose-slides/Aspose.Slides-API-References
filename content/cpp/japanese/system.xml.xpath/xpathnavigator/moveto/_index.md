---
title: MoveTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、XPathNavigator を指定された XPathNavigator と同じ位置に移動します。
type: docs
weight: 664
url: /ja/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) メソッド

派生クラスでオーバーライドされた場合、指定された[XPathNavigator](../)と同じ位置に[XPathNavigator](../)を移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 移動したいノード上に位置する[XPathNavigator](../)です。 |

### 戻り値

**true** は、[XPathNavigator](../) が指定された [XPathNavigator](../) と同じ位置へ正常に移動した場合です。それ以外の場合は **false** です。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)