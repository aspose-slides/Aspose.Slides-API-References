---
title: Create()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową instancję XmlReader z określonym adresem URI.
type: docs
weight: 1015
url: /pl/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) metoda


Tworzy nową instancję [XmlReader](../) z określonym adresem URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Adres URI pliku zawierającego dane XML. Klasa [XmlUrlResolver](../../xmlurlresolver/) jest używana do konwersji ścieżki na kanoniczną reprezentację danych. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego adresu URI i ustawień.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Adres URI pliku zawierającego dane XML. Obiekt [XmlResolver](../../xmlresolver/) na obiekcie [XmlReaderSettings](../../xmlreadersettings/) jest używany do konwersji ścieżki na kanoniczną reprezentację danych. Jeśli wartość XmlReaderSettings::get_XmlResolver jest **nullptr**, używany jest nowy obiekt [XmlUrlResolver](../../xmlurlresolver/). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Ustawienia nowej instancji [XmlReader](../). Ta wartość może być **nullptr**. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego adresu URI, ustawień oraz informacji kontekstowych do parsowania.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Adres URI pliku zawierającego dane XML. Obiekt [XmlResolver](../../xmlresolver/) na obiekcie [XmlReaderSettings](../../xmlreadersettings/) jest używany do konwersji ścieżki na kanoniczną reprezentację danych. Jeśli wartość XmlReaderSettings::get_XmlResolver jest **nullptr**, używany jest nowy obiekt [XmlUrlResolver](../../xmlurlresolver/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Ustawienia nowej instancji [XmlReader](../). Ta wartość może być **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Informacje kontekstowe wymagane do parsowania fragmentu XML. Informacje kontekstowe mogą zawierać [XmlNameTable](../../xmlnametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżący zakres **xml:lang** i **xml:space**, podstawowy adres URI oraz definicję typu dokumentu. Ta wartość może być **nullptr**. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego strumienia z domyślnymi ustawieniami.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML. [XmlReader](../) przegląda pierwsze bajty strumienia w poszukiwaniu znacznika kolejności bajtów lub innego wskazania kodowania. Gdy kodowanie zostanie określone, jest ono używane do dalszego odczytu strumienia, a przetwarzanie kontynuuje parsowanie wejścia jako strumienia znaków (Unicode). |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) metoda


Tworzy nową instancję [XmlReader](../) z określonym strumieniem i ustawieniami.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML. [XmlReader](../) przegląda pierwsze bajty strumienia w poszukiwaniu znacznika kolejności bajtów lub innego wskazania kodowania. Gdy kodowanie zostanie określone, jest ono używane do dalszego odczytu strumienia, a przetwarzanie kontynuuje parsowanie wejścia jako strumienia znaków (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Ustawienia nowej instancji [XmlReader](../). Ta wartość może być **nullptr**. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego strumienia, podstawowego adresu URI oraz ustawień.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML. [XmlReader](../) przegląda pierwsze bajty strumienia w poszukiwaniu znacznika kolejności bajtów lub innego wskazania kodowania. Gdy kodowanie zostanie określone, jest ono używane do dalszego odczytu strumienia, a przetwarzanie kontynuuje parsowanie wejścia jako strumienia znaków (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Ustawienia nowej instancji [XmlReader](../). Ta wartość może być **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Podstawowy adres URI dla odczytywanego podmiotu lub dokumentu. Ta wartość może być **nullptr**. **[Security](../../../system.security/) Uwaga** Podstawowy adres URI jest używany do rozwiązywania względnego adresu URI dokumentu XML. Nie należy używać podstawowego adresu URI z niezaufanego źródła. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego strumienia, ustawień oraz informacji kontekstowych do parsowania.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML. [XmlReader](../) przegląda pierwsze bajty strumienia w poszukiwaniu znacznika kolejności bajtów lub innego wskazania kodowania. Gdy kodowanie zostanie określone, jest ono używane do dalszego odczytu strumienia, a przetwarzanie kontynuuje parsowanie wejścia jako strumienia znaków (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Ustawienia nowej instancji [XmlReader](../). Ta wartość może być **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Informacje kontekstowe wymagane do parsowania fragmentu XML. Informacje kontekstowe mogą zawierać [XmlNameTable](../../xmlnametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżący zakres **xml:lang** i **xml:space**, podstawowy adres URI oraz definicję typu dokumentu. Ta wartość może być **nullptr**. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego czytnika tekstu.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Czytnik tekstu, z którego odczytywane są dane XML. Czytnik tekstu zwraca strumień znaków Unicode, więc kodowanie określone w deklaracji XML nie jest używane przez czytnik XML do dekodowania strumienia danych. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego czytnika tekstu i ustawień.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Czytnik tekstu, z którego odczytywane są dane XML. Czytnik tekstu zwraca strumień znaków Unicode, więc kodowanie określone w deklaracji XML nie jest używane przez czytnik XML do dekodowania strumienia danych. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Ustawienia nowej [XmlReader](../). Ta wartość może być **nullptr**. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego czytnika tekstu, ustawień oraz podstawowego adresu URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Czytnik tekstu, z którego odczytywane są dane XML. Czytnik tekstu zwraca strumień znaków Unicode, więc kodowanie określone w deklaracji XML nie jest używane przez [XmlReader](../) do dekodowania strumienia danych. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Ustawienia nowej [XmlReader](../). Ta wartość może być **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Podstawowy adres URI dla odczytywanego podmiotu lub dokumentu. Ta wartość może być **nullptr**. **[Security](../../../system.security/) Uwaga** Podstawowy adres URI jest używany do rozwiązywania względnego adresu URI dokumentu XML. Nie należy używać podstawowego adresu URI z niezaufanego źródła. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego czytnika tekstu, ustawień oraz informacji kontekstowych do parsowania.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Czytnik tekstu, z którego odczytywane są dane XML. Czytnik tekstu zwraca strumień znaków Unicode, więc kodowanie określone w deklaracji XML nie jest używane przez czytnik XML do dekodowania strumienia danych. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Ustawienia nowej [XmlReader](../). Ta wartość może być **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Informacje kontekstowe wymagane do parsowania fragmentu XML. Informacje kontekstowe mogą zawierać [XmlNameTable](../../xmlnametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżący zakres **xml:lang** i **xml:space**, podstawowy adres URI oraz definicję typu dokumentu. Ta wartość może być **nullptr**. |

### Wartość zwracana

Obiekt używany do odczytu danych XML w strumieniu.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) metoda


Tworzy nową instancję [XmlReader](../) przy użyciu określonego czytnika XML i ustawień.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Obiekt, którego chcesz użyć jako bazowego czytnika XML. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Ustawienia nowej [XmlReader](../). Poziom zgodności obiektu [XmlReaderSettings](../../xmlreadersettings/) musi być zgodny z poziomem zgodności bazowego czytnika lub musi być ustawiony na [ConformanceLevel::Auto](../../conformancelevel/). |

### Wartość zwracana

Obiekt owinący określony obiekt [XmlReader](../).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlReader](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlReaderSettings](../../xmlreadersettings/)
* Klasa [XmlParserContext](../../xmlparsercontext/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [TextReader](../../../system.io/textreader/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)