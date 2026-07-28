---
title: Create()
second_title: Odwołanie API Aspose.Slides dla C++
description: Tworzy nową instancję XmlWriter przy użyciu określonej nazwy pliku.
type: docs
weight: 469
url: /pl/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu określonej nazwy pliku.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Plik, do którego chcesz zapisać. [XmlWriter](../) tworzy plik w określonej ścieżce i zapisuje go w składni tekstowej XML 1.0. **outputFileName** musi być ścieżką systemu plików. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu nazwy pliku i obiektu [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Plik, do którego chcesz zapisać. [XmlWriter](../) tworzy plik w określonej ścieżce i zapisuje go w składni tekstowej XML 1.0. **outputFileName** musi być ścieżką systemu plików. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Obiekt [XmlWriterSettings](../../xmlwritersettings/) używany do skonfigurowania nowej instancji [XmlWriter](../). Jeśli jest to **nullptr**, używany jest [XmlWriterSettings](../../xmlwritersettings/) z ustawieniami domyślnymi. Jeśli [XmlWriter](../) jest używany z metodą XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metoda, należy użyć wartości XslCompiledTransform::get_OutputSettings, aby uzyskać obiekt [XmlWriterSettings](../../xmlwritersettings/) z odpowiednimi ustawieniami. To zapewnia, że utworzony obiekt [XmlWriter](../) ma prawidłowe ustawienia wyjściowe. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu określonego strumienia.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisać. [XmlWriter](../) zapisuje w składni tekstowej XML 1.0 i dopisuje to do określonego strumienia. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu strumienia i obiektu [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisać. [XmlWriter](../) zapisuje w składni tekstowej XML 1.0 i dopisuje go do określonego strumienia. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Obiekt [XmlWriterSettings](../../xmlwritersettings/) używany do skonfigurowania nowej instancji [XmlWriter](../). Jeśli jest to **nullptr**, używany jest [XmlWriterSettings](../../xmlwritersettings/) z ustawieniami domyślnymi. Jeśli [XmlWriter](../) jest używany z metodą XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metoda, należy użyć wartości XslCompiledTransform::get_OutputSettings, aby uzyskać obiekt [XmlWriterSettings](../../xmlwritersettings/) z odpowiednimi ustawieniami. To zapewnia, że utworzony obiekt [XmlWriter](../) ma prawidłowe ustawienia wyjściowe. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu określonego TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego chcesz zapisać. [XmlWriter](../) zapisuje w składni tekstowej XML 1.0 i dopisuje go do określonego TextWriter. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu TextWriter oraz obiektów [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego chcesz zapisać. [XmlWriter](../) zapisuje w składni tekstowej XML 1.0 i dopisuje go do określonego TextWriter. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Obiekt [XmlWriterSettings](../../xmlwritersettings/) używany do skonfigurowania nowej instancji [XmlWriter](../). Jeśli jest to **nullptr**, używany jest [XmlWriterSettings](../../xmlwritersettings/) z ustawieniami domyślnymi. Jeśli [XmlWriter](../) jest używany z metodą XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metoda, należy użyć wartości XslCompiledTransform::get_OutputSettings, aby uzyskać obiekt [XmlWriterSettings](../../xmlwritersettings/) z odpowiednimi ustawieniami. To zapewnia, że utworzony obiekt [XmlWriter](../) ma prawidłowe ustawienia wyjściowe. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu określonego [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/), do którego zapisywać. Zawartość zapisana przez [XmlWriter](../) jest dopisywana do [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu obiektów [Text::StringBuilder](../../../system.text/stringbuilder/) i [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/), do którego zapisywać. Zawartość zapisana przez [XmlWriter](../) jest dopisywana do [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Obiekt [XmlWriterSettings](../../xmlwritersettings/) używany do skonfigurowania nowej instancji [XmlWriter](../). Jeśli jest to **nullptr**, używany jest [XmlWriterSettings](../../xmlwritersettings/) z ustawieniami domyślnymi. Jeśli [XmlWriter](../) jest używany z metodą XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metoda, należy użyć wartości XslCompiledTransform::get_OutputSettings, aby uzyskać obiekt [XmlWriterSettings](../../xmlwritersettings/) z odpowiednimi ustawieniami. To zapewnia, że utworzony obiekt [XmlWriter](../) ma prawidłowe ustawienia wyjściowe. |

### Wartość zwracana

Obiekt [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu określonego obiektu [XmlWriter](../).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | [XmlWriter](../) obiekt, którego chcesz użyć jako podstawowego writera. |

### Wartość zwracana

Obiekt [XmlWriter](../) otoczony wokół określonego obiektu [XmlWriter](../).



## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) metoda


Tworzy nową instancję [XmlWriter](../) przy użyciu określonych [XmlWriter](../) i [XmlWriterSettings](../../xmlwritersettings/) obiektów.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | [XmlWriter](../) obiekt, którego chcesz użyć jako podstawowego writera. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Obiekt [XmlWriterSettings](../../xmlwritersettings/) używany do skonfigurowania nowej instancji [XmlWriter](../). Jeśli jest to **nullptr**, używany jest [XmlWriterSettings](../../xmlwritersettings/) z ustawieniami domyślnymi. Jeśli [XmlWriter](../) jest używany z metodą XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metoda, należy użyć wartości XslCompiledTransform::get_OutputSettings, aby uzyskać obiekt [XmlWriterSettings](../../xmlwritersettings/) z odpowiednimi ustawieniami. To zapewnia, że utworzony obiekt [XmlWriter](../) ma prawidłowe ustawienia wyjściowe. |

### Wartość zwracana

Obiekt [XmlWriter](../) otoczony wokół określonego obiektu [XmlWriter](../).



## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlWriter](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlWriterSettings](../../xmlwritersettings/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [TextWriter](../../../system.io/textwriter/)
* Klasa [StringBuilder](../../../system.text/stringbuilder/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)