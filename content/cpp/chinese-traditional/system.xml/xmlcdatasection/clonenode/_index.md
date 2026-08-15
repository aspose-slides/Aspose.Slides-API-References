---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立此節點的副本。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) method


建立此節點的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式克隆指定節點下的子樹；**false** 僅克隆節點本身。因為 CDATA 節點沒有子節點，無論參數設定為何，克隆後的節點都會包含資料內容。 |

### 回傳值

克隆後的節點。

## 另請參考

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlCDataSection](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)