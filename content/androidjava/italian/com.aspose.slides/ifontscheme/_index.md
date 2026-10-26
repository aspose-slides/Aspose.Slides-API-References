---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Stores theme-defined fonts.
type: docs
url: /it/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Memorizza i caratteri definiti dal tema.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMinor()](#getMinor--) | Restituisce la raccolta di caratteri per la parte "body" della diapositiva. |
| [getMajor()](#getMajor--) | Restituisce la raccolta di caratteri per la parte "heading" della diapositiva. |
| [getName()](#getName--) | Restituisce il nome dello schema di caratteri. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce il nome dello schema di caratteri. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Restituisce la raccolta di caratteri per la parte "body" della diapositiva. Solo lettura [IFonts](../../com.aspose.slides/ifonts).

**Restituisce:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Restituisce la raccolta di caratteri per la parte "heading" della diapositiva. Solo lettura [IFonts](../../com.aspose.slides/ifonts).

**Restituisce:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Restituisce il nome dello schema di caratteri. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Restituisce il nome dello schema di caratteri. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
