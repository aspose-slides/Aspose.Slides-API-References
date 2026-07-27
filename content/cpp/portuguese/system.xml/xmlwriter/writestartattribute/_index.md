---
title: WriteStartAttribute()
second_title: Aspose.Slides para Referência da API C++
description: Escreve o início de um atributo com o nome local e o URI do namespace especificados.
type: docs
weight: 144
url: /pt/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) método


Escreve o início de um atributo com o nome local e o URI do namespace especificados.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| ns | const [String](../../../system/string/)\& | O URI do namespace do atributo. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) método


Quando sobrescrito em uma classe derivada, escreve o início de um atributo com o prefixo, nome local e URI do namespace especificados.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo do namespace do atributo. |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| ns | const [String](../../../system/string/)\& | O URI do namespace do atributo. |

## XmlWriter::WriteStartAttribute(const String\&) método


Escreve o início de um atributo com o nome local especificado.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)