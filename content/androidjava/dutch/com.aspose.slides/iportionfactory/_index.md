---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe testporties te maken
type: docs
url: /nl/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Staat toe testporties te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createPortion()](#createPortion--) | Maakt een lege tekstportie. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Maakt een tekstportie van een opgegeven string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Maakt een portie met gebruik van opgegeven portiegegevens. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Maakt een lege tekstportie.

**Retour:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Maakt een tekstportie van een opgegeven string.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | java.lang.String | String. |

**Retour:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Maakt een portie met gebruik van opgegeven portiegegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Een te gebruiken portie. |

**Retour:**
[IPortion](../../com.aspose.slides/iportion) - Portion.