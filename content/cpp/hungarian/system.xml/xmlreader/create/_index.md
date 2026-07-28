---
title: Create()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy új XmlReader példányt a megadott URI-val.
type: docs
weight: 1015
url: /hu/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott URI-val.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A URI a fájlhoz, amely az XML adatot tartalmazza. A [XmlUrlResolver](../../xmlurlresolver/) osztályt az útvonal kanonikus adatábrázolássá konvertálására használják. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott URI és beállítások használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A URI a fájlhoz, amely az XML adatot tartalmazza. A [XmlResolver](../../xmlresolver/) objektum a [XmlReaderSettings](../../xmlreadersettings/) objektumon használatos az útvonal kanonikus adatábrázolássá konvertálására. Ha az XmlReaderSettings::get_XmlResolver értéke **nullptr**, egy új [XmlUrlResolver](../../xmlurlresolver/) objektumot használnak. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Az új [XmlReader](../) példány beállításai. Ez az érték lehet **nullptr**. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott URI, beállítások és a feldolgozáshoz szükséges kontextus információk használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A URI a fájlhoz, amely az XML adatot tartalmazza. A [XmlResolver](../../xmlresolver/) objektum a [XmlReaderSettings](../../xmlreadersettings/) objektumon használatos az útvonal kanonikus adatábrázolássá konvertálására. Ha az XmlReaderSettings::get_XmlResolver értéke **nullptr**, egy új [XmlUrlResolver](../../xmlurlresolver/) objektumot használnak. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Az új [XmlReader](../) példány beállításai. Ez az érték lehet **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A kontextus információ, amely az XML töredék feldolgozásához szükséges. A kontextus információ tartalmazhatja a [XmlNameTable](../../xmlnametable/) használatát, kódolást, névtér hatókört, a jelenlegi **xml:lang** és **xml:space** hatókört, alap URI-t és a dokumentumtípus-definíciót. Ez az érték lehet **nullptr**. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott stream használatával alapértelmezett beállításokkal.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az a stream, amely az XML adatot tartalmazza. A [XmlReader](../) a stream első bájtjait keresi a bájtrendelés jelzés vagy más kódolási jelzés után. Amint a kódolás meghatározásra kerül, azt használják a stream további olvasásához, és a feldolgozás folytatódik a (Unicode) karakterek streamként történő elemzésével. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott stream és beállítások használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az a stream, amely az XML adatot tartalmazza. A [XmlReader](../) a stream első bájtjait keresi a bájtrendelés jelzés vagy más kódolási jelzés után. Amint a kódolás meghatározásra kerül, azt használják a stream további olvasásához, és a feldolgozás folytatódik a (Unicode) karakterek streamként történő elemzésével. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Az új [XmlReader](../) példány beállításai. Ez az érték lehet **nullptr**. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott stream, alap URI és beállítások használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az a stream, amely az XML adatot tartalmazza. A [XmlReader](../) a stream első bájtjait keresi a bájtrendelés jelzés vagy más kódolási jelzés után. Amint a kódolás meghatározásra kerül, azt használják a stream további olvasásához, és a feldolgozás folytatódik a (Unicode) karakterek streamként történő elemzésével. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Az új [XmlReader](../) példány beállításai. Ez az érték lehet **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Az entitás vagy dokumentum alap URI-ja, amelyet olvasunk. Ez az érték lehet **nullptr**. **[Security](../../../system.security/) Megjegyzés** Az alap URI-t a relatív URI feloldásához használják az XML dokumentumban. Ne használjon megbízhatatlan forrásból származó alap URI-t. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott stream, beállítások és a feldolgozáshoz szükséges kontextus információk használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az a stream, amely az XML adatot tartalmazza. A [XmlReader](../) a stream első bájtjait keresi a bájtrendelés jelzés vagy más kódolási jelzés után. Amint a kódolás meghatározásra kerül, azt használják a stream további olvasásához, és a feldolgozás folytatódik a (Unicode) karakterek streamként történő elemzésével. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Az új [XmlReader](../) példány beállításai. Ez az érték lehet **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A kontextus információ, amely az XML töredék feldolgozásához szükséges. A kontextus információ tartalmazhatja a [XmlNameTable](../../xmlnametable/) használatát, kódolást, névtér hatókört, a jelenlegi **xml:lang** és **xml:space** hatókört, alap URI-t és a dokumentumtípus-definíciót. Ez az érték lehet **nullptr**. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott szövegolvasó használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | A szövegolvasó, amelyből az XML adatot olvassák. A szövegolvasó Unicode karakterek streamjét adja vissza, így az XML deklarációban megadott kódolást az XML olvasó nem használja a data stream dekódolásához. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott szövegolvasó és beállítások használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | A szövegolvasó, amelyből az XML adatot olvassák. A szövegolvasó Unicode karakterek streamjét adja vissza, így az XML deklarációban megadott kódolást az XML olvasó nem használja a data stream dekódolásához. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Az új [XmlReader](../) beállításai. Ez az érték lehet **nullptr**. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott szövegolvasó, beállítások és alap URI használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | A szövegolvasó, amelyből az XML adatot olvassák. A szövegolvasó Unicode karakterek streamjét adja vissza, így az XML deklarációban megadott kódolást a [XmlReader](../) nem használja a data stream dekódolásához. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Az új [XmlReader](../) példány beállításai. Ez az érték lehet **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Az entitás vagy dokumentum alap URI-ja, amelyet olvasunk. Ez az érték lehet **nullptr**. **[Security](../../../system.security/) Megjegyzés** Az alap URI-t a relatív URI feloldásához használják az XML dokumentumban. Ne használjon megbízhatatlan forrásból származó alap URI-t. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott szövegolvasó, beállítások és kontextus információk használatával az elemzéshez.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | A szövegolvasó, amelyből az XML adatot olvassák. A szövegolvasó Unicode karakterek streamjét adja vissza, így az XML deklarációban megadott kódolást az XML olvasó nem használja a data stream dekódolásához. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Az új [XmlReader](../) beállításai. Ez az érték lehet **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A kontextus információ, amely az XML töredék feldolgozásához szükséges. A kontextus információ tartalmazhatja a [XmlNameTable](../../xmlnametable/) használatát, kódolást, névtér hatókört, a jelenlegi **xml:lang** és **xml:space** hatókört, alap URI-t és a dokumentumtípus-definíciót. Ez az érték lehet **nullptr**. |

### Visszatérési érték

Egy objektum, amelyet az XML adatok streamben történő olvasásához használnak.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) metódus

Létrehoz egy új [XmlReader](../) példányt a megadott XML olvasó és beállítások használatával.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Az az objektum, amelyet az alapul szolgáló XML olvasóként kíván használni. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Az új [XmlReader](../) példány beállításai. A [XmlReaderSettings](../../xmlreadersettings/) objektum megfelelőségi szintjének meg kell egyeznie az alapul szolgáló olvasó megfelelőségi szintjével, vagy [ConformanceLevel::Auto](../../conformancelevel/)-ra kell állítania. |

### Visszatérési érték

Egy objektum, amely a megadott [XmlReader](../) objektum köré van csomagolva.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlReader](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlReaderSettings](../../xmlreadersettings/)
* Osztály [XmlParserContext](../../xmlparsercontext/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [TextReader](../../../system.io/textreader/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)