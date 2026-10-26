---
title: XmlTextWriter()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy példányt az XmlTextWriter osztályból a megadott adatfolyam és kódolás használatával.
type: docs
weight: 183
url: /hu/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor

Létrehoz egy példányt a [XmlTextWriter](../) osztályból a megadott adatfolyam és kódolás használatával.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az adatfolyam, amelybe írni szeretne. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A generálandó kódolás. Ha a kódolás **nullptr**, akkor az adatfolyamot UTF-8ként írja ki, és elhagyja a kódolás attribútumot a **ProcessingInstruction**-ból. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) konstruktor

Létrehoz egy példányt a [XmlTextWriter](../) osztályból a megadott fájl használatával.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A fájlnév, amelybe írni kíván. Ha a fájl létezik, akkor levágja és felülírja az új tartalommal. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A generálandó kódolás. Ha a kódolás **nullptr**, akkor a fájlt UTF-8ként írja ki, és elhagyja a kódolás attribútumot a **ProcessingInstruction**-ból. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) konstruktor

Létrehoz egy példányt a [XmlTextWriter](../) osztályból a megadott TextWriter használatával.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe írni kíván. Feltételezzük, hogy a TextWriter már a megfelelő kódolásra van beállítva. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [Encoding](../../../system.text/encoding/)
* Osztály [XmlTextWriter](../)
* Osztály [String](../../../system/string/)
* Osztály [TextWriter](../../../system.io/textwriter/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)