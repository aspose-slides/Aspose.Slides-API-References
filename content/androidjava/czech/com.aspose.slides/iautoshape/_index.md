---
title: IAutoShape
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Reprezentuje AutoShape.
type: docs
url: /cs/com.aspose.slides/iautoshape/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Reprezentuje AutoShape.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Vrací AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Vrací objekt TextFrame pro AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Určuje, zda by tento autoshape měl být vyplněn slide's background fill místo výplně určené stylem nebo formátem výplně. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Určuje, zda by tento autoshape měl být vyplněn slide's background fill místo výplně určené stylem nebo formátem výplně. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Přidá nový TextFrame do tvaru. |
| [isTextBox()](#isTextBox--) | Určuje, zda je tvar textovým polem. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Vrací AutoShape's locks. Pouze pro čtení [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Vrací:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Vrací objekt TextFrame pro AutoShape. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Určuje, zda by tento autoshape měl být vyplněn slide's background fill místo výplně určené stylem nebo formátem výplně. Boolean čtení/zápis.

**Vrací:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Určuje, zda by tento autoshape měl být vyplněn slide's background fill místo výplně určené stylem nebo formátem výplně. Boolean čtení/zápis.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Přidá nový TextFrame do tvaru. Pokud tvar již obsahuje TextFrame, jednoduše změní jeho text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Výchozí text pro nový TextFrame. |

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe) - New [ITextFrame](../../com.aspose.slides/itextframe) object.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Určuje, zda je tvar textovým polem.

--------------------

Pokud není tvar určen jako textové pole, neznamená to, že nemůže mít k němu připojený text. Textové pole je jen specializovaný tvar se specifickými vlastnostmi.

**Vrací:**
boolean