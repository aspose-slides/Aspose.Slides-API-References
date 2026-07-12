---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API Reference
description: Ábrázolja az animációs viselkedés tulajdonságtípusait.
type: docs
url: /hu/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Ábrázolja az animációs viselkedés tulajdonságtípusait. Kövesse a tulajdonságok listáját a https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx és https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx címekről
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getValue()](#getValue--) | A tulajdonság értéke |
| [isCustom()](#isCustom--) | Megjeleníti, ha ez a tulajdonság nem tartozik a specifikáció előre definiált tulajdonságlistájához: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
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


Megjeleníti, ha ez a tulajdonság nem tartozik a specifikáció előre definiált tulajdonságlistájához: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Visszatér:**
boolean