---
title: ToString()
second_title: Aspose.Slides for C++ API-referencia
description: Az adott bájttömb összes értékét hexadecimális karakterlánc ábrázolássá konvertálja. A hexadecimális jelölésben használandó betűk nagybetűssége és a szomszédos bájtok között beillesztett elválasztó a megfelelő argumentumokkal van megadva.
type: docs
weight: 157
url: /hu/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method

Az adott bájttömb összes értékét hexadecimális karakterlánc ábrázolásává konvertálja. A hexadecimális jelölésben használandó betűk nagybetűssége és a szomszédos bájtok között beillesztett elválasztó a megfelelő argumentumokkal van megadva.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| uppercase | **bool** | Meghatározza a betűk nagybetűs vagy kisbetűs formáját a kapott hexadecimális ábrázolásban |
| separator | const [String](../../string/)\& | Egy karakterlánc, amely elválasztóként kerül beillesztésre a szomszédos bájtok párosai közé a kapott karakterláncban |

### Visszatérési érték

[String](../../string/) amely a megadott bájttömb hexadecimális ábrázolását tartalmazza

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method

Az adott bájttömb értékeit hexadecimális karakterláncá alakítja, a megadott indexnél kezdve.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a megadott tömbben, ahol a konvertálás kezdődik |

### Visszatérési érték

[String](../../string/) amely a megadott tömb adott elemtartományának hexadecimális ábrázolását tartalmazza

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method

Az adott bájttömb egy tartományának értékeit hexadecimális karakterláncá alakítja.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a megadott tömbben, ahol a konvertálandó bájtok tartománya kezdődik |
| length | int | A konvertálandó bájtok tartományának hossza |

### Visszatérési érték

[String](../../string/) amely a megadott tömb adott elemtartományának hexadecimális ábrázolását tartalmazza

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)