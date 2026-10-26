---
title: FieldType
second_title: Aspose.Slides för Java API-referens
description: Representerar en typ av fält.
type: docs
url: /sv/com.aspose.slides/fieldtype/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

Representerar en typ av fält. Detta värde bestämmer vilken text som kommer att sättas i fältet när det uppdateras.

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | Initierar en ny instans av klassen FieldType. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInternalString()](#getInternalString--) | Returnerar det interna namnet för detta FieldType-objekt. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | Returnerar det interna namnet för detta FieldType-objekt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollerar om detta fält är lika med ett annat. |
| [hashCode()](#hashCode--) | Returnerar hashkod för detta objekt. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Kontrollerar om två FieldType-objekt är lika. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Kontrollerar om två FieldType-objekt är olika. |
| [getSlideNumber()](#getSlideNumber--) | Aktuellt bildnummer. |
| [getFooter()](#getFooter--) | Bildens sidfot. |
| [getHeader()](#getHeader--) | Bildens sidhuvud. |
| [getDateTime()](#getDateTime--) | Aktuellt datum och tid i standarddatumformat för renderingsapplikationen. |
| [getDateTime1()](#getDateTime1--) | Aktuellt datum och tid i det första fördefinierade formatet (MM/DD/YYYY för engelska). |
| [getDateTime2()](#getDateTime2--) | Aktuellt datum och tid i det andra fördefinierade formatet (Day, Month DD, YYYY för engelska). |
| [getDateTime3()](#getDateTime3--) | Aktuellt datum och tid i det tredje fördefinierade formatet (DD Month YYYY för engelska). |
| [getDateTime4()](#getDateTime4--) | Aktuellt datum och tid i det fjärde fördefinierade formatet (Month DD, YYYY för engelska). |
| [getDateTime5()](#getDateTime5--) | Aktuellt datum och tid i det femte fördefinierade formatet (DD-Mon-YY för engelska). |
| [getDateTime6()](#getDateTime6--) | Aktuellt datum och tid i det sjätte fördefinierade formatet (Month YY för engelska). |
| [getDateTime7()](#getDateTime7--) | Aktuellt datum och tid i det sjunde fördefinierade formatet (Mon-YY för engelska). |
| [getDateTime8()](#getDateTime8--) | Aktuellt datum och tid i det åttonde fördefinierade formatet (MM/DD/YYYY hh:mm AM/PM för engelska). |
| [getDateTime9()](#getDateTime9--) | Aktuellt datum och tid i det nionde fördefinierade formatet (MM/DD/YYYY hh:mm:ss AM/PM för engelska). |
| [getDateTime10()](#getDateTime10--) | Aktuellt datum och tid i det tionde fördefinierade formatet (hh:mm för engelska). |
| [getDateTime11()](#getDateTime11--) | Aktuellt datum och tid i det elfte fördefinierade formatet (hh:mm:ss för engelska). |
| [getDateTime12()](#getDateTime12--) | Aktuellt datum och tid i det tolfte fördefinierade formatet (hh:mm AM/PM för engelska). |
| [getDateTime13()](#getDateTime13--) | Aktuellt datum och tid i det trettonde fördefinierade formatet (hh:mm:ss AM/PM för engelska). |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

Initierar en ny instans av klassen FieldType.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

Returnerar det interna namnet för detta FieldType-objekt. Läs/skriv String.

**Returnerar:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

Returnerar det interna namnet för detta FieldType-objekt. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kontrollerar om detta fält är lika med ett annat.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Fält att jämföra. |

**Returnerar:**
boolean - Sant om fälten är lika.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Returnerar hashkod för detta objekt.

**Returnerar:**
int - Hashkod int.

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

Kontrollerar om två FieldType-objekt är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Första FieldType att jämföra. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Andra FieldType att jämföra. |

**Returnerar:**
boolean - Sant om FieldType-objekten är lika.

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

Kontrollerar om två FieldType-objekt är olika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Första FieldType att jämföra. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Andra FieldType att jämföra. |

**Returnerar:**
boolean - Sant om FieldType-objekten inte är lika.

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

Aktuellt bildnummer. Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

Bildens sidfot. Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

Bildens sidhuvud. Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

Aktuellt datum och tid i standarddatumformat för renderingsapplikationen. Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

Aktuellt datum och tid i det första fördefinierade formatet (MM/DD/YYYY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

Aktuellt datum och tid i det andra fördefinierade formatet (Day, Month DD, YYYY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

Aktuellt datum och tid i det tredje fördefinierade formatet (DD Month YYYY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

Aktuellt datum och tid i det fjärde fördefinierade formatet (Month DD, YYYY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

Aktuellt datum och tid i det femte fördefinierade formatet (DD-Mon-YY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

Aktuellt datum och tid i det sjätte fördefinierade formatet (Month YY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

Aktuellt datum och tid i det sjunde fördefinierade formatet (Mon-YY för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

Aktuellt datum och tid i det åttonde fördefinierade formatet (MM/DD/YYYY hh:mm AM/PM för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

Aktuellt datum och tid i det nionde fördefinierade formatet (MM/DD/YYYY hh:mm:ss AM/PM för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

Aktuellt datum och tid i det tionde fördefinierade formatet (hh:mm för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

Aktuellt datum och tid i det elfte fördefinierade formatet (hh:mm:ss för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

Aktuellt datum och tid i det tolfte fördefinierade formatet (hh:mm AM/PM för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

Aktuellt datum och tid i det trettonde fördefinierade formatet (hh:mm:ss AM/PM för engelska). Skrivskyddad [FieldType](../../com.aspose.slides/fieldtype).

**Returnerar:**
[FieldType](../../com.aspose.slides/fieldtype)