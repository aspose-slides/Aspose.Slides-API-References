---
title: ITabEffectiveData
second_title: Aspose.Slides für Android über Java API Referenz
description: Unveränderliches Objekt, das die Tabulationsstopp-Eigenschaften des effektiven Textes enthält.
type: docs
url: /de/com.aspose.slides/itabeffectivedata/
---
**Alle implementierten Schnittstellen:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Unveränderliches Objekt, das die Tabulatorstopp-Eigenschaften des effektiven Textes enthält.

--------------------

Dieses Interface wird als Teil von [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPosition()](#getPosition--) | Gibt die Position eines Tabulators zurück. |
| [getAlignment()](#getAlignment--) | Gibt den Ausrichtungsstil eines Tabulators zurück. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

Gibt die Position eines Tabulators zurück. Das Zuweisen dieser Eigenschaft kann den Index des Tabulators in der Sammlung ändern und den Enumerator ungültig machen. Nur lesbar double.

**Rückgabe:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Gibt den Ausrichtungsstil eines Tabulators zurück. Nur lesbar [TabAlignment](../../com.aspose.slides/tabalignment).

**Rückgabe:**
int