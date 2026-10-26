---
title: WriteDocType()
second_title: Aspose.Slides C++ API 參考
description: 在衍生類別中覆寫時，寫入具有指定名稱和可選屬性的 DOCTYPE 宣告。
type: docs
weight: 79
url: /zh-hant/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) method


在衍生類別中覆寫時，寫入具有指定名稱和可選屬性的 DOCTYPE 宣告。

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE 的名稱。此名稱不得為空。 |
| pubid | const [String](../../../system/string/)\& | 如果非 null，則也寫入 PUBLIC \"pubid\" \"sysid\"，其中 **pubid** 和 **sysid** 會被給定參數的值取代。 |
| sysid | const [String](../../../system/string/)\& | 如果 **pubid** 為 **nullptr** 且 **sysid** 為非 null，則寫入 SYSTEM \"sysid\"，其中 **sysid** 會被此參數的值取代。 |
| subset | const [String](../../../system/string/)\& | 如果非 null，則寫入 [subset]，其中 subset 會被此參數的值取代。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)