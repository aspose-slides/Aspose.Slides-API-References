---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
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
| [getMinor()](#getMinor--) | Vrací kolekci písem pro část "body" snímku. |
| [getMajor()](#getMajor--) | Vrací kolekci písem pro část "heading" snímku. |
| [getName()](#getName--) | Vrací název schématu písem. |
| [setName(String value)](#setName-java.lang.String-) | Vrací název schématu písem. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Vrací kolekci písem pro část "body" snímku. Pouze pro čtení [IFonts](../../com.aspose.slides/ifonts).

**Vrací:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Vrací kolekci písem pro část "heading" snímku. Pouze pro čtení [IFonts](../../com.aspose.slides/ifonts).

**Vrací:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Vrací název schématu písem. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Vrací název schématu písem. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |