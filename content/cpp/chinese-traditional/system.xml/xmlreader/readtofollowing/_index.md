---
title: ReadToFollowing()
second_title: Aspose.Slides for C++ API 參考
description: 讀取直到找到具有指定限定名稱的元素。
type: docs
weight: 898
url: /zh-hant/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) 方法

讀取直到找到具有指定限定名稱的元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 元素的限定名稱。 |

### 返回值

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## XmlReader::ReadToFollowing(String, String) 方法

讀取直到找到具有指定本機名稱和命名空間 URI 的元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空間 URI。 |

### 返回值

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 名稱空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)