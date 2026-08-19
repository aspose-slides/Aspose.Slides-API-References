---
title: FontScheme
second_title: Riferimento API di Aspose.Slides per Java
description: Memorizza i caratteri definiti dal tema.
type: docs
url: /it/com.aspose.slides/fontscheme/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

Memorizza i caratteri definiti dal tema.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMinor()](#getMinor--) | Restituisce la raccolta di caratteri per una parte "body" della diapositiva. |
| [getMajor()](#getMajor--) | Restituisce la raccolta di caratteri per una parte "heading" della diapositiva. |
| [getName()](#getName--) | Restituisce il nome dello schema di caratteri. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce il nome dello schema di caratteri. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```


Restituisce la raccolta di caratteri per una parte "body" della diapositiva. Solo lettura [IFonts](../../com.aspose.slides/ifonts).

**Restituisce:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```


Restituisce la raccolta di caratteri per una parte "heading" della diapositiva. Solo lettura [IFonts](../../com.aspose.slides/ifonts).

**Restituisce:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome dello schema di caratteri. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Restituisce il nome dello schema di caratteri. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject