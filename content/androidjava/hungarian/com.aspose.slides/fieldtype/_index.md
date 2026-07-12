---
title: FieldType
second_title: Aspose.Slides Androidhoz Java API Referencia
description: Egy mező típusát képviseli.
type: docs
url: /hu/com.aspose.slides/fieldtype/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

Egy mező típusát képviseli. Ez az érték határozza meg, hogy milyen szöveg lesz beállítva a mező részére, amikor frissül.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | Új példányt inicializál a FieldType osztályból. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInternalString()](#getInternalString--) | Visszaadja ennek a FieldType objektumnak a belső nevét. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | Visszaadja ennek a FieldType objektumnak a belső nevét. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ellenőrzi, hogy ez a mező egyenlő-e egy másikkal. |
| [hashCode()](#hashCode--) | Visszaadja ennek az objektumnak a hashkódját. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Ellenőrzi, hogy két FieldType objektum egyenlő-e. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Ellenőrzi, hogy két FieldType objektum nem egyenlő-e. |
| [getSlideNumber()](#getSlideNumber--) | Az aktuális dia száma. |
| [getFooter()](#getFooter--) | Dia lábléc. |
| [getHeader()](#getHeader--) | Dia fejléc. |
| [getDateTime()](#getDateTime--) | Az aktuális dátum és idő az alapértelmezett dátum-idő formátumban a megjelenítő alkalmazás számára. |
| [getDateTime1()](#getDateTime1--) | Az aktuális dátum és idő az első előre meghatározott formátumban (MM/DD/YYYY angol nyelven). |
| [getDateTime2()](#getDateTime2--) | Az aktuális dátum és idő a második előre meghatározott formátumban (Day, Month DD, YYYY angol nyelven). |
| [getDateTime3()](#getDateTime3--) | Az aktuális dátum és idő a harmadik előre meghatározott formátumban (DD Month YYYY angol nyelven). |
| [getDateTime4()](#getDateTime4--) | Az aktuális dátum és idő a negyedik előre meghatározott formátumban (Month DD, YYYY angol nyelven). |
| [getDateTime5()](#getDateTime5--) | Az aktuális dátum és idő az ötödik előre meghatározott formátumban (DD-Mon-YY angol nyelven). |
| [getDateTime6()](#getDateTime6--) | Az aktuális dátum és idő a hatodik előre meghatározott formátumban (Month YY angol nyelven). |
| [getDateTime7()](#getDateTime7--) | Az aktuális dátum és idő a hetedik előre meghatározott formátumban (Mon-YY angol nyelven). |
| [getDateTime8()](#getDateTime8--) | Az aktuális dátum és idő a nyolcadik előre meghatározott formátumban (MM/DD/YYYY hh:mm AM/PM angol nyelven). |
| [getDateTime9()](#getDateTime9--) | Az aktuális dátum és idő a kilencedik előre meghatározott formátumban (MM/DD/YYYY hh:mm:ss AM/PM angol nyelven). |
| [getDateTime10()](#getDateTime10--) | Az aktuális dátum és idő a tizedik előre meghatározott formátumban (hh:mm angol nyelven). |
| [getDateTime11()](#getDateTime11--) | Az aktuális dátum és idő a tizenegyedik előre meghatározott formátumban (hh:mm:ss angol nyelven). |
| [getDateTime12()](#getDateTime12--) | Az aktuális dátum és idő a tizenkettedik előre meghatározott formátumban (hh:mm AM/PM angol nyelven). |
| [getDateTime13()](#getDateTime13--) | Az aktuális dátum és idő a tizenharmadik előre meghatározott formátumban (hh:mm:ss AM/PM angol nyelven). |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

Új példányt inicializál a FieldType osztályból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

Visszaadja ennek a FieldType objektumnak a belső nevét. Olvasható/írható String.

**Visszatérési érték:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

Visszaadja ennek a FieldType objektumnak a belső nevét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ellenőrzi, hogy ez a mező egyenlő-e egy másikkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Összehasonlítandó mező. |

**Visszatérési érték:**
boolean - Igaz, ha a mezők egyenlőek.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Visszaadja ennek az objektumnak a hashkódját.

**Visszatérési érték:**
int - Hashkód int.

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

Ellenőrzi, hogy két FieldType objektum egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Az első összehasonlítandó FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | A második összehasonlítandó FieldType. |

**Visszatérési érték:**
boolean - Igaz, ha a FieldType objektumok egyenlőek.

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

Ellenőrzi, hogy két FieldType objektum nem egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Az első összehasonlítandó FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | A második összehasonlítandó FieldType. |

**Visszatérési érték:**
boolean - Igaz, ha a FieldType objektumok nem egyenlőek.

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

Az aktuális dia száma. Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

Dia lábléc. Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

Dia fejléc. Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

Az aktuális dátum és idő az alapértelmezett dátum-idő formátumban a megjelenítő alkalmazás számára. Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldName getDateTime1()
```

Az aktuális dátum és idő az első előre meghatározott formátumban (MM/DD/YYYY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

Az aktuális dátum és idő a második előre meghatározott formátumban (Day, Month DD, YYYY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

Az aktuális dátum és idő a harmadik előre meghatározott formátumban (DD Month YYYY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

Az aktuális dátum és idő a negyedik előre meghatározott formátumban (Month DD, YYYY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

Az aktuális dátum és idő az ötödik előre meghatározott formátumban (DD-Mon-YY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

Az aktuális dátum és idő a hatodik előre meghatározott formátumban (Month YY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

Az aktuális dátum és idő a hetedik előre meghatározott formátumban (Mon-YY angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

Az aktuális dátum és idő a nyolcadik előre meghatározott formátumban (MM/DD/YYYY hh:mm AM/PM angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

Az aktuális dátum és idő a kilencedik előre meghatározott formátumban (MM/DD/YYYY hh:mm:ss AM/PM angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

Az aktuális dátum és idő a tizedik előre meghatározott formátumban (hh:mm angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

Az aktuális dátum és idő a tizenegyedik előre meghatározott formátumban (hh:mm:ss angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

Az aktuális dátum és idő a tizenkettedik előre meghatározott formátumban (hh:mm AM/PM angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

Az aktuális dátum és idő a tizenharmadik előre meghatározott formátumban (hh:mm:ss AM/PM angol nyelven). Csak olvasható [FieldType](../../com.aspose.slides/fieldtype).

**Visszatérési érték:**
[FieldType](../../com.aspose.slides/fieldtype)