---
title: LookupNamespace()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 現在の要素のスコープで名前空間プレフィックスを解決します。
type: docs
weight: 404
url: /ja/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) メソッド

現在の要素のスコープで名前空間プレフィックスを解決します。

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 解決したい名前空間URIを持つプレフィックスです。デフォルトの名前空間に一致させるには、空文字列を渡します。この文字列はアトム化する必要はありません。 |

### 戻り値

プレフィックスがマップされる名前空間URI、または一致するプレフィックスが見つからない場合は **nullptr** 。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)