---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API Reference
description: Represent property types for animation behavior.
type: docs
url: /tr/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Animasyon davranışı için özellik türlerini temsil eder. Özelliklerin listesini şu adreslerden alır: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx ve https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Özelliğin değeri |
| [isCustom()](#isCustom--) | Bu özelliğin, spec'de önceden tanımlanmış özellikler listesine ait olup olmadığını gösterir: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |

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

Bu özelliğin, spec'de önceden tanımlanmış özellikler listesine ait olup olmadığını gösterir: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Döndürür:**
boolean