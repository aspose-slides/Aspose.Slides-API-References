---
title: PortionFactory
second_title: Aspose.Slides için Java API Referansı
description: Test bölümleri oluşturulmasına izin verir
type: docs
url: /tr/com.aspose.slides/portionfactory/
---
**Miras:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Test bölümleri oluşturulmasına izin verir

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createPortion()](#createPortion--) | Boş bir metin bölümü oluşturur. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Belirtilen dizeden bir metin bölümü oluşturur. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Belirtilen bölüm verisini kullanarak bir bölüm oluşturur. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Boş bir metin bölümü oluşturur.

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Belirtilen dizeden bir metin bölümü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String | String. |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Belirtilen bölüm verisini kullanarak bir bölüm oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Kullanılacak bir bölüm. |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Portion.