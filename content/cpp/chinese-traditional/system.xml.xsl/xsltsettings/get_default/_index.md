---
title: get_Default()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 傳回具有預設設定的 XsltSettings 物件。已停用對 XSLT document() 函式以及嵌入式腳本區塊的支援。
type: docs
weight: 1
url: /zh-hant/system.xml.xsl/xsltsettings/get_default/
---
## XsltSettings::get_Default() 方法

返回一個 [XsltSettings](../) 物件，使用預設設定。對 XSLT **document()** 函式和嵌入式腳本區塊的支援已停用。

```cpp
static SharedPtr<XsltSettings> System::Xml::Xsl::XsltSettings::get_Default()
```

### 返回值

一個 [XsltSettings](../) 物件，其 [XsltSettings::set_EnableDocumentFunction](../set_enabledocumentfunction/) 與 [XsltSettings::set_EnableScript](../set_enablescript/) 選項設定為 **false**。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltSettings](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)