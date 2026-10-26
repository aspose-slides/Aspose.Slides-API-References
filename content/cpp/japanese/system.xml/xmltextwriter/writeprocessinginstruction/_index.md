---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API リファレンス
description: "名前とテキストの間にスペースを入れた処理指示を次のように出力します: <?name text?>。"
type: docs
weight: 326
url: /ja/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) メソッド

名前とテキストの間にスペースを入れた処理指示を次のように出力します: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 処理指示の名前。 |
| text | [String](../../../system/string/) | [Text](../../../system.text/) を処理指示に含める。 |
## 備考

このメソッドは、[XmlTextWriter::WriteStartDocument](../writestartdocument/) がすでに呼び出された後に XML 宣言を作成するために使用されます。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)