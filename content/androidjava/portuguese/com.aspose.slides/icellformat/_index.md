---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Representa o formato de uma célula de tabela.
type: docs
url: /pt/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Representa o formato de uma célula de tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retorna um objeto de propriedades de preenchimento de célula. |
| [getBorderLeft()](#getBorderLeft--) | Retorna um objeto de propriedades da linha da borda esquerda. |
| [getBorderTop()](#getBorderTop--) | Retorna um objeto de propriedades da linha da borda superior. |
| [getBorderRight()](#getBorderRight--) | Retorna um objeto de propriedades da linha da borda direita. |
| [getBorderBottom()](#getBorderBottom--) | Retorna um objeto de propriedades da linha da borda inferior. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Retorna um objeto de propriedades da linha diagonal superior esquerda para inferior direita. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Retorna um objeto de propriedades da linha diagonal inferior esquerda para superior direita. |
| [getTransparency()](#getTransparency--) | Obtém ou define a transparência da cor de preenchimento. |
| [setTransparency(float value)](#setTransparency-float-) | Obtém ou define a transparência da cor de preenchimento. |
| [getEffective()](#getEffective--) | Obtém as propriedades de formatação efetiva da célula de tabela com herança e estilos de tabela aplicados. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retorna um objeto de propriedades de preenchimento de célula. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Retorna um objeto de propriedades da linha da borda esquerda. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Retorna um objeto de propriedades da linha da borda superior. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Retorna um objeto de propriedades da linha da borda direita. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Retorna um objeto de propriedades da linha da borda inferior. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Retorna um objeto de propriedades da linha diagonal superior esquerda para inferior direita. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Retorna um objeto de propriedades da linha diagonal inferior esquerda para superior direita. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Obtém ou define a transparência da cor de preenchimento. Leitura/gravação  float .

**Retorna:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Obtém ou define a transparência da cor de preenchimento. Leitura/gravação  float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Obtém as propriedades de formatação efetiva da célula de tabela com herança e estilos de tabela aplicados.

**Retorna:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Um [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).