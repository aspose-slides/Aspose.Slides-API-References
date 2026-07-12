---
title: IAxis
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir grafiğin eksenini temsil eden nesneyi kapsüller.
type: docs
url: /tr/com.aspose.slides/iaxis/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Grafiğin eksenini temsil eden nesneyi kapsüller.
## Yöntemler

| Method | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [getCrossAt()](#getCrossAt--) | Eksen üzerindeki, dik eksenin kesiştiği noktayı temsil eder. |
| [setCrossAt(float value)](#setCrossAt-float-) | Eksen üzerindeki, dik eksenin kesiştiği noktayı temsil eder. |
| [getDisplayUnit()](#getDisplayUnit--) | Değer ekseni için görüntü birimlerinin ölçekleme değerini belirtir. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Değer ekseni için görüntü birimlerinin ölçekleme değerini belirtir. |
| [getActualMaxValue()](#getActualMaxValue--) | Eksen üzerindeki gerçek maksimum değeri belirtir. |
| [getActualMinValue()](#getActualMinValue--) | Eksen üzerindeki gerçek minimum değeri belirtir. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Eksenin gerçek ana birimini belirtir. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Eksenin gerçek yan birimini belirtir. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Eksenin gerçek ana birim ölçeğini belirtir. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Eksenin gerçek yan birim ölçeğini belirtir. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [getMaxValue()](#getMaxValue--) | Değer ekseni üzerindeki maksimum değeri temsil eder. |
| [setMaxValue(double value)](#setMaxValue-double-) | Değer ekseni üzerindeki maksimum değeri temsil eder. |
| [getMinorUnit()](#getMinorUnit--) | Tarih veya değer ekseni için yan birimleri temsil eder. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Tarih veya değer ekseni için yan birimleri temsil eder. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Eksenin yan biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Eksenin yan biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [getMajorUnit()](#getMajorUnit--) | Tarih veya değer ekseni için ana birimleri temsil eder. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Tarih veya değer ekseni için ana birimleri temsil eder. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [getMinValue()](#getMinValue--) | Değer ekseni üzerindeki minimum değeri temsil eder. |
| [setMinValue(double value)](#setMinValue-double-) | Değer ekseni üzerindeki minimum değeri temsil eder. |
| [isLogarithmic()](#isLogarithmic--) | Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [getLogBase()](#getLogBase--) | Logaritmik tabanı temsil eder. |
| [setLogBase(double value)](#setLogBase-double-) | Logaritmik tabanı temsil eder. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint'in veri noktalarını sonuncudan birincine doğru çizip çizmediğini temsil eder. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint'in veri noktalarını sonuncudan birincine doğru çizip çizmediğini temsil eder. |
| [isVisible()](#isVisible--) | Eksenin görünür olup olmadığını temsil eder. |
| [setVisible(boolean value)](#setVisible-boolean-) | Eksenin görünür olup olmadığını temsil eder. |
| [getMajorTickMark()](#getMajorTickMark--) | Belirtilen eksen için ana işaret türünü temsil eder. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Belirtilen eksen için ana işaret türünü temsil eder. |
| [getMinorTickMark()](#getMinorTickMark--) | Belirtilen eksen için yan işaret türünü temsil eder. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Belirtilen eksen için yan işaret türünü temsil eder. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Belirtilen eksen üzerindeki işaret etiketi konumunu temsil eder. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Belirtilen eksen üzerindeki işaret etiketi konumunu temsil eder. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Bir grafik eksenindeki yan ızgara çizgileri formatını temsil eder. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Bir grafik eksenindeki ana ızgara çizgileri formatını temsil eder. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Yan ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Ana ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. |
| [getFormat()](#getFormat--) | Eksenin formatını temsil eder. |
| [getTitle()](#getTitle--) | Eksenin başlığını alır. |
| [getCrossType()](#getCrossType--) | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. |
| [setCrossType(int value)](#setCrossType-int-) | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. |
| [getPosition()](#getPosition--) | Eksenin konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Eksenin konumunu temsil eder. |
| [hasTitle()](#hasTitle--) | Bir eksenin görünür bir başlığa sahip olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir eksenin görünür bir başlığa sahip olup olmadığını belirler. |
| [getNumberFormat()](#getNumberFormat--) | Eksen Etiketleri için format dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Eksen Etiketleri için format dizesini temsil eder. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Formatın bağlı kaynak verisi olup olmadığını gösterir. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Formatın bağlı kaynak verisi olup olmadığını gösterir. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | İşaret etiketi döndürme açısını temsil eder Read/write float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | İşaret etiketi döndürme açısını temsil eder Read/write float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirtir. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirtir. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Otomatik işaret etiketi aralığı değerini belirtir. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Otomatik işaret etiketi aralığı değerini belirtir. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Bir sonraki işaret işareti çizilmeden önce kaç işaret işaretinin atlanacağını belirtir. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Bir sonraki işaret işareti çizilmeden önce kaç işaret işaretinin atlanacağını belirtir. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Otomatik işaret işaretleri aralığı değerini belirtir. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Otomatik işaret işaretleri aralığı değerini belirtir. |
| [getLabelOffset()](#getLabelOffset--) | Etiketlerin eksenden uzaklığını belirtir. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Etiketlerin eksenden uzaklığını belirtir. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | IAxis.CategoryAxisType özelliğini eksen verilerine dayanarak otomatik olarak belirlenen bir değerle ayarlar. |
| [getAggregationType()](#getAggregationType--) | Kategori ekseninin toplama tipini (binleme) temsil eder. |
| [setAggregationType(int value)](#setAggregationType-int-) | Kategori ekseninin toplama tipini (binleme) temsil eder. |
| [getBinWidth()](#getBinWidth--) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir. |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir. |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. |
| [isOverflowBin()](#isOverflowBin--) | Taşma kutusunun uygulanıp uygulanmadığını belirtir. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Taşma kutusunun uygulanıp uygulanmadığını belirtir. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Otomatik taşma kutusu değerini belirtir. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Otomatik taşma kutusu değerini belirtir. |
| [getOverflowBin()](#getOverflowBin--) | Taşma kutusu özel değerini belirtir. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Taşma kutusu özel değerini belirtir. |
| [isUnderflowBin()](#isUnderflowBin--) | Alt akış kutusunun uygulanıp uygulanmadığını belirtir. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Alt akış kutusunun uygulanıp uygulanmadığını belirtir. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Otomatik alt akış kutusu değerini belirtir. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Otomatik alt akış kutusu değerini belirtir. |
| [getUnderflowBin()](#getUnderflowBin--) | Alt akış kutusu özel değerini belirtir. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Alt akış kutusu özel değerini belirtir. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3-B eksenlere uygulanmaz. Read/write boolean.

**Döndürür:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3-B eksenlere uygulanmaz. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Eksen üzerindeki, dik eksenin kesiştiği noktayı temsil eder. Read/write float.

**Döndürür:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Eksen üzerindeki, dik eksenin kesiştiği noktayı temsil eder. Read/write float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Değer ekseni için görüntü birimlerinin ölçekleme değerini belirtir. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Döndürür:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Değer ekseni için görüntü birimlerinin ölçekleme değerini belirtir. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Eksen üzerindeki gerçek maksimum değeri belirtir. Call method IChart.ValidateChartLayout() previously to get actual value.

**Döndürür:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Eksen üzerindeki gerçek minimum değeri belirtir. Call method IChart.ValidateChartLayout() previously to get actual value.

**Döndürür:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Eksenin gerçek ana birimini belirtir. Call method IChart.ValidateChartLayout() previously to get actual value.

**Döndürür:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Eksenin gerçek yan birimini belirtir. Call method IChart.ValidateChartLayout() previously to get actual value.

**Döndürür:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Eksenin gerçek ana birim ölçeğini belirtir. Call method IChart.ValidateChartLayout() previously to get actual value.

**Döndürür:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Eksenin gerçek yan birim ölçeğini belirtir. Call method IChart.ValidateChartLayout() previously to get actual value.

**Döndürür:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Döndürür:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Değer ekseni üzerindeki maksimum değeri temsil eder. Read/write double.

**Döndürür:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Değer ekseni üzerindeki maksimum değeri temsil eder. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Tarih veya değer ekseni için yan birimleri temsil eder. Read/write double.

**Döndürür:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Tarih veya değer ekseni için yan birimleri temsil eder. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Eksenin yan biriminin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Döndürür:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Eksenin yan biriminin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Tarih veya değer ekseni için ana birimleri temsil eder. Read/write double.

**Döndürür:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Tarih veya değer ekseni için ana birimleri temsil eder. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Döndürür:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Döndürür:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Değer ekseni üzerindeki minimum değeri temsil eder. Read/write double.

**Döndürür:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Değer ekseni üzerindeki minimum değeri temsil eder. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Read/write boolean.

**Döndürür:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Logaritmik tabanı temsil eder. Default value is 10. Read/write double.

**Döndürür:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Logaritmik tabanı temsil eder. Default value is 10. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

MS PowerPoint'in veri noktalarını sonuncudan birincine doğru çizip çizmediğini temsil eder. Read/write boolean.

**Döndürür:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

MS PowerPoint'in veri noktalarını sonuncudan birincine doğru çizip çizmediğini temsil eder. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Eksenin görünür olup olmadığını temsil eder. Read/write boolean.

**Döndürür:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Eksenin görünür olup olmadığını temsil eder. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Belirtilen eksen için ana işaret türünü temsil eder. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Belirtilen eksen için ana işaret türünü temsil eder. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Belirtilen eksen için yan işaret türünü temsil eder. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Belirtilen eksen için yan işaret türünü temsil eder. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Belirtilen eksen üzerindeki işaret etiketi konumunu temsil eder. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Döndürür:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Belirtilen eksen üzerindeki işaret etiketi konumunu temsil eder. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Tarih ekseni için ana birim ölçeğini temsil eder. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Tarih ekseni için ana birim ölçeğini temsil eder. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Tarih ekseni için ana birim ölçeğini temsil eder. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Tarih ekseni için ana birim ölçeğini temsil eder. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Yan ızgara çizgileri formatını temsil eder. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Ana ızgara çizgileri formatını temsil eder. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Yan ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Read-only boolean.

**Döndürür:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Ana ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Read-only boolean.

**Döndürür:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Eksenin formatını temsil eder. Read-only [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Döndürür:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Eksenin başlığını alır. Read-only [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Döndürür:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Eksenin konumunu temsil eder. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Döndürür:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Eksenin konumunu temsil eder. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bir eksenin görünür bir başlığa sahip olup olmadığını belirler. Read/write boolean.

**Döndürür:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bir eksenin görünür bir başlığa sahip olup olmadığını belirler. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Eksen Etiketleri için format dizesini temsil eder. Read/write String.

**Döndürür:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Eksen Etiketleri için format dizesini temsil eder. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Formatın bağlı kaynak verisi olup olmadığını gösterir. Read/write boolean.

**Döndürür:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Formatın bağlı kaynak verisi olup olmadığını gösterir. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

İşaret etiketi döndürme açısını temsil eder. Read/write float.

**Döndürür:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

İşaret etiketi döndürme açısını temsil eder. Read/write float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirtir. Read/write long.

**Döndürür:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirtir. Read/write long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Otomatik işaret etiketi aralığı değerini belirtir. If false: use TickLabelSpacing property. Read/write boolean.

**Döndürür:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Otomatik işaret etiketi aralığı değerini belirtir. If false: use TickLabelSpacing property. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Bir sonraki işaret işareti çizilmeden önce kaç işaret işaretinin atlanacağını belirtir. Applied to category or series axis. Read/write int.

**Döndürür:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Bir sonraki işaret işareti çizilmeden önce kaç işaret işaretinin atlanacağını belirtir. Applied to category or series axis. Read/write int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Otomatik işaret işaretleri aralığı değerini belirtir. If false: use TickMarksSpacing property. Read/write boolean.

**Döndürür:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Otomatik işaret işaretleri aralığı değerini belirtir. If false: use TickMarksSpacing property. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Etiketlerin eksenden uzaklığını belirtir. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int.

**Döndürür:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Etiketlerin eksenden uzaklığını belirtir. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Kategori ekseninin tipini belirtir. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Döndürür:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Kategori ekseninin tipini belirtir. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType özelliğini eksen verilerine dayanarak otomatik olarak belirlenen bir değerle ayarlar.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Kategori ekseninin toplama tipini (binleme) temsil eder. Applied to category. Used with Histogram or HistogramPareto series only.

**Döndürür:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Kategori ekseninin toplama tipini (binleme) temsil eder. Applied to category. Used with Histogram or HistogramPareto series only.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Döndürür:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Döndürür:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Taşma kutusunun uygulanıp uygulanmadığını belirtir. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Döndürür:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Taşma kutusunun uygulanıp uygulanmadığını belirtir. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Otomatik taşma kutusu değerini belirtir. If false: use OverflowBin property.

**Döndürür:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Otomatik taşma kutusu değerini belirtir. If false: use OverflowBin property.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Taşma kutusu özel değerini belirtir. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true.

**Döndürür:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Taşma kutusu özel değerini belirtir. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Alt akış kutusunun uygulanıp uygulanmadığını belirtir. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Döndürür:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Alt akış kutusunun uygulanıp uygulanmadığını belirtir. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Otomatik alt akış kutusu değerini belirtir. If false: use UnderflowBin property.

**Döndürür:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Otomatik alt akış kutusu değerini belirtir. If false: use UnderflowBin property.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Alt akış kutusu özel değerini belirtir. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true.

**Döndürür:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Alt akış kutusu özel değerini belirtir. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |