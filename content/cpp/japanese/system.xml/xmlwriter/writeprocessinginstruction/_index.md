---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API リファレンス
description: "派生クラスでオーバーライドされた場合、名前とテキストの間にスペースを入れた処理指示を次のように書き出します: <?name text?>."
type: docs
weight: 196
url: /ja/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) メソッド


When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 処理指示の名前です。 |
| text | [String](../../../system/string/) | 処理指示に含めるテキストです。 |
## 備考



This method is being used to create an XML declaration after [XmlWriter::WriteStartDocument](../writestartdocument/) has already been called. 
## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)