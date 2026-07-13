---
title: RowFormat
second_title: Aspose.Slides dla Androida – Dokumentacja API Java
description: Reprezentuje format wiersza tabeli.
type: docs
url: /pl/com.aspose.slides/rowformat/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Reprezentuje format wiersza tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania wiersza tabeli z zastosowanym dziedziczeniem i stylami tabeli. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Pobiera efektywne właściwości formatowania wiersza tabeli z zastosowanym dziedziczeniem i stylami tabeli.

--------------------

> ```
> Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli.
>  Uwaga: formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersze - wyższy niż kolumny, kolumny - wyższy niż cała tabela.
>  W związku z tym właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod to tylko przykład użycia API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - A [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Wersja. Long tylko do odczytu.

**Zwraca:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Zwraca rodzica IPresentationComponent. [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent) tylko do odczytu.

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)