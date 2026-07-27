---
title: WriteProcessingInstruction()
second_title: Referência da API Aspose.Slides para C++
description: "Quando sobrescrito em uma classe derivada, grava uma instrução de processamento com um espaço entre o nome e o texto da seguinte forma: <?name text?>."
type: docs
weight: 196
url: /pt/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) método


Quando sobrescrito em uma classe derivada, grava uma instrução de processamento com um espaço entre o nome e o texto da seguinte forma: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome da instrução de processamento. |
| text | [String](../../../system/string/) | O texto a ser incluído na instrução de processamento. |
## Observações



Este método está sendo usado para criar uma declaração XML após [XmlWriter::WriteStartDocument](../writestartdocument/) já ter sido chamado. 
## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)