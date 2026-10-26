---
title: get_BaseStream()
second_title: Aspose.Slides for C++ API 參考
description: 傳回底層的串流物件。
type: docs
weight: 1
url: /zh-hant/system.xml/xmltextwriter/get_basestream/
---
## XmlTextWriter::get_BaseStream() 方法


返回底層的串流物件。

```cpp
SharedPtr<IO::Stream> System::Xml::XmlTextWriter::get_BaseStream()
```


### 返回值

此串流是 [XmlTextWriter](../) 正在寫入的目標；如果 [XmlTextWriter](../) 是使用未繼承自 StreamWriter 類別的 TextWriter 建構，則為 **nullptr**。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [XmlTextWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)