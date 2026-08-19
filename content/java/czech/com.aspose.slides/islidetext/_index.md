---
title: ISlideText
second_title: Aspose.Slides pro Java – reference API
description: Representuje text extrahovaný ze snímku
type: docs
url: /cs/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Representuje text extrahovaný ze snímku
## Metody

| Metoda | Popis |
| --- | --- |
| [getText()](#getText--) | Text na tvarech snímku |
| [getMasterText()](#getMasterText--) | Text na tvarech hlavní stránky pro tento snímek |
| [getLayoutText()](#getLayoutText--) | Text na tvarech rozvržení stránky pro tento snímek |
| [getNotesText()](#getNotesText--) | Text na tvarech stránky poznámek pro tento snímek |
| [getCommentsText()](#getCommentsText--) | Text komentářů snímku |
### getText() {#getText--}
```
public abstract String getText()
```


Text na tvarech snímku

**Vrací:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Text na tvarech hlavní stránky pro tento snímek

**Vrací:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Text na tvarech rozvržení stránky pro tento snímek

**Vrací:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Text na tvarech stránky poznámek pro tento snímek

**Vrací:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Text komentářů snímku

--------------------

Toto pole je prázdné, pokud je text extrahován pomocí režimu Arranged.

**Vrací:**
java.lang.String