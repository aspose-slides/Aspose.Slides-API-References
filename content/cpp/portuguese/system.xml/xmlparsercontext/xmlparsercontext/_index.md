---
title: XmlParserContext()
second_title: Referência da API Aspose.Slides para C++
description: "Inicializa uma nova instância da classe XmlParserContext com os valores especificados de XmlNameTable, XmlNamespaceManager, xml:lang e xml:space."
type: docs
weight: 261
url: /pt/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

Inicializa uma nova instância da classe [XmlParserContext](../) com os [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** e **xml:space** especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado para atomizar strings. Se for **nullptr**, a tabela de nomes usada para construir o **nsMgr** será usada em seu lugar. Para mais informações sobre strings atomizadas, veja [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | O [XmlNamespaceManager](../../xmlnamespacemanager/) a ser usado para procurar informações de namespace, ou **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | O escopo **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Um valor XmlSpace que indica o escopo **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Inicializa uma nova instância da classe [XmlParserContext](../) com os [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** e a codificação especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado para atomizar strings. Se for **nullptr**, a tabela de nomes usada para construir o **nsMgr** será usada em seu lugar. Para mais informações sobre strings atomizadas, veja [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | O [XmlNamespaceManager](../../xmlnamespacemanager/) a ser usado para procurar informações de namespace, ou **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | O escopo **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Um valor XmlSpace que indica o escopo **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Um objeto Encoding que indica a configuração de codificação. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

Inicializa uma nova instância da classe [XmlParserContext](../) com os [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space** e os valores de tipo de documento especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado para atomizar strings. Se for **nullptr**, a tabela de nomes usada para construir o **nsMgr** será usada em seu lugar. Para mais informações sobre strings atomizadas, veja [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | O [XmlNamespaceManager](../../xmlnamespacemanager/) a ser usado para procurar informações de namespace, ou **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | O nome da declaração de tipo de documento. |
| pubId | const [String](../../../system/string/)\& | O identificador público. |
| sysId | const [String](../../../system/string/)\& | O identificador de sistema. |
| internalSubset | const [String](../../../system/string/)\& | O subconjunto interno DTD. O subconjunto DTD é usado para resolução de entidades, não para validação de documento. |
| baseURI | const [String](../../../system/string/)\& | O URI base para o fragmento XML (o local de onde o fragmento foi carregado). |
| xmlLang | const [String](../../../system/string/)\& | O escopo **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Um valor XmlSpace que indica o escopo **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Inicializa uma nova instância da classe [XmlParserContext](../) com os [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space**, codificação e valores de tipo de documento especificados.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado para atomizar strings. Se for **nullptr**, a tabela de nomes usada para construir o **nsMgr** será usada em seu lugar. Para mais informações sobre strings atomizadas, veja [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | O [XmlNamespaceManager](../../xmlnamespacemanager/) a ser usado para procurar informações de namespace, ou **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | O nome da declaração de tipo de documento. |
| pubId | const [String](../../../system/string/)\& | O identificador público. |
| sysId | const [String](../../../system/string/)\& | O identificador de sistema. |
| internalSubset | const [String](../../../system/string/)\& | O subconjunto interno DTD. O DTD é usado para resolução de entidades, não para validação de documento. |
| baseURI | const [String](../../../system/string/)\& | O URI base para o fragmento XML (o local de onde o fragmento foi carregado). |
| xmlLang | const [String](../../../system/string/)\& | O escopo **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Um valor XmlSpace que indica o escopo **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Um objeto Encoding que indica a configuração de codificação. |

## Veja Também

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../xmlnametable/)
* Classe [XmlNamespaceManager](../../xmlnamespacemanager/)
* Classe [String](../../../system/string/)
* Classe [XmlParserContext](../)
* Classe [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)