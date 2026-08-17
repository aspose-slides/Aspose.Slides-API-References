---
title: ISlideText
second_title: Aspose.Slides for Java API Referansı
description: Slayttan çıkarılan metni temsil eder
type: docs
url: /tr/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Slayttan çıkarılan metni temsil eder
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getText()](#getText--) | Slaydın şekillerindeki metin |
| [getMasterText()](#getMasterText--) | Bu slayt için ana sayfanın şekillerindeki metin |
| [getLayoutText()](#getLayoutText--) | Bu slayt için düzen sayfasının şekillerindeki metin |
| [getNotesText()](#getNotesText--) | Bu slayt için not sayfasının şekillerindeki metin |
| [getCommentsText()](#getCommentsText--) | Slayt yorumlarının metni |
### getText() {#getText--}
```
public abstract String getText()
```

Slaydın şekillerindeki metin

**Döndürür:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

Bu slayt için ana sayfanın şekillerindeki metin

**Döndürür:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

Bu slayt için düzen sayfasının şekillerindeki metin

**Döndürür:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

Bu slayt için not sayfasının şekillerindeki metin

**Döndürür:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

Slayt yorumlarının metni

--------------------

Metin Arranged mode kullanılarak çıkarıldığında bu alan boştur.

**Döndürür:**
java.lang.String