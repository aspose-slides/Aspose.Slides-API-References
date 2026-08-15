---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個新的 XmlDocumentType 物件。
type: docs
weight: 313
url: /zh-hant/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method

返回一個新的 [XmlDocumentType](../../xmldocumenttype/) 物件。

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 文件類型的名稱。 |
| publicId | const [String](../../../system/string/)\& | 文件類型的公開識別碼或 **nullptr**。您可以指定公開的 URI，亦可提供系統識別碼以指明外部 DTD 子集的位置。 |
| systemId | const [String](../../../system/string/)\& | 文件類型的系統識別碼或 **nullptr**。指定外部 DTD 子集檔案位置的 URL。 |
| internalSubset | const [String](../../../system/string/)\& | 文件類型的 DTD 內部子集或 **nullptr**。 |

### 傳回值

新的 [XmlDocumentType](../../xmldocumenttype/)。

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)