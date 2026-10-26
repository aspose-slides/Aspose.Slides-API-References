---
title: IBehaviorProperty
second_title: Aspose.Slides for Java API Referansı
description: Animasyon davranışı için özellik türlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Animasyon davranışı için özellik türlerini temsil eder. Özelliklerin listesini şu adreslerden izler: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx ve https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Value of the property |
| [isCustom()](#isCustom--) | Shows if this property does not belong to the predefined properties list in the specification: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```

Özelliğin değeri

**Döndürür:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

Bu özelliğin, belirtim içinde önceden tanımlanmış özellikler listesine ait olup olmadığını gösterir: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Döndürür:**
boolean