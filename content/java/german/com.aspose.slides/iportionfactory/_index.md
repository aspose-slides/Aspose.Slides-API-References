---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Ermöglicht das Erstellen von Test Portionen
type: docs
url: /de/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Ermöglicht das Erstellen von Test Portionen

--------------------

Für COM-Kompatibilität

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createPortion()](#createPortion--) | Erstellt einen leeren Text Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Erstellt einen Text Portion aus dem angegebenen String. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Erstellt einen Portion mit der Verwendung der angegebenen Portiondaten. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Erstellt einen leeren Text Portion.

**Rückgabewert:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Erstellt einen Text Portion aus dem angegebenen String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | java.lang.String | String. |

**Rückgabewert:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Erstellt einen Portion mit der Verwendung der angegebenen Portiondaten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Ein Portion, der verwendet werden soll. |

**Rückgabewert:**
[IPortion](../../com.aspose.slides/iportion) - Portion.