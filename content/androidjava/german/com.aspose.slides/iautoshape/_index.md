---
title: IAutoShape
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein AutoShape dar.
type: docs
url: /de/com.aspose.slides/iautoshape/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Stellt ein AutoShape dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Gibt die AutoShape-Sperren zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt das TextFrame-Objekt für das AutoShape zurück. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bestimmt, ob dieses AutoShape mit dem Folienhintergrund ausgefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bestimmt, ob dieses AutoShape mit dem Folienhintergrund ausgefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Fügt einem Shape ein neues TextFrame hinzu. |
| [isTextBox()](#isTextBox--) | Gibt an, ob das Shape ein Textfeld ist. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Gibt die AutoShape-Sperren zurück. Nur lesbar [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Rückgabe:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Gibt das TextFrame-Objekt für das AutoShape zurück. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Bestimmt, ob dieses AutoShape mit dem Folienhintergrund ausgefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. Lese-/Schreib-Boolean.

**Rückgabe:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Bestimmt, ob dieses AutoShape mit dem Folienhintergrund ausgefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. Lese-/Schreib-Boolean.

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

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe) - Neues [ITextFrame](../../com.aspose.slides/itextframe)-Objekt.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Gibt an, ob das Shape ein Textfeld ist.

--------------------

Wenn ein Shape nicht als Textfeld angegeben ist, bedeutet das nicht, dass ihm kein Text zugeordnet werden kann. Ein Textfeld ist lediglich ein spezialisiertes Shape mit bestimmten Eigenschaften.

**Rückgabe:**
boolean