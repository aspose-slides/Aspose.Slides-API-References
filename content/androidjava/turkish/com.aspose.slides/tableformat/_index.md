---
title: TableFormat
second_title: Aspose.Slides Android için Java API Referansı
description: Bir tablonun biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/tableformat/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Bir tablonun biçimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir tablo doldurma özellikleri nesnesi döndürür. |
| [getTransparency()](#getTransparency--) | Dolgu renginin şeffaflığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Dolgu renginin şeffaflığını alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Bir tablo doldurma özellikleri nesnesi döndürür. Yalnızca okuyabilir [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Dolgu renginin şeffaflığını alır veya ayarlar. Okuma/yazma  float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Dolgu renginin şeffaflığını alır veya ayarlar. Okuma/yazma  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır.

--------------------

> ```
> Bu örnek, farklı tablo mantığı bölümleri için etkili doldurma biçimini almayı gösterir.
>  Lütfen hücre biçimlendirmesinin her zaman satır biçimlendirmesinden, satır biçimlendirmesinin de sütundan, sütun biçimlendirmesinin de tüm tablodan daha yüksek önceliğe sahip olduğunu unutmayın.
>  Dolayısıyla sonunda CellFormatEffectiveData özellikleri her zaman tabloyu çizmek için kullanılır. Aşağıdaki kod yalnızca bir API örneğidir.
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
```

**Döndürür:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Bir [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Sürüm. Yalnızca okuyabilir long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Üst IPresentationComponent nesnesini döndürür. Yalnızca okuyabilir [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)