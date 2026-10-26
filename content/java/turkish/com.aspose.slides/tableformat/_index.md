---
title: TableFormat
second_title: Aspose.Slides for Java API Referansı
description: Bir tablonun biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/tableformat/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Bir tablonun biçimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir tablo dolgu özellikleri nesnesi döndürür. |
| [getTransparency()](#getTransparency--) | Dolgu renginin saydamlığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Dolgu renginin saydamlığını alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Bir tablo dolgu özellikleri nesnesi döndürür. Yalnızca okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Dolgu renginin saydamlığını alır veya ayarlar. Okunur/Yazılabilir  float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Dolgu renginin saydamlığını alır veya ayarlar. Okunur/Yazılabilir  float .

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
> Bu örnek, farklı tablo mantık bölümleri için etkili dolgu biçimini almayı göstermektedir.
>  Lütfen hücre biçimlendirmesinin her zaman satır biçimlendirmesinden, satırın sütundan, sütunun ise tüm tablodan daha yüksek önceliğe sahip olduğunu unutmayın.
>  Bu yüzden sonunda CellFormatEffectiveData özellikleri tablonun çiziminde her zaman kullanılır. Aşağıdaki kod yalnızca API örneğidir.
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
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Sürüm. Yalnızca okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Üst IPresentationComponent döndürür. Yalnızca okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)