---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前空間 URI に宣言されたプレフィックスを検索します。
type: docs
weight: 131
url: /ja/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) method

指定された名前空間 URI に対して宣言されたプレフィックスを検索します。

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | プレフィックスを解決するための名前空間。 |

### 戻り値

一致するプレフィックス。マッピングされたプレフィックスがない場合、メソッドは [String::Empty](../../../system/string/empty/) を返します。null 値が指定された場合、**nullptr** が返されます。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNamespaceManager](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)