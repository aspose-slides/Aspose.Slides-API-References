---
title: Tab
second_title: Aspose.Slides pro Java API Reference
description: Představuje tabulaci pro text.
type: docs
url: /cs/com.aspose.slides/tab/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Představuje tabulaci pro text.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Vytvoří nový Tab |
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Vrací nebo nastavuje pozici tabulátoru. |
| [setPosition(double value)](#setPosition-double-) | Vrací nebo nastavuje pozici tabulátoru. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje styl zarovnání tabulátoru. |
| [setAlignment(int value)](#setAlignment-int-) | Vrací nebo nastavuje styl zarovnání tabulátoru. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Porovnává aktuální instanci s jiným objektem stejného typu. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Vytvoří nový Tab

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | double | Pozice tabulátoru. |
| align | int | Zarovnání. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

**Vrací:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Vrací nebo nastavuje pozici tabulátoru. Přiřazení této vlastnosti může změnit index tabulátoru ve sbírce a zneplatnit Enumerator. Čtení/zápis double.

**Vrací:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Vrací nebo nastavuje pozici tabulátoru. Přiřazení této vlastnosti může změnit index tabulátoru ve sbírce a zneplatnit Enumerator. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Vrací nebo nastavuje styl zarovnání tabulátoru. Čtení/zápis [TabAlignment](../../com.aspose.slides/tabalignment).

**Vrací:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Vrací nebo nastavuje styl zarovnání tabulátoru. Čtení/zápis [TabAlignment](../../com.aspose.slides/tabalignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Porovnává aktuální instanci s jiným objektem stejného typu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt pro porovnání s touto instancí. |

**Vrací:**
int - 32bitové celé číslo, které udává relativní pořadí porovnávaných objektů. Návratová hodnota má tyto významy:

 * < 0 – Tato instance je menší než obj.
 * = 0 – Tato instance je rovna obj.
 * > 0 – Tato instance je větší než obj.