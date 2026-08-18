---
title: TableFormat
second_title: Aspose.Slides dla Java - referencja API
description: Reprezentuje format tabeli.
type: docs
url: /pl/com.aspose.slides/tableformat/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Reprezentuje format tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt właściwości wypełnienia tabeli. |
| [getTransparency()](#getTransparency--) | Pobiera lub ustawia przezroczystość koloru wypełnienia. |
| [setTransparency(float value)](#setTransparency-float-) | Pobiera lub ustawia przezroczystość koloru wypełnienia. |
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Zwraca obiekt właściwości wypełnienia tabeli. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Gets or sets the transparency of the fill color. odczyt/zapis  float .

**Zwraca:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Gets or sets the transparency of the fill color. odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Gets effective table formatting properties with inheritance and table styles applied.

--------------------

> ```
> Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli.
>  Należy zauważyć, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersze - wyższy niż kolumny, kolumny - wyższy niż cała tabela.
>  Ostatecznie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest tylko przykładem użycia API.
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


**Zwraca:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Obiekt [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
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