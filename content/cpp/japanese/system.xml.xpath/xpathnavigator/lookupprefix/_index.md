---
title: LookupPrefix()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定された名前空間URIに対して宣言されたプレフィックスを返します。
type: docs
weight: 417
url: /ja/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) メソッド


指定された名前空間URIに対して宣言されたプレフィックスを返します。

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | プレフィックスを解決するための名前空間URIです。 |

### 戻り値

指定された名前空間URIに割り当てられた名前空間プレフィックスを含む[String](../../../system/string/)です。割り当てられたプレフィックスがない場合は[String::Empty](../../../system/string/empty/)が返されます。返される[String](../../../system/string/)は原子化されています。

## 参照

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)