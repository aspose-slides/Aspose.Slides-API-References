---
title: ReadToFollowing()
second_title: Referência da API Aspose.Slides para C++
description: Lê até que um elemento com o nome qualificado especificado seja encontrado.
type: docs
weight: 898
url: /pt/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) método

Lê até que um elemento com o nome qualificado especificado seja encontrado.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do elemento. |

### Valor de Retorno

**true** se um elemento correspondente for encontrado; caso contrário **false** e o [XmlReader](../) está em estado de fim de arquivo.

## XmlReader::ReadToFollowing(String, String) método

Lê até que um elemento com o nome local e o URI do namespace especificados seja encontrado.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do elemento. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do elemento. |

### Valor de Retorno

**true** se um elemento correspondente for encontrado; caso contrário **false** e o [XmlReader](../) está em estado de fim de arquivo.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)