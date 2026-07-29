---
title: Compare()
second_title: Aspose.Slides för C++ API-referens
description: Jämför strängar. Ej implementerad.
type: docs
weight: 66
url: /sv/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String&, const String&) const metod

Jämför strängar. Ej implementerad.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Vänstersträng. |
| string2 | const [String](../../../system/string/)& | Högersträng. |

### Returvärde

Negativt värde om vänstersträngen föregår högersträngen, noll om de matchar, positivt värde annars.

## CompareInfo::Compare(const String&, const String&, CompareOptions) const metod

Jämför strängar. Endast lägena Ordinal och OrdinalIgnoreCase stöds.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const [String](../../../system/string/)& | Vänstersträng. |
| b | const [String](../../../system/string/)& | Högersträng. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) jämförelsetyp. |

### Returvärde

Negativt värde om vänstersträngen föregår högersträngen, noll om de matchar, positivt värde annars.

## CompareInfo::Compare(const String&, int, int, const String&, int, int) const metod

Jämför ett avsnitt av en sträng med ett avsnitt av en annan sträng. Ej implementerad.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Första strängen. |
| offset1 | int | Startindex för tecken i **string1**. |
| length1 | int | Antal tecken i **string1** att jämföra. |
| string2 | const [String](../../../system/string/)& | Andra strängen. |
| offset2 | int | Startindex för tecken i **string2**. |
| length2 | int | Antal tecken i **string2** att jämföra. |

### Returvärde

Negativt värde om första strängavsnittet föregår andra strängavsnittet, noll om de matchar, positivt värde annars.

## CompareInfo::Compare(const String&, int, const String&, int, CompareOptions) const metod

Jämför slutavsnittet av en sträng med slutavsnittet av en annan sträng med hjälp av strängjämförelsesätt. Ej implementerad.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Första strängen. |
| offset1 | int | Startindex för tecken i **string1**. |
| string2 | const [String](../../../system/string/)& | Andra strängen. |
| offset2 | int | Startindex för tecken i **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) jämförelsalternativ. |

### Returvärde

Negativt värde om första strängavsnittet föregår andra strängavsnittet, noll om de matchar, positivt värde annars.

## CompareInfo::Compare(const String&, int, const String&, int) const metod

Jämför slutavsnittet av en sträng med slutavsnittet av en annan sträng. Ej implementerad.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Första strängen. |
| offset1 | int | Startindex för tecken i **string1**. |
| string2 | const [String](../../../system/string/)& | Andra strängen. |
| offset2 | int | Startindex för tecken i **string2**. |

### Returvärde

Negativt värde om första strängavsnittet föregår andra strängavsnittet, noll om de matchar, positivt värde annars.

## CompareInfo::Compare(const String&, int, int, const String&, int, int, CompareOptions) const metod

Jämför ett avsnitt av en sträng med ett avsnitt av en annan sträng med hjälp av strängjämförelsesätt. Ej implementerad.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Första strängen. |
| offset1 | int | Startindex för tecken i **string1**. |
| length1 | int | Antal tecken i **string1** att jämföra. |
| string2 | const [String](../../../system/string/)& | Andra strängen. |
| offset2 | int | Startindex för tecken i **string2**. |
| length2 | int | Antal tecken i **string2** att jämföra. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) jämförelsalternativ. |

### Returvärde

Negativt värde om första strängavsnittet föregår andra strängavsnittet, noll om de matchar, positivt värde annars.

## Se även

* Enum [CompareOptions](../../compareoptions/)
* Klass [String](../../../system/string/)
* Klass [CompareInfo](../)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)