---
title: Tab
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje tabulaci pro text.
type: docs
url: /cs/com.aspose.slides/tab/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Reprezentuje tabulátor pro text.
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

Verze. Pouze pro čtení long.

**Vrací:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Vrací nebo nastavuje pozici tabulátoru. Při přiřazení této vlastnosti může změnit index tabulátoru ve sbírce a neplatnit Enumerator. Čtení/zápis double.

**Vrací:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Vrací nebo nastavuje pozici tabulátoru. Při přiřazení této vlastnosti může změnit index tabulátoru ve sbírce a neplatnit Enumerator. Čtení/zápis double.

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
| obj | java.lang.Object | Objekt, který se má porovnat s touto instancí. |

**Vrací:**
int - 32-bitové celé číslo, které určuje relativní pořadí porovnávaných objektů. Návratová hodnota má následující významy: 

 *  < 0 - Tato instance je menší než obj.
 *  = 0 - Tato instance je rovna obj.
 *  > 0 - Tato instance je větší než obj.