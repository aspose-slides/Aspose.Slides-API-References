---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、現在の要素のスコープで名前空間プレフィックスを解決します。
type: docs
weight: 729
url: /ja/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) メソッド

派生クラスでオーバーライドされた場合、現在の要素のスコープで名前空間プレフィックスを解決します。

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 解決したい名前空間URIを持つプレフィックスです。デフォルト名前空間に一致させるには、空文字列を渡してください。 |

### 戻り値

プレフィックスがマップされる名前空間URI、または一致するプレフィックスが見つからない場合は **nullptr** 。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)