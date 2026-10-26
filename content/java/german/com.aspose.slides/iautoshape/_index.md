---
title: IAutoShape
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine AutoShape dar.
type: docs
url: /de/com.aspose.slides/iautoshape/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Stellt eine AutoShape dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Gibt die Sperren der AutoShape zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt das TextFrame-Objekt für die AutoShape zurück. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bestimmt, ob diese AutoShape mit dem Hintergrundfüllung der Folie anstelle von durch Stil oder Füllformat angegeben gefüllt werden soll. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bestimmt, ob diese AutoShape mit dem Hintergrundfüllung der Folie anstelle von durch Stil oder Füllformat angegeben gefüllt werden soll. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Fügt einem Shape ein neues TextFrame hinzu. |
| [isTextBox()](#isTextBox--) | Gibt an, ob das Shape ein Textfeld ist. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

Gibt die Sperren der AutoShape zurück. Nur lesbar [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Rückgabewert:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Gibt das TextFrame-Objekt für die AutoShape zurück. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabewert:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

Bestimmt, ob diese AutoShape mit dem Hintergrundfüllung der Folie anstelle von durch Stil oder Füllformat angegeben gefüllt werden soll. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Bestimmt, ob diese AutoShape mit dem Hintergrundfüllung der Folie anstelle von durch Stil oder Füllformat angegeben gefüllt werden soll. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Fügt einem Shape ein neues TextFrame hinzu. Wenn das Shape bereits ein TextFrame hat, wird einfach dessen Text geändert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Standardtext für ein neues TextFrame. |

**Rückgabewert:**
[ITextFrame](../../com.aspose.slides/itextframe) - Neues [ITextFrame](../../com.aspose.slides/itextframe)-Objekt.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Gibt an, ob das Shape ein Textfeld ist.

--------------------

Wenn ein Shape nicht als Textfeld festgelegt ist, bedeutet das nicht, dass es keinen Text enthalten kann. Ein Textfeld ist lediglich ein spezialisierter Shape mit bestimmten Eigenschaften.

**Rückgabewert:**
boolean