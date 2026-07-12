---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Stores theme-defined fonts.
type: docs
url: /tr/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Tema tarafından tanımlanan yazı tiplerini saklar.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getMinor()](#getMinor--) | Slaytın "body" bölümüne ait yazı tipi koleksiyonunu döndürür. |
| [getMajor()](#getMajor--) | Slaytın "heading" bölümüne ait yazı tipi koleksiyonunu döndürür. |
| [getName()](#getName--) | Yazı tipi şeması adını döndürür. |
| [setName(String value)](#setName-java.lang.String-) | Yazı tipi şeması adını döndürür. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Slaytın "body" bölümüne ait yazı tipi koleksiyonunu döndürür. Yalnızca okuma [IFonts](../../com.aspose.slides/ifonts).

**Döndürür:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Slaytın "heading" bölümüne ait yazı tipi koleksiyonunu döndürür. Yalnızca okuma [IFonts](../../com.aspose.slides/ifonts).

**Döndürür:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Yazı tipi şeması adını döndürür. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Yazı tipi şeması adını döndürür. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |