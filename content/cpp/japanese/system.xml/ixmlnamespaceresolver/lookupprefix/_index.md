---
title: LookupPrefix()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 指定された名前空間 URI にマップされているプレフィックスを返します。
type: docs
weight: 27
url: /ja/system.xml/ixmlnamespaceresolver/lookupprefix/
---
## IXmlNamespaceResolver::LookupPrefix(const String\&) メソッド


指定された名前空間 URI にマップされているプレフィックスを返します。

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupPrefix(const String &namespaceName)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| namespaceName | const [String](../../../system/string/)\& | プレフィックスを取得したい名前空間 URI。 |

### 戻り値

名前空間 URI にマップされているプレフィックス；プレフィックスがマップされていない場合は **nullptr** が返されます。

## 参照

* クラス [String](../../../system/string/)
* クラス [IXmlNamespaceResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)