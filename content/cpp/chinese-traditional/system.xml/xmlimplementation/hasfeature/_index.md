---
title: HasFeature()
second_title: Aspose.Slides for C++ API 參考文件
description: 測試文件物件模型 (DOM) 實作是否實作特定功能。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) 方法

測試文件 [Object](../../../system/object/) 模型 (DOM) 實作是否實作特定功能。

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | 要測試的功能之套件名稱。此名稱不區分大小寫。 |
| strVersion | const [String](../../../system/string/)\& | 要測試的套件名稱的版本號碼。如果未指定版本 (**nullptr**)，支援該功能的任何版本都會使方法回傳 **true**。 |

### 返回值

**true** 表示在指定版本中已實作該功能；否則為 **false**。

## 備註

以下表格顯示導致 **HasFeature** 回傳 **true** 的組合。

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlImplementation](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)