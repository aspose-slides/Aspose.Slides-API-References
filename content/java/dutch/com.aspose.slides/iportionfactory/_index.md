---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Staat toe om testgedeelten te maken
type: docs
url: /nl/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Staat toe om testgedeelten te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createPortion()](#createPortion--) | Maakt een leeg tekstgedeelte. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Maakt een tekstgedeelte van een opgegeven String. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Maakt een Portion met het gebruik van gespecificeerde Portion-gegevens. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Maakt een leeg tekstgedeelte.

**Retourneert:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Maakt een tekstgedeelte van een opgegeven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | java.lang.String | String. |

**Retourneert:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Maakt een Portion met het gebruik van gespecificeerde Portion-gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Een Portion om te gebruiken. |

**Retourneert:**
[IPortion](../../com.aspose.slides/iportion) - Portion.