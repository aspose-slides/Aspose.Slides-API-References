---
title: Compare()
second_title: Aspose.Slides C++ API-referencia
description: Karakterláncokat hasonlít össze. Nincs megvalósítva.
type: docs
weight: 66
url: /hu/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method

Karakterláncokat hasonlít össze. Nincs megvalósítva.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Bal oldal karakterlánc. |
| string2 | const [String](../../../system/string/)\& | Jobb oldal karakterlánc. |

### Visszatérési érték

Negatív érték, ha a bal oldal karakterlánc megelőzi a jobb oldalt, nulla ha egyeznek, egyébként pozitív érték.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method

Karakterláncokat hasonlít össze. Csak az Ordinal és az OrdinalIgnoreCase módok támogatottak.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Bal oldal karakterlánc. |
| b | const [String](../../../system/string/)\& | Jobb oldal karakterlánc. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) összehasonlítási típus. |

### Visszatérési érték

Negatív érték, ha a bal oldal karakterlánc megelőzi a jobb oldalt, nulla ha egyeznek, egyébként pozitív érték.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method

Egy karakterlánc egy szakaszát hasonlítja össze egy másik karakterlánc egy szakaszával. Nincs megvalósítva.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Első karakterlánc. |
| offset1 | int | A karakterek kezdőindexe a **string1**-ben. |
| length1 | int | A **string1**-ben összehasonlítandó karakterek száma. |
| string2 | const [String](../../../system/string/)\& | Második karakterlánc. |
| offset2 | int | A karakterek kezdőindexe a **string2**-ben. |
| length2 | int | A **string2**-ben összehasonlítandó karakterek száma. |

### Visszatérési érték

Negatív érték, ha az első karakterlánc szakasz megelőzi a második karakterlánc szakaszát, nulla ha egyeznek, egyébként pozitív érték.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method

Egy karakterlánc végső szakaszát hasonlítja össze egy másik karakterlánc végső szakaszával a karakterlánc-összehasonlító módszerek használatával. Nincs megvalósítva.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Első karakterlánc. |
| offset1 | int | A karakterek kezdőindexe a **string1**-ben. |
| string2 | const [String](../../../system/string/)\& | Második karakterlánc. |
| offset2 | int | A karakterek kezdőindexe a **string2**-ben. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) összehasonlítási beállítások. |

### Visszatérési érték

Negatív érték, ha az első karakterlánc szakasz megelőzi a második karakterlánc szakaszát, nulla ha egyeznek, egyébként pozitív érték.

## CompareInfo::Compare(const String\&, int, const String\&, int) const method

Egy karakterlánc végső szakaszát hasonlítja össze egy másik karakterlánc végső szakaszával. Nincs megvalósítva.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Első karakterlánc. |
| offset1 | int | A karakterek kezdőindexe a **string1**-ben. |
| string2 | const [String](../../../system/string/)\& | Második karakterlánc. |
| offset2 | int | A karakterek kezdőindexe a **string2**-ben. |

### Visszatérési érték

Negatív érték, ha az első karakterlánc szakasz megelőzi a második karakterlánc szakaszát, nulla ha egyeznek, egyébként pozitív érték.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method

Egy karakterlánc egy szakaszát hasonlítja össze egy másik karakterlánc egy szakaszával a karakterlánc-összehasonlító módszerek használatával. Nincs megvalósítva.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Első karakterlánc. |
| offset1 | int | A karakterek kezdőindexe a **string1**-ben. |
| length1 | int | A **string1**-ben összehasonlítandó karakterek száma. |
| string2 | const [String](../../../system/string/)\& | Második karakterlánc. |
| offset2 | int | A karakterek kezdőindexe a **string2**-ben. |
| length2 | int | A **string2**-ben összehasonlítandó karakterek száma. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) összehasonlítási beállítások. |

### Visszatérési érték

Negatív érték, ha az első karakterlánc szakasz megelőzi a második karakterlánc szakaszát, nulla ha egyeznek, egyébként pozitív érték.

## Lásd még

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)