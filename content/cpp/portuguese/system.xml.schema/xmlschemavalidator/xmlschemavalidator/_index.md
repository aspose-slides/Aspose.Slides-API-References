---
title: XmlSchemaValidator()
second_title: Aspose.Slides para C++ Referência da API
description: Inicializa uma nova instância da classe XmlSchemaValidator.
type: docs
weight: 92
url: /pt/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor

Inicializa uma nova instância da classe [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Um objeto [XmlNameTable](../../../system.xml/xmlnametable/) que contém nomes de elementos e atributos como strings atomizadas. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Um objeto [XmlSchemaSet](../../xmlschemaset/) que contém os esquemas XML [Schema](../../) Definition Language (XSD) usados para validação. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Um objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver namespaces encontrados durante a validação. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Um valor XmlSchemaValidationFlags que especifica as opções de validação de esquema. |

## Veja Também

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../../system.xml/xmlnametable/)
* Classe [XmlSchemaSet](../../xmlschemaset/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)