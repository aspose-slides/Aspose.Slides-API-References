---
title: IAutoShape
second_title: Referência da API Aspose.Slides para Java
description: Representa um AutoShape.
type: docs
url: /pt/com.aspose.slides/iautoshape/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Representa um AutoShape.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

Retorna os bloqueios do AutoShape. Somente leitura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retorna:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Retorna o objeto TextFrame para o AutoShape. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de especificado por estilo ou formato de preenchimento. Leitura/Gravação boolean.

**Retorna:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de especificado por estilo ou formato de preenchimento. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Adiciona um novo TextFrame a uma forma. Se a forma já possui TextFrame, simplesmente altera seu texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto padrão para um novo TextFrame. |

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe) - Novo objeto [ITextFrame](../../com.aspose.slides/itextframe).
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Especifica se a forma é uma caixa de texto.

--------------------

Se a forma não for especificada como caixa de texto, isso não significa que ela não possa ter texto anexado a ela. Uma caixa de texto é apenas uma forma especializada com propriedades específicas.

**Retorna:**
boolean