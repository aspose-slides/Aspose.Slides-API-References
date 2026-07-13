---
title: IAutoShape
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un'AutoShape.
type: docs
url: /it/com.aspose.slides/iautoshape/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Rappresenta un'AutoShape.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Restituisce i blocchi di AutoShape. |
| [getTextFrame()](#getTextFrame--) | Restituisce l'oggetto TextFrame per l'AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Aggiunge un nuovo TextFrame a una forma. |
| [isTextBox()](#isTextBox--) | Specifica se la forma è una casella di testo. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Restituisce i blocchi di AutoShape. Solo lettura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Restituisce:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Restituisce l'oggetto TextFrame per l'AutoShape. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. Booleano di lettura/scrittura.

**Restituisce:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. Booleano di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Aggiunge un nuovo TextFrame a una forma. Se la forma ha già un TextFrame, allora cambia semplicemente il suo testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo predefinito per un nuovo TextFrame. |

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe) - Nuovo oggetto [ITextFrame](../../com.aspose.slides/itextframe).
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Specifica se la forma è una casella di testo.

--------------------

Se la forma non è specificata come casella di testo non significa che non possa avere del testo associato. Una casella di testo è semplicemente una forma specializzata con proprietà specifiche.

**Restituisce:**
boolean