---
title: IBehaviorProperty
second_title: Aspose.Slides for Java API Reference
description: Ábrázolja az animációs viselkedés tulajdonságtípusait.
type: docs
url: /hu/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Ábrázolja az animációs viselkedés tulajdonságtípusait. A tulajdonságok listájára támaszkodik a https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx és a https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getValue()](#getValue--) | A tulajdonság értéke |
| [isCustom()](#isCustom--) | Megjeleníti, ha ez a tulajdonság nem szerepel a specifikáció előre definiált tulajdonságlistáján: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```


A tulajdonság értéke

**Visszatér:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Megjeleníti, ha ez a tulajdonság nem tartozik a specifikációban előre definiált tulajdonságlistához: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Visszatér:**
boolean