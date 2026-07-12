---
title: IMasterTheme
second_title: Aspose.Slides Android için Java API Referansı
description: Bir ana tema temsil eder.
type: docs
url: /tr/com.aspose.slides/imastertheme/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Bir ana tema temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Ek renk şemalarının koleksiyonunu döndürür. |
| [getName()](#getName--) | Bir temanın adını döndürür. |
| [setName(String value)](#setName-java.lang.String-) | Bir temanın adını döndürür. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Ek renk şemalarının koleksiyonunu döndürür. Bu şemalar sunumun görünümünü etkilemez, bir slayt için ana renk şeması olarak seçilebilir. Yalnızca okuma [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Döndürür:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Bir temanın adını döndürür. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Bir temanın adını döndürür. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |