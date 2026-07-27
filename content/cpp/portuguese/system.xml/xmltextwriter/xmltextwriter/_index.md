---
title: XmlTextWriter()
second_title: Referência da API do Aspose.Slides para C++
description: Cria uma instância da classe XmlTextWriter usando o fluxo especificado e a codificação.
type: docs
weight: 183
url: /pt/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) construtor


Cria uma instância da classe [XmlTextWriter](../) usando o stream especificado e a codificação.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O stream para o qual deseja gravar. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A codificação a ser gerada. Se a codificação for **nullptr** ele grava o stream como UTF-8 e omite o atributo de codificação do **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) construtor


Cria uma instância da classe [XmlTextWriter](../) usando o arquivo especificado.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | O nome do arquivo para gravar. Se o arquivo existir, ele o trunca e o sobrescreve com o novo conteúdo. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A codificação a ser gerada. Se a codificação for **nullptr** ele grava o arquivo como UTF-8 e omite o atributo de codificação do **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) construtor


Cria uma instância da classe [XmlTextWriter](../) usando o TextWriter especificado.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para gravar. Presume-se que o TextWriter já esteja configurado com a codificação correta. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Encoding](../../../system.text/encoding/)
* Classe [XmlTextWriter](../)
* Classe [String](../../../system/string/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)