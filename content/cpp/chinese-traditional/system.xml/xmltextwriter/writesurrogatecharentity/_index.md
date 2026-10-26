---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API 參考
description: 產生並寫入代理字元對的代理字元實體。
type: docs
weight: 391
url: /zh-hant/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) 方法

產生並寫入代理字元對的代理字元實體。

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lowChar | char16_t | 低位代理字元。該值必須介於 **0xDC00** 與 **0xDFFF** 之間。 |
| highChar | char16_t | 高位代理字元。該值必須介於 **0xD800** 與 **0xDBFF** 之間。 |

## 另請參閱

* 類別 [XmlTextWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)