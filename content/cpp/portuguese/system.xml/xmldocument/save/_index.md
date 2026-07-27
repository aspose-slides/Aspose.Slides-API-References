---
title: Save()
second_title: Referência da API Aspose.Slides para C++
description: Salva o documento XML no arquivo especificado. Se o arquivo especificado existir, este método o sobrescreve.
type: docs
weight: 534
url: /pt/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) método


Salva o documento XML no arquivo especificado. Se o arquivo especificado existir, este método o sobrescreve.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | [String](../../../system/string/) | O local do arquivo onde você deseja salvar o documento. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) método


Salva o documento XML no stream especificado.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O stream para o qual você deseja salvar. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) método


Salva o documento XML no TextWriter especificado.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | O TextWriter para o qual você deseja salvar. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) método


Salva o documento XML no [XmlWriter](../../xmlwriter/) especificado.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | O [XmlWriter](../../xmlwriter/) para o qual você deseja salvar. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)