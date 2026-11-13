---
title: CachedChartValue
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een gecachte chartwaarde voor, bijv. X, Y, bubbelformaat of de hoofdwaarde.
type: docs
url: /nl/com.aspose.slides/cachedchartvalue/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Stelt een gecachte chartwaarde voor (bijv. X, Y, bubbelformaat, of de hoofdwaarde).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [toString()](#toString--) | Retourneert een tekenreeksrepresentatie van de gecachte waarde. |
| [toDouble()](#toDouble--) | Converteert de gecachte waarde naar een double. |
| [getData()](#getData--) | Haalt het gecachte dataobject op. |

### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

Retourneert een tekenreeksrepresentatie van de gecachte waarde.

**Retour:**
java.lang.String

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Converteert de gecachte waarde naar een double.

**Retour:**
double - De numerieke representatie, of Double.NaN als Data (\#getData.getData/\#setData(Object).setData(Object)) null is of niet kan worden omgezet naar een double.

### getData() {#getData--}
```
public final Object getData()
```

Haalt het gecachte dataobject op. Alleen-lezen  Object .

**Retour:**
java.lang.Object