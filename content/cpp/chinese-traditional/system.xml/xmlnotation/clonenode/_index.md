---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立此節點的副本。標記節點無法被克隆。對 XmlNotation 物件呼叫此方法會拋出例外。
type: docs
weight: 118
url: /zh-hant/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) 方法

建立此節點的副本。標記節點無法被克隆。對 [XmlNotation](../) 物件呼叫此方法會拋出例外。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true** 表示遞迴地克隆指定節點下的子樹；**false** 表示僅克隆節點本身。 |

### 返回值

由呼叫此方法的節點所產生的 [XmlNode](../../xmlnode/) 複本。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNotation](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)