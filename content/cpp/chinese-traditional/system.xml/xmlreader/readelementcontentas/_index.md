---
title: ReadElementContentAs()
second_title: Aspose.Slides for C++ API 參考文件
description: 將元素內容讀取為指定的類型。
type: docs
weight: 586
url: /zh-hant/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

將元素內容讀取為指定的類型。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要返回之值的類型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 用於解析與類型轉換相關的任何命名空間前綴的 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 物件。 |

### 返回值

將元素內容轉換為請求的類型物件。

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) 方法

檢查指定的本地名稱與命名空間 URI 是否與目前元素相符，然後將元素內容讀取為指定的類型。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要返回之值的類型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 用於解析與類型轉換相關的任何命名空間前綴的 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 物件。 |
| localName | [String](../../../system/string/) | 元素的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空間 URI。 |

### 返回值

將元素內容轉換為請求的類型物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* 類別 [XmlReader](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)