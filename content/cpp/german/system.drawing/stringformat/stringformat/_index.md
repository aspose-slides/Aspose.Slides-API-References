---
title: StringFormat()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert eine neue Instanz der StringFormat Klasse.
type: docs
weight: 1
url: /de/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() Konstruktor

Konstruiert eine neue Instanz der [StringFormat](../) Klasse.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) Konstruktor

Konstruiert eine neue Instanz der [StringFormat](../) Klasse mit den angegebenen Formatflags und der Sprache.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Eine bitweise Kombination des StringFormatFlags Enum-Wertes, der das Zeichenformat angibt, das vom zu erstellenden Objekt dargestellt werden soll |
| language | **int32_t** | Die Sprache des Textes |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) Konstruktor

Kopierkonstruktor.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Ein [StringFormat](../) Objekt, von dem kopiert werden soll |

## Siehe auch

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [StringFormat](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)