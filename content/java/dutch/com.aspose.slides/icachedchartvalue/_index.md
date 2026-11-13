---
title: ICachedChartValue
second_title: Aspose.Slides for Java API-referentie
description: Vertegenwoordigt een gecachte diagramwaarde b.v. X Y bubbelgrootte of de hoofdwaarde.
type: docs
url: /nl/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Vertegenwoordigt een gecachte diagramwaarde (bijv., X, Y, bubbelgrootte, of de hoofdwaarde).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getData()](#getData--) | Haalt het gecachte gegevensobject op. |
| [toDouble()](#toDouble--) | Converteert de gecachte waarde naar een double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Haalt het gecachte gegevensobject op. Alleen-lezen  Object .

**Returns:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converteert de gecachte waarde naar een double.

**Returns:**
double - De numerieke weergave, of Double.NaN als Data (\#getData.getData) null is of niet kan worden geconverteerd naar een double.