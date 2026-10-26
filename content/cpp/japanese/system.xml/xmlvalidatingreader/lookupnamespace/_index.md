---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の要素のスコープで名前空間プレフィックスを解決します。
type: docs
weight: 547
url: /ja/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) メソッド


現在の要素のスコープで名前空間プレフィックスを解決します。

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 解決したい名前空間の Uniform Resource Identifier (URI) を持つプレフィックスです。デフォルト名前空間に一致させるには、空文字列を渡してください。 |

### 戻り値

プレフィックスがマッピングされる名前空間の URI、または一致するプレフィックスが見つからなかった場合は **nullptr**。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)