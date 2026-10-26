---
title: CellFormat
second_title: Aspose.Slides for Java API Referansı
description: Bir tablo hücresinin biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/cellformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Bir tablo hücresinin biçimini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Bir hücre dolgu özellikleri nesnesi döndürür. |
| [getBorderLeft()](#getBorderLeft--) | Bir sol kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderTop()](#getBorderTop--) | Bir üst kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderRight()](#getBorderRight--) | Bir sağ kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderBottom()](#getBorderBottom--) | Bir alt kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Sol üstten sağ alta çapraz çizgi özellikleri nesnesi döndürür. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Sol alt köşeden sağ üst köşeye çapraz çizgi özellikleri nesnesi döndürür. |
| [getEffective()](#getEffective--) | Miras ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır. |
| [getTransparency()](#getTransparency--) | Dolgu renginin saydamlığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Dolgu renginin saydamlığını alır veya ayarlar. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur uzun.

**Döndürür:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Bir hücre dolgu özellikleri nesnesi döndürür. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Bir sol kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Bir üst kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Bir sağ kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Bir alt kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Sol üstten sağ alta çapraz çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Sol alt köşeden sağ üst köşeye çapraz çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Miras ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


**Döndürür:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Bir [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Dolgu renginin saydamlığını alır veya ayarlar. Okunabilir/Yazılabilir float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Dolgu renginin saydamlığını alır veya ayarlar. Okunabilir/Yazılabilir float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |