---
title: ColumnFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o formato de uma coluna de tabela.
type: docs
url: /pt/com.aspose.slides/columnformat/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Representa o formato de uma coluna de tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getEffective()](#getEffective--) | Obtém propriedades de formatação efetiva da coluna da tabela com herança e estilos de tabela aplicados. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


Obtém propriedades de formatação efetiva da coluna da tabela com herança e estilos de tabela aplicados.

--------------------

> ```
> Este exemplo demonstra como obter o formato de preenchimento efetivo para diferentes partes lógicas da tabela.
>  Observe que a formatação de célula sempre tem prioridade maior que a formatação de linha, linha - maior que coluna, coluna - maior que a tabela inteira.
>  Portanto, finalmente as propriedades de CellFormatEffectiveData são sempre usadas para desenhar a tabela. O código a seguir é apenas um exemplo da API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
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
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - A [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
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