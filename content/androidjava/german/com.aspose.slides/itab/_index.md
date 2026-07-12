---
title: ITab
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Tabulation für einen Text dar.
type: docs
url: /de/com.aspose.slides/itab/
---
**Alle implementierten Schnittstellen:**
java.lang.Comparable
```
public interface ITab extends Comparable
```

Stellt eine Tabulation für einen Text dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPosition()](#getPosition--) | Gibt die Position eines Tabulators zurück oder legt sie fest. |
| [setPosition(double value)](#setPosition-double-) | Gibt die Position eines Tabulators zurück oder legt sie fest. |
| [getAlignment()](#getAlignment--) | Gibt den Ausrichtungsstil eines Tabulators zurück oder legt ihn fest. |
| [setAlignment(int value)](#setAlignment-int-) | Gibt den Ausrichtungsstil eines Tabulators zurück oder legt ihn fest. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

Gibt die Position eines Tabulators zurück oder legt sie fest. Das Zuordnen dieser Eigenschaft kann den Index des Tabulators in der Sammlung ändern und den Enumerator ungültig machen. Lesen/Schreiben double.

**Rückgabe:**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```

Gibt die Position eines Tabulators zurück oder legt sie fest. Das Zuordnen dieser Eigenschaft kann den Index des Tabulators in der Sammlung ändern und den Enumerator ungültig machen. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Gibt den Ausrichtungsstil eines Tabulators zurück oder legt ihn fest. Lesen/Schreiben [TabAlignment](../../com.aspose.slides/tabalignment).

**Rückgabe:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Gibt den Ausrichtungsstil eines Tabulators zurück oder legt ihn fest. Lesen/Schreiben [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |