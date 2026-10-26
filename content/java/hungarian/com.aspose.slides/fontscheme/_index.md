---
title: FontScheme
second_title: Aspose.Slides Java API referencia
description: A téma által meghatározott betűtípusokat tárolja.
type: docs
url: /hu/com.aspose.slides/fontscheme/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

Tárolja a téma által meghatározott betűtípusokat.
## Módszerek

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Visszaadja a diák "body" részéhez tartozó betűtípus-gyűjteményt. |
| [getMajor()](#getMajor--) | Visszaadja a diák "heading" részéhez tartozó betűtípus-gyűjteményt. |
| [getName()](#getName--) | Visszaadja a betűkészlet-séma nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja a betűkészlet-séma nevét. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```

Visszaadja a diák "body" részéhez tartozó betűtípus-gyűjteményt. Csak olvasható [IFonts](../../com.aspose.slides/ifonts).

**Visszatér:**
[IFonts](../../com.aspose.slides/ifonts)

### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```

Visszaadja a diák "heading" részéhez tartozó betűtípus-gyűjteményt. Csak olvasható [IFonts](../../com.aspose.slides/ifonts).

**Visszatér:**
[IFonts](../../com.aspose.slides/ifonts)

### getName() {#getName--}
```
public final String getName()
```

Visszaadja a betűkészlet-séma nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Visszaadja a betűkészlet-séma nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject