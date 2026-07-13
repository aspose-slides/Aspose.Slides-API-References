---
title: CellFormat
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje format komórki tabeli.
type: docs
url: /pl/com.aspose.slides/cellformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Reprezentuje format komórki tabeli.
## Metody

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt właściwości wypełnienia komórki. |
| [getBorderLeft()](#getBorderLeft--) | Zwraca obiekt właściwości linii lewego obramowania. |
| [getBorderTop()](#getBorderTop--) | Zwraca obiekt właściwości linii górnego obramowania. |
| [getBorderRight()](#getBorderRight--) | Zwraca obiekt właściwości linii prawego obramowania. |
| [getBorderBottom()](#getBorderBottom--) | Zwraca obiekt właściwości linii dolnego obramowania. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Zwraca obiekt właściwości linii ukośnej od lewego górnego do prawego dolnego. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Zwraca obiekt właściwości linii ukośnej od lewego dolnego do prawego górnego. |
| [getEffective()](#getEffective--) | Pobiera efektywne właściwości formatowania komórki tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabel. |
| [getTransparency()](#getTransparency--) | Pobiera lub ustawia przezroczystość koloru wypełnienia. |
| [setTransparency(float value)](#setTransparency-float-) | Pobiera lub ustawia przezroczystość koloru wypełnienia. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Zwraca obiekt właściwości wypełnienia komórki. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Zwraca obiekt właściwości linii lewego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Zwraca obiekt właściwości linii górnego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Zwraca obiekt właściwości linii prawego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Zwraca obiekt właściwości linii dolnego obramowania. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Zwraca obiekt właściwości linii ukośnej od lewego górnego do prawego dolnego. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Zwraca obiekt właściwości linii ukośnej od lewego dolnego do prawego górnego. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Pobiera efektywne właściwości formatowania komórki tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabel.

--------------------

> ```
> Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli.
>  Należy pamiętać, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersz - wyższy niż kolumna, kolumna - wyższy niż cała tabela.
>  W rezultacie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest jedynie przykładem użycia API.
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


**Zwraca:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Pobiera lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Zwraca:**
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Pobiera lub ustawia przezroczystość koloru wypełnienia. Odczyt/zapis  float .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |