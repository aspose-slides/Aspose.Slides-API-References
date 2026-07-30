---
title: Create()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza di XmlWriter utilizzando il nome file specificato.
type: docs
weight: 469
url: /it/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando il nome file specificato.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Il file su cui vuoi scrivere. Il [XmlWriter](../) crea un file nel percorso specificato e vi scrive in sintassi testo XML 1.0. Il **outputFileName** deve essere un percorso del file system. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando il nome file e l'oggetto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Il file su cui vuoi scrivere. Il [XmlWriter](../) crea un file nel percorso specificato e vi scrive in sintassi testo XML 1.0. Il **outputFileName** deve essere un percorso del file system. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L'oggetto [XmlWriterSettings](../../xmlwritersettings/) usato per configurare la nuova istanza [XmlWriter](../). Se è **nullptr**, viene usato un [XmlWriterSettings](../../xmlwritersettings/) con impostazioni predefinite. Se il [XmlWriter](../) è utilizzato con il metodo XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , dovresti usare il valore XslCompiledTransform::get_OutputSettings per ottenere un oggetto [XmlWriterSettings](../../xmlwritersettings/) con le impostazioni corrette. Questo garantisce che l'oggetto [XmlWriter](../) creato abbia le impostazioni di output corrette. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando lo stream specificato.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream su cui vuoi scrivere. Il [XmlWriter](../) scrive in sintassi testo XML 1.0 e lo aggiunge allo stream specificato. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando lo stream e l'oggetto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream su cui vuoi scrivere. Il [XmlWriter](../) scrive in sintassi testo XML 1.0 e lo aggiunge allo stream specificato. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L'oggetto [XmlWriterSettings](../../xmlwritersettings/) usato per configurare la nuova istanza [XmlWriter](../). Se è **nullptr**, viene usato un [XmlWriterSettings](../../xmlwritersettings/) con impostazioni predefinite. Se il [XmlWriter](../) è utilizzato con il metodo XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , dovresti usare il valore XslCompiledTransform::get_OutputSettings per ottenere un oggetto [XmlWriterSettings](../../xmlwritersettings/) con le impostazioni corrette. Questo garantisce che l'oggetto [XmlWriter](../) creato abbia le impostazioni di output corrette. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando il TextWriter specificato.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter su cui vuoi scrivere. Il [XmlWriter](../) scrive in sintassi testo XML 1.0 e lo aggiunge al TextWriter specificato. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando il TextWriter e gli oggetti [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter su cui vuoi scrivere. Il [XmlWriter](../) scrive in sintassi testo XML 1.0 e lo aggiunge al TextWriter specificato. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L'oggetto [XmlWriterSettings](../../xmlwritersettings/) usato per configurare la nuova istanza [XmlWriter](../). Se è **nullptr**, viene usato un [XmlWriterSettings](../../xmlwritersettings/) con impostazioni predefinite. Se il [XmlWriter](../) è utilizzato con il metodo XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , dovresti usare il valore XslCompiledTransform::get_OutputSettings per ottenere un oggetto [XmlWriterSettings](../../xmlwritersettings/) con le impostazioni corrette. Questo garantisce che l'oggetto [XmlWriter](../) creato abbia le impostazioni di output corrette. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando il [Text::StringBuilder](../../../system.text/stringbuilder/) specificato.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Il [Text::StringBuilder](../../../system.text/stringbuilder/) su cui scrivere. Il contenuto scritto dal [XmlWriter](../) viene aggiunto al [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando gli oggetti [Text::StringBuilder](../../../system.text/stringbuilder/) e [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Il [Text::StringBuilder](../../../system.text/stringbuilder/) su cui scrivere. Il contenuto scritto dal [XmlWriter](../) viene aggiunto al [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L'oggetto [XmlWriterSettings](../../xmlwritersettings/) usato per configurare la nuova istanza [XmlWriter](../). Se è **nullptr**, viene usato un [XmlWriterSettings](../../xmlwritersettings/) con impostazioni predefinite. Se il [XmlWriter](../) è utilizzato con il metodo XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , dovresti usare il valore XslCompiledTransform::get_OutputSettings per ottenere un oggetto [XmlWriterSettings](../../xmlwritersettings/) con le impostazioni corrette. Questo garantisce che l'oggetto [XmlWriter](../) creato abbia le impostazioni di output corrette. |

### Valore di ritorno

Un oggetto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando l'oggetto [XmlWriter](../) specificato.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | L'oggetto [XmlWriter](../) che vuoi usare come writer sottostante. |

### Valore di ritorno

Un oggetto [XmlWriter](../) avvolto attorno all'oggetto [XmlWriter](../) specificato.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) metodo


Crea una nuova istanza [XmlWriter](../) utilizzando gli oggetti [XmlWriter](../) e [XmlWriterSettings](../../xmlwritersettings/) specificati.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | L'oggetto [XmlWriter](../) che vuoi usare come writer sottostante. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L'oggetto [XmlWriterSettings](../../xmlwritersettings/) usato per configurare la nuova istanza [XmlWriter](../). Se è **nullptr**, viene usato un [XmlWriterSettings](../../xmlwritersettings/) con impostazioni predefinite. Se il [XmlWriter](../) è utilizzato con il metodo XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , dovresti usare il valore XslCompiledTransform::get_OutputSettings per ottenere un oggetto [XmlWriterSettings](../../xmlwritersettings/) con le impostazioni corrette. Questo garantisce che l'oggetto [XmlWriter](../) creato abbia le impostazioni di output corrette. |

### Valore di ritorno

Un oggetto [XmlWriter](../) avvolto attorno all'oggetto [XmlWriter](../) specificato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../)
* Classe [String](../../../system/string/)
* Classe [XmlWriterSettings](../../xmlwritersettings/)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)