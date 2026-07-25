---
title: get_XmlSpace()
second_title: Aspose.Slides for C++ API リファレンス
description: "派生クラスでオーバーライドされた場合、現在の xml:space スコープを表す XmlSpace を取得します。"
type: docs
weight: 27
url: /ja/system.xml/xmlwriter/get_xmlspace/
---
## XmlWriter::get_XmlSpace() メソッド


派生クラスでオーバーライドされた場合、現在の **xml:space** スコープを表す XmlSpace を取得します。

```cpp
virtual System::Xml::XmlSpace System::Xml::XmlWriter::get_XmlSpace()
```


### 戻り値

現在の **xml:space** スコープを表す XmlSpace。


| 値 | 意味 |
| --- | --- |
| `None`| `xml:space` スコープが存在しない場合のデフォルトです。 |
| `Default`| 現在のスコープは `xml:space="default"` です。 |
| `Preserve`| 現在のスコープは `xml:space="preserve"` です。 |


## 参照

* 列挙体 [XmlSpace](../../xmlspace/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)