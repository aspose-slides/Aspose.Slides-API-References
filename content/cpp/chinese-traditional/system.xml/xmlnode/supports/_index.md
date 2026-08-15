---
title: Supports()
second_title: Aspose.Slides for C++ API 參考文件
description: 測試 DOM 實作是否實作特定功能。
type: docs
weight: 482
url: /zh-hant/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) 方法


測試 DOM 實作是否實作特定功能。

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| feature | [String](../../../system/string/) | 要測試的功能之套件名稱。此名稱不區分大小寫。 |
| version | [String](../../../system/string/) | 要測試的套件名稱之版本號碼。如果未指定版本（null），支援該功能的任何版本會使方法回傳 true。 |

### 傳回值

**true** 如果在指定版本中實作了該功能，則回傳 **true**；否則回傳 **false**。
## 備註



下表描述會回傳 **true** 的組合。 

| 功能 | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNode](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)