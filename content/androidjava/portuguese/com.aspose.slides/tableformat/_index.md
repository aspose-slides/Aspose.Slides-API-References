---
title: TableFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o formato de uma tabela.
type: docs
url: /pt/com.aspose.slides/tableformat/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as interfaces implementadas:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Representa o formato de uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retorna um objeto de propriedades de preenchimento da tabela. |
| [getTransparency()](#getTransparency--) | Obtém ou define a transparência da cor de preenchimento. |
| [setTransparency(float value)](#setTransparency-float-) | Obtém ou define a transparência da cor de preenchimento. |
| [getEffective()](#getEffective--) | Obtém propriedades de formatação de tabela efetivas com herança e estilos de tabela aplicados. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Retorna um objeto de propriedades de preenchimento da tabela. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Obtém ou define a transparência da cor de preenchimento. Leitura/Gravação  float .

**Retorna:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Obtém ou define a transparência da cor de preenchimento. Leitura/Gravação  float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Obtém propriedades de formatação de tabela efetivas com herança e estilos de tabela aplicados.

--------------------

> ```
> Este exemplo demonstra como obter o formato de preenchimento efetivo para diferentes partes lógicas da tabela.
>  Observe que a formatação de célula sempre tem prioridade maior que a formatação de linha, linha - maior que coluna, coluna - maior que a tabela inteira.
>  Portanto, as propriedades de CellFormatEffectiveData são sempre usadas para desenhar a tabela. O código a seguir é apenas um exemplo da API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Retorna o IPresentationComponent pai. Somente leitura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retorna:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)