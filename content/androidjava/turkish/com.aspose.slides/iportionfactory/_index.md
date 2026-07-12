---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Test bölümleri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Test bölümleri oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Boş bir metin bölümü oluşturur.

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Bölüm.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Belirtilen dizeden bir metin bölümü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String | Dize. |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Bölüm.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Belirtilen bölüm verisini kullanarak bir bölüm oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Kullanılacak bir bölüm. |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Bölüm.