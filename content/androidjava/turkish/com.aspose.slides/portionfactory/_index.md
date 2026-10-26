---
title: PortionFactory
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Test bölümleri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/portionfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Test bölümleri oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Boş bir metin bölümü oluşturur.

**Dönüş:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Belirtilen dizeden bir metin bölümü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String | Dize. |

**Dönüş:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Belirtilen bölüm verisi kullanılarak bir bölüm oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Kullanılacak bir bölüm. |

**Dönüş:**
[IPortion](../../com.aspose.slides/iportion) - Portion.