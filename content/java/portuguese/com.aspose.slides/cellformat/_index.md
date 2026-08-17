---
title: CellFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa o formato de uma célula de tabela.
type: docs
url: /pt/com.aspose.slides/cellformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Representa o formato de uma célula de tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Retorna um objeto de propriedades de preenchimento da célula. |
| [getBorderLeft()](#getBorderLeft--) | Retorna um objeto de propriedades da linha da borda esquerda. |
| [getBorderTop()](#getBorderTop--) | Retorna um objeto de propriedades da linha da borda superior. |
| [getBorderRight()](#getBorderRight--) | Retorna um objeto de propriedades da linha da borda direita. |
| [getBorderBottom()](#getBorderBottom--) | Retorna um objeto de propriedades da linha da borda inferior. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Retorna um objeto de propriedades da linha diagonal de cima à esquerda para baixo à direita. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Retorna um objeto de propriedades da linha diagonal de baixo à esquerda para cima à direita. |
| [getEffective()](#getEffective--) | Obtém as propriedades de formatação efetiva da célula de tabela com herança e estilos de tabela aplicados. |
| [getTransparency()](#getTransparency--) | Obtém ou define a transparência da cor de preenchimento. |
| [setTransparency(float value)](#setTransparency-float-) | Obtém ou define a transparência da cor de preenchimento. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Returns:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Retorna um objeto de propriedades de preenchimento da célula. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Retorna um objeto de propriedades da linha da borda esquerda. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Retorna um objeto de propriedades da linha da borda superior. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Retorna um objeto de propriedades da linha da borda direita. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Retorna um objeto de propriedades da linha da borda inferior. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Retorna um objeto de propriedades da linha diagonal de cima à esquerda para baixo à direita. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Retorna um objeto de propriedades da linha diagonal de baixo à esquerda para cima à direita. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Obtém as propriedades de formatação efetiva da célula de tabela com herança e estilos de tabela aplicados.

--------------------

> ```
> Este exemplo demonstra como obter o formato de preenchimento efetivo para diferentes partes lógicas da tabela.
>  Observe que a formatação de célula sempre tem prioridade maior que a formatação de linha, linha - maior que coluna, coluna - maior que a tabela inteira.
>  Assim, as propriedades de CellFormatEffectiveData são sempre usadas para desenhar a tabela. O código a seguir é apenas um exemplo de uso da API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Obtém ou define a transparência da cor de preenchimento. Leitura/gravação  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Obtém ou define a transparência da cor de preenchimento. Leitura/gravação  float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |