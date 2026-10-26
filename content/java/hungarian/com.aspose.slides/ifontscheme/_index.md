---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Tárolja a téma által meghatározott betűtípusokat.
type: docs
url: /hu/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Tárolja a téma által meghatározott betűtípusokat.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getMinor()](#getMinor--) | Visszaadja a dia "body" részéhez tartozó betűtípus-gyűjteményt. |
| [getMajor()](#getMajor--) | Visszaadja a dia "heading" részéhez tartozó betűtípus-gyűjteményt. |
| [getName()](#getName--) | Visszaadja a betűtípus-séma nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja a betűtípus-séma nevét. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Visszaadja a dia "body" részéhez tartozó betűtípus-gyűjteményt. Csak olvasható [IFonts](../../com.aspose.slides/ifonts).

**Visszatér:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Visszaadja a dia "heading" részéhez tartozó betűtípus-gyűjteményt. Csak olvasható [IFonts](../../com.aspose.slides/ifonts).

**Visszatér:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja a betűtípus-séma nevét. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Visszaadja a betűtípus-séma nevét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |