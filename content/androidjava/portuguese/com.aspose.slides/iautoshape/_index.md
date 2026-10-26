---
title: IAutoShape
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa um AutoShape.
type: docs
url: /pt/com.aspose.slides/iautoshape/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Representa um AutoShape.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Retorna os bloqueios do AutoShape. |
| [getTextFrame()](#getTextFrame--) | Retorna o objeto TextFrame para o AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de especificado por estilo ou formato de preenchimento. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de especificado por estilo ou formato de preenchimento. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adiciona um novo TextFrame a uma forma. |
| [isTextBox()](#isTextBox--) | Especifica se a forma é uma caixa de texto. |
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


Adiciona um novo TextFrame a uma forma. Se a forma já tem TextFrame, então simplesmente altera seu texto.

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

Se a forma não for especificada como caixa de texto, isso não significa que ela não pode ter texto associado a ela. Uma caixa de texto é apenas uma forma especializada com propriedades específicas.

**Retorna:**
boolean