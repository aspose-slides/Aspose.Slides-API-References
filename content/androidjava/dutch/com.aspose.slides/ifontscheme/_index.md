---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Slaat themadefinieerde lettertypen op.
type: docs
url: /nl/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Slaat themadefinieerde lettertypen op.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMinor()](#getMinor--) | Retourneert de lettertypecollectie voor een "body"-deel van de dia. |
| [getMajor()](#getMajor--) | Retourneert de lettertypecollectie voor een "heading"-deel van de dia. |
| [getName()](#getName--) | Retourneert de naam van het lettertype-schema. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert de naam van het lettertype-schema. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Retourneert de lettertypecollectie voor een "body"-deel van de dia. Alleen-lezen [IFonts](../../com.aspose.slides/ifonts).

**Retourneert:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Retourneert de lettertypecollectie voor een "heading"-deel van de dia. Alleen-lezen [IFonts](../../com.aspose.slides/ifonts).

**Retourneert:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Retourneert de naam van het lettertype-schema. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Retourneert de naam van het lettertype-schema. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |