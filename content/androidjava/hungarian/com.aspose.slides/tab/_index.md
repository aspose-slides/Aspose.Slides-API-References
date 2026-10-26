---
title: Tab
second_title: Aspose.Slides Androidhoz Java API referenciája
description: Szöveghez tartozó tabulációt képvisel.
type: docs
url: /hu/com.aspose.slides/tab/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Egy szöveghez tartozó tabulációt képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Új Tabot hoz létre |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja egy tab pozícióját. |
| [setPosition(double value)](#setPosition-double-) | Visszaadja vagy beállítja egy tab pozícióját. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja egy tab igazítási stílusát. |
| [setAlignment(int value)](#setAlignment-int-) | Visszaadja vagy beállítja egy tab igazítási stílusát. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Összehasonlítja a jelenlegi példányt egy azonos típusú másik objektummal. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Új Tabot hoz létre

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | double | Tab pozíciója. |
| align | int | Igazítás. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Visszaadja vagy beállítja egy tab pozícióját. Ennek a tulajdonságnak a beállítása megváltoztathatja a tab indexét a gyűjteményben és érvénytelenítheti a Enumerator-t. Olvasható/írható double.

**Visszatérési érték:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Visszaadja vagy beállítja egy tab pozícióját. Ennek a tulajdonságnak a beállítása megváltoztathatja a tab indexét a gyűjteményben és érvénytelenítheti a Enumerator-t. Olvasható/írható double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Visszaadja vagy beállítja egy tab igazítási stílusát. Olvasható/írható [TabAlignment](../../com.aspose.slides/tabalignment).

**Visszatérési érték:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Visszaadja vagy beállítja egy tab igazítási stílusát. Olvasható/írható [TabAlignment](../../com.aspose.slides/tabalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Összehasonlítja a jelenlegi példányt egy azonos típusú másik objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Egy objektum, amellyel összehasonlítja ezt a példányt. |

**Visszatérési érték:**
int - 32 bites egész szám, amely a hasonlítandók relatív sorrendjét jelzi. A visszatérési érték a következő jelentésekkel rendelkezik: 

 *  < 0 - Ez a példány kisebb, mint az obj.
 *  = 0 - Ez a példány egyenlő az obj.
 *  > 0 - Ez a példány nagyobb, mint az obj.