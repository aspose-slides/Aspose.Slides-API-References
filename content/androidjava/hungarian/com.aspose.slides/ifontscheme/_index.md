---
title: IFontScheme
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A témában definiált betűtípusokat tárolja.
type: docs
url: /hu/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

A témában definiált betűtípusokat tárolja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getMinor()](#getMinor--) | Visszaadja a diáknak a "body" részéhez tartozó betűtípus-gyűjteményt. |
| [getMajor()](#getMajor--) | Visszaadja a diáknak a "heading" részéhez tartozó betűtípus-gyűjteményt. |
| [getName()](#getName--) | Visszaadja a betűtípus-séma nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja a betűtípus-séma nevét. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Visszaadja a diáknak a "body" részéhez tartozó betűtípus-gyűjteményt. Csak olvasható [IFonts](../../com.aspose.slides/ifonts).

**Visszatérési érték:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Visszaadja a diáknak a "heading" részéhez tartozó betűtípus-gyűjteményt. Csak olvasható [IFonts](../../com.aspose.slides/ifonts).

**Visszatérési érték:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja a betűtípus-séma nevét. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Visszaadja a betűtípus-séma nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |