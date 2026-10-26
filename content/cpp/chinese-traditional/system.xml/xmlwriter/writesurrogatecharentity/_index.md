---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides C++ API 參考
description: 當在衍生類別中覆寫時，會產生並寫入代理字元對的代理字元實體。
type: docs
weight: 261
url: /zh-hant/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) 方法


當在衍生類別中覆寫時，會產生並寫入代理字元對的代理字元實體。

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lowChar | char16_t | 低位代理項。其值必須介於 0xDC00 與 0xDFFF 之間。 |
| highChar | char16_t | 高位代理項。其值必須介於 0xD800 與 0xDBFF 之間。 |

## 參見

* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)