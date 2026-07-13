---
title: IAutoShape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en AutoShape.
type: docs
url: /sv/com.aspose.slides/iautoshape/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Representerar en AutoShape.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returnerar AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returnerar TextFrame object för AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bestämmer om detta autoshape ska fyllas med bildens bakgrundsfyllning istället för specificerad av stil eller fyllningsformat. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bestämmer om detta autoshape ska fyllas med bildens bakgrundsfyllning istället för specificerad av stil eller fyllningsformat. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Lägger till en ny TextFrame till en form. |
| [isTextBox()](#isTextBox--) | Anger om formen är en textruta. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Returnerar AutoShape's locks. Skrivskyddad [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returnerar:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Returnerar TextFrame object för AutoShape. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Bestämmer om detta autoshape ska fyllas med bildens bakgrundsfyllning istället för specificerad av stil eller fyllningsformat. Läs/skriv boolean.

**Returnerar:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Bestämmer om detta autoshape ska fyllas med bildens bakgrundsfyllning istället för specificerad av stil eller fyllningsformat. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Lägger till en ny TextFrame till en form. Om formen redan har TextFrame ändras dess text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Standardtext för en ny TextFrame. |

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe) - Ny [ITextFrame](../../com.aspose.slides/itextframe)-objekt.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Anger om formen är en textruta.

--------------------

Om en form inte specificeras som en textruta betyder det inte att den inte kan ha text kopplad till sig. En textruta är bara en specialiserad form med specifika egenskaper.

**Returnerar:**
boolean