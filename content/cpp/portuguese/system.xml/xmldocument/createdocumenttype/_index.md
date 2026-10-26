---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ Referência da API
description: Retorna um novo objeto XmlDocumentType.
type: docs
weight: 313
url: /pt/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) método

Retorna um novo [XmlDocumentType](../../xmldocumenttype/) objeto.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome do tipo de documento. |
| publicId | const [String](../../../system/string/)\& | O identificador público do tipo de documento ou **nullptr**. Você pode especificar um URI público e também um identificador de sistema para identificar o local do subconjunto DTD externo. |
| systemId | const [String](../../../system/string/)\& | O identificador de sistema do tipo de documento ou **nullptr**. Especifica a URL do local do arquivo para o subconjunto DTD externo. |
| internalSubset | const [String](../../../system/string/)\& | O subconjunto interno DTD do tipo de documento ou **nullptr**. |

### Valor de Retorno

O novo [XmlDocumentType](../../xmldocumenttype/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlDocumentType](../../xmldocumenttype/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)