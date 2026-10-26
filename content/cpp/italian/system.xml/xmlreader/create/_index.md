---
title: Create()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza XmlReader con l'URI specificato.
type: docs
weight: 1015
url: /it/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) metodo


Crea una nuova istanza [XmlReader](../) con l'URI specificato.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI per il file che contiene i dati XML. La classe [XmlUrlResolver](../../xmlurlresolver/) è utilizzata per convertire il percorso in una rappresentazione canonica dei dati. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) metodo


Crea una nuova istanza [XmlReader](../) utilizzando l'URI e le impostazioni specificati.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI per il file contenente i dati XML. L'oggetto [XmlResolver](../../xmlresolver/) sull'oggetto [XmlReaderSettings](../../xmlreadersettings/) è utilizzato per convertire il percorso in una rappresentazione canonica dei dati. Se il valore XmlReaderSettings::get_XmlResolver è **nullptr**, viene usato un nuovo oggetto [XmlUrlResolver](../../xmlurlresolver/). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metodo


Crea una nuova istanza [XmlReader](../) utilizzando l'URI, le impostazioni e le informazioni di contesto per l'analisi.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI per il file contenente i dati XML. L'oggetto [XmlResolver](../../xmlresolver/) sull'oggetto [XmlReaderSettings](../../xmlreadersettings/) è utilizzato per convertire il percorso in una rappresentazione canonica dei dati. Se il valore XmlReaderSettings::get_XmlResolver è **nullptr**, viene usato un nuovo oggetto [XmlUrlResolver](../../xmlurlresolver/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le informazioni di contesto necessarie per analizzare il frammento XML. Le informazioni di contesto possono includere il [XmlNameTable](../../xmlnametable/) da usare, la codifica, lo spazio dei nomi, l'ambito corrente **xml:lang** e **xml:space**, l'URI di base e la definizione del tipo di documento. Questo valore può essere **nullptr**. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) metodo


Crea una nuova istanza [XmlReader](../) usando lo stream specificato con impostazioni predefinite.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream che contiene i dati XML. Il [XmlReader](../) esamina i primi byte dello stream alla ricerca di un byte order mark o di altri segnali di codifica. Quando la codifica è determinata, viene usata per continuare la lettura dello stream, e l'elaborazione prosegue analizzando l'input come un flusso di caratteri (Unicode). |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) metodo


Crea una nuova istanza [XmlReader](../) con lo stream e le impostazioni specificati.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream che contiene i dati XML. Il [XmlReader](../) esamina i primi byte dello stream alla ricerca di un byte order mark o di altri segnali di codifica. Quando la codifica è determinata, viene usata per continuare la lettura dello stream, e l'elaborazione prosegue analizzando l'input come un flusso di caratteri (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metodo


Crea una nuova istanza [XmlReader](../) usando lo stream, l'URI di base e le impostazioni specificati.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream che contiene i dati XML. Il [XmlReader](../) esamina i primi byte dello stream alla ricerca di un byte order mark o di altri segnali di codifica. Quando la codifica è determinata, viene usata per continuare la lettura dello stream, e l'elaborazione prosegue analizzando l'input come un flusso di caratteri (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | L'URI di base per l'entità o il documento da leggere. Questo valore può essere **nullptr**. **[Security](../../../system.security/) Nota** L'URI di base è usato per risolvere l'URI relativo del documento XML. Non utilizzare un URI di base da una fonte non attendibile. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metodo


Crea una nuova istanza [XmlReader](../) usando lo stream, le impostazioni e le informazioni di contesto per l'analisi.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream che contiene i dati XML. Il [XmlReader](../) esamina i primi byte dello stream alla ricerca di un byte order mark o di altri segnali di codifica. Quando la codifica è determinata, viene usata per continuare la lettura dello stream, e l'elaborazione prosegue analizzando l'input come un flusso di caratteri (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le informazioni di contesto necessarie per analizzare il frammento XML. Le informazioni di contesto possono includere il [XmlNameTable](../../xmlnametable/) da usare, la codifica, lo spazio dei nomi, l'ambito corrente **xml:lang** e **xml:space**, l'URI di base e la definizione del tipo di documento. Questo valore può essere **nullptr**. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) metodo


Crea una nuova istanza [XmlReader](../) usando il lettore di testo specificato.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il lettore di testo da cui leggere i dati XML. Un lettore di testo restituisce un flusso di caratteri Unicode, quindi la codifica specificata nella dichiarazione XML non è utilizzata dal lettore XML per decodificare lo stream di dati. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) metodo


Crea una nuova istanza [XmlReader](../) usando il lettore di testo e le impostazioni specificati.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il lettore di testo da cui leggere i dati XML. Un lettore di testo restituisce un flusso di caratteri Unicode, quindi la codifica specificata nella dichiarazione XML non è usata dal lettore XML per decodificare lo stream di dati. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Le impostazioni per il nuovo [XmlReader](../). Questo valore può essere **nullptr**. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metodo


Crea una nuova istanza [XmlReader](../) usando il lettore di testo, le impostazioni e l'URI di base specificati.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il lettore di testo da cui leggere i dati XML. Un lettore di testo restituisce un flusso di caratteri Unicode, quindi la codifica specificata nella dichiarazione XML non è usata dal [XmlReader](../) per decodificare lo stream di dati. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | L'URI di base per l'entità o il documento da leggere. Questo valore può essere **nullptr**. **[Security](../../../system.security/) Nota** L'URI di base è usato per risolvere l'URI relativo del documento XML. Non utilizzare un URI di base da una fonte non attendibile. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metodo


Crea una nuova istanza [XmlReader](../) usando il lettore di testo, le impostazioni e le informazioni di contesto per l'analisi.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il lettore di testo da cui leggere i dati XML. Un lettore di testo restituisce un flusso di caratteri Unicode, quindi la codifica specificata nella dichiarazione XML non è usata dal lettore XML per decodificare lo stream di dati. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Le impostazioni per la nuova istanza [XmlReader](../). Questo valore può essere **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le informazioni di contesto necessarie per analizzare il frammento XML. Le informazioni di contesto possono includere il [XmlNameTable](../../xmlnametable/) da usare, la codifica, lo spazio dei nomi, l'ambito corrente **xml:lang** e **xml:space**, l'URI di base e la definizione del tipo di documento. Questo valore può essere **nullptr**. |

### Valore di ritorno

Un oggetto usato per leggere i dati XML nel flusso.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) metodo


Crea una nuova istanza [XmlReader](../) usando il lettore XML e le impostazioni specificati.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | L'oggetto che si desidera usare come lettore XML sottostante. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Le impostazioni per la nuova istanza [XmlReader](../). Il livello di conformità dell'oggetto [XmlReaderSettings](../../xmlreadersettings/) deve corrispondere al livello di conformità del lettore sottostante, oppure deve essere impostato a [ConformanceLevel::Auto](../../conformancelevel/). |

### Valore di ritorno

Un oggetto incapsulato intorno all'oggetto [XmlReader](../) specificato.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)