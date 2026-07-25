---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたプレフィックスの名前空間 URI を返します。
type: docs
weight: 404
url: /ja/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) メソッド

指定されたプレフィックスの名前空間 URI を返します。

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 解決したい名前空間 URI を持つプレフィックスです。デフォルト名前空間に一致させるには、[String::Empty](../../../system/string/empty/) を渡します。 |

### 戻り値

指定された名前空間プレフィックスに割り当てられた名前空間 URI を含む [String](../../../system/string/) です。プレフィックスに名前空間 URI が割り当てられていない場合は **nullptr** が返されます。返される [String](../../../system/string/) はアトミック化されています。

## 参照

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)