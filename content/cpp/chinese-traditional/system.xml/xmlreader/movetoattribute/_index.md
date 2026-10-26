---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: "當在衍生類別中被覆寫時，會移動到具有指定 XmlReader::get_Name 值的屬性。"
type: docs
weight: 625
url: /zh-hant/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) 方法

在衍生類別中覆寫時，將移動到具有指定 [XmlReader::get_Name](../get_name/) 值的屬性。

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 返回值

**true** 若找到屬性；否則為 **false**。如果 **false**，讀取器的位置不會改變。

## XmlReader::MoveToAttribute(String, String) 方法

在衍生類別中覆寫時，將移動到具有指定 [XmlReader::get_LocalName](../get_localname/) 與 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的屬性。

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的本機名稱。 |
| ns | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 返回值

**true** 若找到屬性；否則為 **false**。如果 **false**，讀取器的位置不會改變。

## XmlReader::MoveToAttribute(int32_t) 方法

在衍生類別中覆寫時，將移動到具有指定索引的屬性。

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)