---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue XmlReader-Instanz mit der angegebenen URI.
type: docs
weight: 1015
url: /de/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mit der angegebenen URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Der URI für die Datei, die die XML-Daten enthält. Die Klasse [XmlUrlResolver](../../xmlurlresolver/) wird verwendet, um den Pfad in eine kanonische Datenrepräsentation zu konvertieren. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe der angegebenen URI und Einstellungen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Der URI für die Datei, die die XML-Daten enthält. Das [XmlResolver](../../xmlresolver/) Objekt auf dem [XmlReaderSettings](../../xmlreadersettings/) Objekt wird verwendet, um den Pfad in eine kanonische Datenrepräsentation zu konvertieren. Wenn der Wert von XmlReaderSettings::get_XmlResolver **nullptr** ist, wird ein neues [XmlUrlResolver](../../xmlurlresolver/) Objekt verwendet. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe der angegebenen URI, Einstellungen und Kontextinformationen zum Parsen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Der URI für die Datei, die die XML-Daten enthält. Das [XmlResolver](../../xmlresolver/) Objekt auf dem [XmlReaderSettings](../../xmlreadersettings/) Objekt wird verwendet, um den Pfad in eine kanonische Datenrepräsentation zu konvertieren. Wenn der Wert von XmlReaderSettings::get_XmlResolver **nullptr** ist, wird ein neues [XmlUrlResolver](../../xmlurlresolver/) Objekt verwendet. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Die Kontextinformationen, die zum Parsen des XML-Fragments erforderlich sind. Die Kontextinformationen können den zu verwendenden [XmlNameTable](../../xmlnametable/), die Kodierung, den Namensraum-Geltungsbereich, den aktuellen **xml:lang**- und **xml:space**-Geltungsbereich, die Basis-URI und die Dokumenttypdefinition umfassen. Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Streams mit Standardeinstellungen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die XML-Daten enthält. Der [XmlReader](../) scannt die ersten Bytes des Streams, um nach einer Byte Order Mark oder anderen Anzeichen für die Kodierung zu suchen. Wenn die Kodierung bestimmt ist, wird sie verwendet, um das Lesen des Streams fortzusetzen, und die Verarbeitung liest die Eingabe weiterhin als Stream von (Unicode-) Zeichen. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mit dem angegebenen Stream und den Einstellungen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die XML-Daten enthält. Der [XmlReader](../) scannt die ersten Bytes des Streams, um nach einer Byte Order Mark oder anderen Anzeichen für die Kodierung zu suchen. Wenn die Kodierung bestimmt ist, wird sie verwendet, um das Lesen des Streams fortzusetzen, und die Verarbeitung liest die Eingabe weiterhin als Stream von (Unicode-) Zeichen. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Streams, der Basis-URI und der Einstellungen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die XML-Daten enthält. Der [XmlReader](../) scannt die ersten Bytes des Streams, um nach einer Byte Order Mark oder anderen Anzeichen für die Kodierung zu suchen. Wenn die Kodierung bestimmt ist, wird sie verwendet, um das Lesen des Streams fortzusetzen, und die Verarbeitung liest die Eingabe weiterhin als Stream von (Unicode-) Zeichen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |
| baseUri | const [String](../../../system/string/)\& | Die Basis-URI für das zu lesende Entity oder Dokument. Dieser Wert kann **nullptr** sein. **[Security](../../../system.security/) Hinweis** Die Basis-URI wird verwendet, um die relative URI des XML-Dokuments aufzulösen. Verwenden Sie keine Basis-URI aus einer nicht vertrauenswürdigen Quelle. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Streams, der Einstellungen und Kontextinformationen zum Parsen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die XML-Daten enthält. Der [XmlReader](../) scannt die ersten Bytes des Streams, um nach einer Byte Order Mark oder anderen Anzeichen für die Kodierung zu suchen. Wenn die Kodierung bestimmt ist, wird sie verwendet, um das Lesen des Streams fortzusetzen, und die Verarbeitung liest die Eingabe weiterhin als Stream von (Unicode-) Zeichen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Die Kontextinformationen, die zum Parsen des XML-Fragments erforderlich sind. Die Kontextinformationen können den zu verwendenden [XmlNameTable](../../xmlnametable/), die Kodierung, den Namensraum-Geltungsbereich, den aktuellen **xml:lang**- und **xml:space**-Geltungsbereich, die Basis-URI und die Dokumenttypdefinition umfassen. Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Text-Readers.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der Text-Reader, aus dem die XML-Daten gelesen werden. Ein Text-Reader liefert einen Stream von Unicode-Zeichen, sodass die im XML-Deklaration angegebene Kodierung nicht vom XML-Reader zum Dekodieren des Daten-Streams verwendet wird. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Text-Readers und der Einstellungen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der Text-Reader, aus dem die XML-Daten gelesen werden. Ein Text-Reader liefert einen Stream von Unicode-Zeichen, sodass die im XML-Deklaration angegebene Kodierung nicht vom XML-Reader zum Dekodieren des Daten-Streams verwendet wird. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Die Einstellungen für das neue [XmlReader](../). Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Text-Readers, der Einstellungen und der Basis-URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der Text-Reader, aus dem die XML-Daten gelesen werden. Ein Text-Reader liefert einen Stream von Unicode-Zeichen, sodass die im XML-Deklaration angegebene Kodierung nicht vom [XmlReader](../) zum Dekodieren des Daten-Streams verwendet wird. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |
| baseUri | const [String](../../../system/string/)\& | Die Basis-URI für das zu lesende Entity oder Dokument. Dieser Wert kann **nullptr** sein. **[Security](../../../system.security/) Hinweis** Die Basis-URI wird verwendet, um die relative URI des XML-Dokuments aufzulösen. Verwenden Sie keine Basis-URI aus einer nicht vertrauenswürdigen Quelle. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen Text-Readers, der Einstellungen und Kontextinformationen zum Parsen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der Text-Reader, aus dem die XML-Daten gelesen werden. Ein Text-Reader liefert einen Stream von Unicode-Zeichen, sodass die im XML-Deklaration angegebene Kodierung nicht vom XML-Reader zum Dekodieren des Daten-Streams verwendet wird. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Die Einstellungen für die neue [XmlReader](../) Instanz. Dieser Wert kann **nullptr** sein. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Die Kontextinformationen, die zum Parsen des XML-Fragments erforderlich sind. Die Kontextinformationen können den zu verwendenden [XmlNameTable](../../xmlnametable/), die Kodierung, den Namensraum-Geltungsbereich, den aktuellen **xml:lang**- und **xml:space**-Geltungsbereich, die Basis-URI und die Dokumenttypdefinition umfassen. Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Ein Objekt, das zum Lesen der XML-Daten im Stream verwendet wird.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) Methode


Erstellt eine neue [XmlReader](../) Instanz mithilfe des angegebenen XML-Readers und der Einstellungen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Das Objekt, das Sie als zugrunde liegenden XML-Reader verwenden möchten. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Die Einstellungen für die neue [XmlReader](../) Instanz. Das Konformitätsniveau des [XmlReaderSettings](../../xmlreadersettings/) Objekts muss entweder dem Konformitätsniveau des zugrunde liegenden Readers entsprechen oder auf [ConformanceLevel::Auto](../../conformancelevel/) gesetzt werden. |

### Rückgabewert

Ein Objekt, das das angegebene [XmlReader](../) Objekt umschließt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReaderSettings](../../xmlreadersettings/)
* Klasse [XmlParserContext](../../xmlparsercontext/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)