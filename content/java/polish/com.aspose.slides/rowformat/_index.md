---
title: RowFormat
second_title: Aspose.Slides dla Java – Referencja API
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
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania wiersza tabeli z uwzględnieniem dziedziczenia i stylów tabeli. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

Pobiera efektywne właściwości formatowania wiersza tabeli z uwzględnieniem dziedziczenia i stylów tabeli.

--------------------

> ```
> Ten przykład demonstruje uzyskiwanie efektywnego formatu wypełnienia dla różnych części logiki tabeli.
>  Należy pamiętać, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersze - wyższy niż kolumny, kolumny - wyższy niż cała tabela.
>  Ostatecznie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest jedynie przykładem użycia API.
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
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
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

Zwraca nadrzędny IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)