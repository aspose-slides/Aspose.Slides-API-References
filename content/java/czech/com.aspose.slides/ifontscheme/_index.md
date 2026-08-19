---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Ukládá písma definovaná motivem.
type: docs
url: /cs/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Ukládá písma definovaná motivem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getMinor()](#getMinor--) | Vrací kolekci fontů pro část "body" snímku. |
| [getMajor()](#getMajor--) | Vrací kolekci fontů pro část "heading" snímku. |
| [getName()](#getName--) | Vrací název schématu fontů. |
| [setName(String value)](#setName-java.lang.String-) | Vrací název schématu fontů. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Vrací kolekci fontů pro část "body" snímku. Pouze ke čtení [IFonts](../../com.aspose.slides/ifonts).

**Vrací:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Vrací kolekci fontů pro část "heading" snímku. Pouze ke čtení [IFonts](../../com.aspose.slides/ifonts).

**Vrací:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Vrací název schématu fontů. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Vrací název schématu fontů. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |