---
title: ConformanceLevel
second_title: Aspose.Slides for C++ API リファレンス
description: XmlReader と XmlWriter オブジェクトが実行する入力または出力チェックの量を指定します。
type: docs
weight: 625
url: /ja/system.xml/conformancelevel/
---
## ConformanceLevel 列挙型

[XmlReader](../xmlreader/) および [XmlWriter](../xmlwriter/) オブジェクトが実行する入力または出力チェックの量を指定します。

```cpp
enum class ConformanceLevel
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | 0 | [XmlReader](../xmlreader/) または [XmlWriter](../xmlwriter/) オブジェクトは、ドキュメントレベルまたはフラグメントレベルのチェックを実行すべきかを自動的に検出し、適切なチェックを行います。別の [XmlReader](../xmlreader/) または [XmlWriter](../xmlwriter/) オブジェクトをラップしている場合、外側のオブジェクトは追加のコンフォーマンスチェックを行いません。コンフォーマンスチェックは基になるオブジェクトに任されています。 |
| Fragment | 1 | XML データは W3C によって定義された [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) です。このコンフォーマンスレベルは、ルート要素が存在しない可能性があるが、それ以外は正しく形成された XML ドキュメントを表します。このレベルのチェックにより、読み取りまたは書き込み対象のストリームが任意のプロセッサによって [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) として使用できることが保証されます。 |
| Document | 2 | XML データは W3C によって定義された正しく形成された [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) のルールに準拠しています。このレベルのチェックにより、読み取りまたは書き込み対象のストリームが任意のプロセッサによって [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) として使用できることが保証されます。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)