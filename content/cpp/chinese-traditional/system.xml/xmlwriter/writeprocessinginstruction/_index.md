---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API 參考文件
description: "當在衍生類別中被覆寫時，會寫出具有名稱與文字之間空格的處理指令，如下所示：<?name text?>。"
type: docs
weight: 196
url: /zh-hant/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) 方法


當在衍生類別中被覆寫時，會寫出具有名稱與文字之間空格的處理指令，如下所示：**<?name text?>**。

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 處理指令的名稱。 |
| text | [String](../../../system/string/) | 要包含在處理指令中的文字。 |
## 備註



此方法於 [XmlWriter::WriteStartDocument](../writestartdocument/) 已被呼叫後，用於建立 XML 宣告。 
## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)