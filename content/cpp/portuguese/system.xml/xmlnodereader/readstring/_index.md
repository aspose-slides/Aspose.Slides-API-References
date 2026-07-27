---
title: ReadString()
second_title: Aspose.Slides para C++ Referência da API
description: Lê o conteúdo de um elemento ou nó de texto como uma string.
type: docs
weight: 391
url: /pt/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() method


Lê o conteúdo de um elemento ou nó de texto como uma string.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### Valor de Retorno

O conteúdo do elemento ou nó semelhante a texto (isso pode incluir nós CDATA, [Text](../../../system.text/) e assim por diante). Pode ser uma string vazia se o leitor estiver posicionado em algo que não seja um elemento ou nó de texto, ou se não houver mais conteúdo de texto para retornar no contexto atual. Observação: O nó de texto pode ser um nó de elemento ou um nó de texto de atributo.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)