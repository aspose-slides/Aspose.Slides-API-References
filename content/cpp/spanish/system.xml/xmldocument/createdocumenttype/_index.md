---
title: CreateDocumentType()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un nuevo objeto XmlDocumentType.
type: docs
weight: 313
url: /es/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) método

Devuelve un nuevo [XmlDocumentType](../../xmldocumenttype/) objeto.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nombre del tipo de documento. |
| publicId | const [String](../../../system/string/)\& | El identificador público del tipo de documento o **nullptr**. Puede especificar un URI público y también un identificador de sistema para identificar la ubicación del subconjunto DTD externo. |
| systemId | const [String](../../../system/string/)\& | El identificador de sistema del tipo de documento o **nullptr**. Especifica la URL de la ubicación del archivo para el subconjunto DTD externo. |
| internalSubset | const [String](../../../system/string/)\& | El subconjunto interno DTD del tipo de documento o **nullptr**. |

### Valor de retorno

El nuevo [XmlDocumentType](../../xmldocumenttype/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlDocumentType](../../xmldocumenttype/)
* Clase [String](../../../system/string/)
* Clase [XmlDocument](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)