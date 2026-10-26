---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の要素のスコープ内で名前空間プレフィックスを解決します。
type: docs
weight: 612
url: /ja/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) メソッド


現在の要素のスコープ内の名前空間プレフィックスを解決します。

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 解決したい名前空間URIを持つプレフィックスです。デフォルト名前空間に一致させるには、空文字列を渡してください。この文字列は原子化する必要はありません。 |

### 戻り値

プレフィックスがマップされる名前空間URI、または一致するプレフィックスが見つからない場合は **nullptr**。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)