---
title: WriteDocType()
second_title: Aspose.Slides for C++ API 參考
description: 寫入具有指定名稱和可選屬性的 DOCTYPE 宣告。
type: docs
weight: 222
url: /zh-hant/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) 方法

寫入具有指定名稱和可選屬性的 DOCTYPE 聲明。

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE 的名稱。此名稱不得為空。 |
| pubid | const [String](../../../system/string/)\& | 若非 null，還會寫入 PUBLIC \"pubid\" \"sysid\"，其中 **pubid** 和 **sysid** 會被給定參數的值取代。 |
| sysid | const [String](../../../system/string/)\& | 若 **pubid** 為 null 且 **sysid** 為非 null，則寫入 SYSTEM \"sysid\"，其中 **sysid** 會被此參數的值取代。 |
| subset | const [String](../../../system/string/)\& | 若非 null，寫入 [subset]，其中 subset 會被此參數的值取代。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlTextWriter](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)