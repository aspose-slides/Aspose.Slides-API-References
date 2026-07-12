---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Stores theme-defined fonts.
type: docs
url: /de/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Speichert themendefinierte Schriftarten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMinor()](#getMinor--) | Gibt die Schriftartensammlung für den "body"-Teil der Folie zurück. |
| [getMajor()](#getMajor--) | Gibt die Schriftartensammlung für den "heading"-Teil der Folie zurück. |
| [getName()](#getName--) | Gibt den Namen des Schriftartenschemas zurück. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen des Schriftartenschemas zurück. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Gibt die Schriftartensammlung für den "body"-Teil der Folie zurück. Nur lesbar [IFonts](../../com.aspose.slides/ifonts).

**Rückgabe:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Gibt die Schriftartensammlung für den "heading"-Teil der Folie zurück. Nur lesbar [IFonts](../../com.aspose.slides/ifonts).

**Rückgabe:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Gibt den Namen des Schriftartenschemas zurück. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Gibt den Namen des Schriftartenschemas zurück. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |