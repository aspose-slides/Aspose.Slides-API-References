---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Test parçaları oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Test parçaları oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createPortion()](#createPortion--) | Boş bir metin parçası oluşturur. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Belirtilen dizeden bir metin parçası oluşturur. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Belirtilen parça verisini kullanarak bir parça oluşturur. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Boş bir metin parçası oluşturur.

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Belirtilen dizeden bir metin parçası oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String | String. |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Belirtilen parça verisini kullanarak bir parça oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Kullanılacak bir parça. |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion) - Portion.