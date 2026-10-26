---
title: ReadSubtree()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個新的 XmlReader 實例，可用於讀取目前節點及其所有子節點。
type: docs
weight: 963
url: /zh-hant/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() 方法


傳回一個新的 [XmlReader](../) 實例，可用於讀取目前節點以及其所有子節點。

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### 返回值

傳回一個設定為 [ReadState::Initial](../../readstate/) 的新 XML 讀取器實例。呼叫 [XmlReader::Read](../read/) 方法會將新讀取器定位在呼叫 [XmlReader::ReadSubtree](./) 方法之前的當前節點。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)