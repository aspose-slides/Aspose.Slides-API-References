---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Reprezentál egy gyorsítótárazott diagramértéket, például X, Y, buborékméret vagy a fő érték.
type: docs
url: /hu/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Reprezentál egy gyorsítótárazott diagramértéket (például X, Y, buborékméret vagy a fő érték).
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getData()](#getData--) | Lekéri a gyorsítótárazott adatobjektumot. |
| [toDouble()](#toDouble--) | Átalakítja a gyorsítótárazott értéket double típusúvá. |
### getData() {#getData--}
```
public abstract Object getData()
```


Lekéri a gyorsítótárazott adatobjektumot. Csak olvasható  Object .

**Visszatérési érték:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Átalakítja a gyorsítótárazott értéket double típusúvá.

**Visszatérési érték:**
double - A numerikus ábrázolás, vagy Double.NaN, ha a Data (\#getData.getData) null, vagy nem konvertálható double típusúra.