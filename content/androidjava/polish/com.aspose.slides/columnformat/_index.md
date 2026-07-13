---
title: ColumnFormat
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Reprezentuje format kolumny tabeli.
type: docs
url: /pl/com.aspose.slides/columnformat/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Reprezentuje format kolumny tabeli.
## Metody

| Method | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera skuteczne właściwości formatowania kolumny tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


Pobiera skuteczne właściwości formatowania kolumny tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.

--------------------

> ```
> Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli.
>  Należy pamiętać, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersze - wyższy niż kolumny, kolumny - wyższy niż cała tabela.
>  Dlatego ostatecznie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod to tylko przykład użycia API.
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


**Zwraca:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Zwraca rodzica IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)