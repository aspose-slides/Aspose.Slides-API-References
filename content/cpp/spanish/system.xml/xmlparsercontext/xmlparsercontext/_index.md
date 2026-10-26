---
title: XmlParserContext()
second_title: Referencia de API de Aspose.Slides para C++
description: "Inicializa una nueva instancia de la clase XmlParserContext con los XmlNameTable, XmlNamespaceManager, xml:lang y xml:space especificados."
type: docs
weight: 261
url: /es/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, y **xml:space** especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacio de nombres, o **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | El ámbito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valor XmlSpace que indica el ámbito **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, y la codificación especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacio de nombres, o **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | El ámbito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valor XmlSpace que indica el ámbito **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Un objeto Encoding que indica la configuración de codificación. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space**, y los valores del tipo de documento especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacio de nombres, o **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | El nombre de la declaración del tipo de documento. |
| pubId | const [String](../../../system/string/)\& | El identificador público. |
| sysId | const [String](../../../system/string/)\& | El identificador del sistema. |
| internalSubset | const [String](../../../system/string/)\& | El subconjunto DTD interno. El subconjunto DTD se usa para la resolución de entidades, no para la validación del documento. |
| baseURI | const [String](../../../system/string/)\& | El URI base para el fragmento XML (la ubicación desde la que se cargó el fragmento). |
| xmlLang | const [String](../../../system/string/)\& | El ámbito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valor XmlSpace que indica el ámbito **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space**, codificación y valores del tipo de documento especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacio de nombres, o **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | El nombre de la declaración del tipo de documento. |
| pubId | const [String](../../../system/string/)\& | El identificador público. |
| sysId | const [String](../../../system/string/)\& | El identificador del sistema. |
| internalSubset | const [String](../../../system/string/)\& | El subconjunto DTD interno. El DTD se usa para la resolución de entidades, no para la validación del documento. |
| baseURI | const [String](../../../system/string/)\& | El URI base para el fragmento XML (la ubicación desde la que se cargó el fragmento). |
| xmlLang | const [String](../../../system/string/)\& | El ámbito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valor XmlSpace que indica el ámbito **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Un objeto Encoding que indica la configuración de codificación. |

## Ver también

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNameTable](../../xmlnametable/)
* Clase [XmlNamespaceManager](../../xmlnamespacemanager/)
* Clase [String](../../../system/string/)
* Clase [XmlParserContext](../)
* Clase [Encoding](../../../system.text/encoding/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)