---
title: ValidateElement()
second_title: Aspose.Slides C++ API Referansı
description: Geçerli bağlamdaki öğeyi doğrular.
type: docs
weight: 131
url: /tr/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\-) yöntemi

Geçerli bağlamdaki öğeyi doğrular.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Doğrulanacak öğenin yerel adı. |
| namespaceUri | const [String](../../../system/string/)\& | Doğrulanacak öğenin ad alanı URI'si. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) nesnesi, öğenin adının başarılı doğrulanması üzerine özellikleri ayarlanır. Bu parametre **nullptr** olabilir. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\-) yöntemi

Geçerli bağlamdaki öğeyi, belirtilen **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** ve **xsi:NoNamespaceSchemaLocation** öznitelik değerleriyle doğrular.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Doğrulanacak öğenin yerel adı. |
| namespaceUri | const [String](../../../system/string/)\& | Doğrulanacak öğenin ad alanı URI'si. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) nesnesi, öğenin adının başarılı doğrulanması üzerine özellikleri ayarlanır. Bu parametre **nullptr** olabilir. |
| xsiType | const [String](../../../system/string/)\& | Öğenin **xsi:Type** öznitelik değeri. Bu parametre **nullptr** olabilir. |
| xsiNil | const [String](../../../system/string/)\& | Öğenin **xsi:Nil** öznitelik değeri. Bu parametre **nullptr** olabilir. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Öğenin **xsi:SchemaLocation** öznitelik değeri. Bu parametre **nullptr** olabilir. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Öğenin **xsi:NoNamespaceSchemaLocation** öznitelik değeri. Bu parametre **nullptr** olabilir. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSchemaInfo](../../xmlschemainfo/)
* Sınıf [XmlSchemaValidator](../)
* İsim Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)