---
title: WriteProcessingInstruction()
second_title: Referência da API Aspose.Slides para C++
description: "Escreve uma instrução de processamento com um espaço entre o nome e o texto da seguinte forma: <?name text?>."
type: docs
weight: 326
url: /pt/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) method


Escreve uma instrução de processamento com um espaço entre o nome e o texto da seguinte forma: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da instrução de processamento. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) para incluir na instrução de processamento. |
## Observações



Este método está sendo usado para criar uma declaração XML após [XmlTextWriter::WriteStartDocument](../writestartdocument/) já ter sido chamado. 
## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)