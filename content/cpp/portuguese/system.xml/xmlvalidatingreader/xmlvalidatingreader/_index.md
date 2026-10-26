---
title: XmlValidatingReader()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe XmlValidatingReader que valida o conteúdo retornado do XmlReader fornecido.
type: docs
weight: 430
url: /pt/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) construtor


Inicializa uma nova instância da classe [XmlValidatingReader](../) que valida o conteúdo retornado do [XmlReader](../../xmlreader/) fornecido.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | O [XmlReader](../../xmlreader/) a ser lido durante a validação. A implementação atual suporta apenas [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) construtor


Inicializa uma nova instância da classe [XmlValidatingReader](../) com os valores especificados.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | A string contendo o fragmento XML a ser analisado. |
| fragType | [XmlNodeType](../../xmlnodetype/) | O XmlNodeType do fragmento XML. Isso também determina o que a string do fragmento pode conter (veja a tabela abaixo). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | O [XmlParserContext](../../xmlparsercontext/) no qual o fragmento XML será analisado. Isso inclui o [NameTable](../../nametable/) a ser usado, codificação, escopo de namespace, **xml:lang** atual e escopo **xml:space**. |

## Observações



A tabela a seguir lista os valores válidos para **fragType** e como o leitor analisa cada um dos diferentes tipos de nó. 

| XmlNodeType | Fragmentos podem conter |
| --- | --- |
| Element| Qualquer conteúdo de elemento válido (por exemplo, qualquer combinação de elementos, comentários, instruções de processamento, cdata, texto e referências de entidade). |
| [Attribute](../../../system/attribute/)| O valor de um atributo (a parte entre aspas). |
| Document| O conteúdo de um documento XML completo; isso impõe regras de nível de documento. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) construtor


Inicializa uma nova instância da classe [XmlValidatingReader](../) com os valores especificados.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo contendo o fragmento XML a ser analisado. |
| fragType | [XmlNodeType](../../xmlnodetype/) | O XmlNodeType do fragmento XML. Isso determina o que o fragmento pode conter (veja a tabela abaixo). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | O [XmlParserContext](../../xmlparsercontext/) no qual o fragmento XML será analisado. Isso inclui o [XmlNameTable](../../xmlnametable/) a ser usado, codificação, escopo de namespace, **xml:lang** atual e escopo **xml:space**. |

## Observações



A tabela a seguir lista os valores válidos para **fragType** e como o leitor analisa cada um dos diferentes tipos de nó. 

| XmlNodeType | Fragmentos podem conter |
| --- | --- |
| Element| Qualquer conteúdo de elemento válido (por exemplo, qualquer combinação de elementos, comentários, instruções de processamento, cdata, texto e referências de entidade). |
| [Attribute](../../../system/attribute/)| O valor de um atributo (a parte entre aspas). |
| Document| O conteúdo de um documento XML completo; isso impõe regras de nível de documento. |


## Veja Também

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlValidatingReader](../)
* Classe [String](../../../system/string/)
* Classe [XmlParserContext](../../xmlparsercontext/)
* Classe [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)