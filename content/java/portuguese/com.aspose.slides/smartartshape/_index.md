---
title: SmartArtShape
second_title: Referência da API Aspose.Slides para Java
description: Representa forma SmartArt
type: docs
url: /pt/com.aspose.slides/smartartshape/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Representa forma SmartArt
## Métodos

| Método | Descrição |
| --- | --- |
| [getShapeType()](#getShapeType--) | Retorna ou define o tipo predefinido de geometria. |
| [setShapeType(int value)](#setShapeType-int-) | Retorna ou define o tipo predefinido de geometria. |
| [getTextFrame()](#getTextFrame--) | Retorna o texto da forma SmartArt. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Retorna ou define o tipo predefinido de geometria. Observação: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Leitura/Gravação [ShapeType](../../com.aspose.slides/shapetype).

**Retorna:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Retorna ou define o tipo predefinido de geometria. Observação: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Leitura/Gravação [ShapeType](../../com.aspose.slides/shapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retorna o texto da forma SmartArt. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)