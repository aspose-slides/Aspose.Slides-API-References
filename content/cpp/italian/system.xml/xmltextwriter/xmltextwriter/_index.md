---
title: XmlTextWriter()
second_title: Aspose.Slides per C++ API Reference
description: Crea un'istanza della classe XmlTextWriter utilizzando lo stream e la codifica specificati.
type: docs
weight: 183
url: /it/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) costruttore


Crea un'istanza della classe [XmlTextWriter](../) utilizzando lo stream e la codifica specificati.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream su cui desideri scrivere. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codifica da generare. Se la codifica è **nullptr** scrive lo stream come UTF-8 e omette l'attributo di codifica dal **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) costruttore


Crea un'istanza della classe [XmlTextWriter](../) utilizzando il file specificato.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file su cui scrivere. Se il file esiste, lo tronca e lo sovrascrive con il nuovo contenuto. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codifica da generare. Se la codifica è **nullptr** scrive il file come UTF-8 e omette l'attributo di codifica dal **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) costruttore


Crea un'istanza della classe [XmlTextWriter](../) utilizzando il TextWriter specificato.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter su cui scrivere. Si presume che il TextWriter sia già impostato sulla codifica corretta. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Encoding](../../../system.text/encoding/)
* Classe [XmlTextWriter](../)
* Classe [String](../../../system/string/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)