---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Memorizza i font definiti dal tema.
type: docs
url: /it/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Memorizza i font definiti dal tema.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
| [setName(String value)](#setName-java.lang.String-) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Restituisce la raccolta di font per una parte "body" della diapositiva. Sola lettura [IFonts](../../com.aspose.slides/ifonts).

**Restituisce:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Restituisce la raccolta di font per una parte "heading" della diapositiva. Sola lettura [IFonts](../../com.aspose.slides/ifonts).

**Restituisce:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Restituisce il nome dello schema dei font. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Restituisce il nome dello schema dei font. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |