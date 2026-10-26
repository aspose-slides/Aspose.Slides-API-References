---
title: ReadContentAs()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 將內容讀取為指定類型的物件。
type: docs
weight: 456
url: /zh-hant/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

將內容讀取為指定型別的物件。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要返回之值的型別。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 用於解析與型別轉換相關之任何命名空間前綴的 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 物件。例如，在將 [XmlQualifiedName](../../xmlqualifiedname/) 物件轉換為 **xs:string** 時可使用此物件。此值可為 **nullptr**。 |

### 傳回值

已串接的文字內容或屬性值，轉換為請求的型別。

## 相關參考

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)