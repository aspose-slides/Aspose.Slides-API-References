---
title: XmlOutputMethod
second_title: C++ 用 Aspose.Slides API リファレンス
description: XmlWriter の出力をシリアライズするために使用される方法を指定します。
type: docs
weight: 846
url: /ja/system.xml/xmloutputmethod/
---
## XmlOutputMethod 列挙型

[XmlWriter](../xmlwriter/) の出力をシリアライズするために使用される方法を指定します。

```cpp
enum class XmlOutputMethod
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Xml | 0 | XML 1.0 の規則に従ってシリアライズします。 |
| Html | 1 | XSLT が指定する HTML の規則に従ってシリアライズします。 |
| Text | 2 | テキストブロックのみをシリアライズします。 |
| AutoDetect | 3 | [XmlOutputMethod::Xml](./) と [XmlOutputMethod::Html](./) の出力方法の間で、実行時に XSLT の規則を使用して選択します。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)