---
title: IAxis
second_title: Aspose.Slides for Java API Referansı
description: Bir grafik eksenini temsil eden nesneyi kapsüller.
type: docs
url: /tr/com.aspose.slides/iaxis/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Bir çizelge eksenini temsil eden nesneyi kapsüller.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [getCrossAt()](#getCrossAt--) | Eksenin, dik eksenin kesiştiği noktayı temsil eder. |
| [setCrossAt(float value)](#setCrossAt-float-) | Eksenin, dik eksenin kesiştiği noktayı temsil eder. |
| [getDisplayUnit()](#getDisplayUnit--) | Değer ekseni için gösterim birimlerinin ölçekleme değerini belirtir. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Değer ekseni için gösterim birimlerinin ölçekleme değerini belirtir. |
| [getActualMaxValue()](#getActualMaxValue--) | Eksen üzerindeki gerçek maksimum değeri belirtir. |
| [getActualMinValue()](#getActualMinValue--) | Eksen üzerindeki gerçek minimum değeri belirtir. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Eksenin gerçek ana birimini belirtir. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Eksenin gerçek alt birimini belirtir. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Eksenin gerçek ana birim ölçeğini belirtir. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Eksenin gerçek alt birim ölçeğini belirtir. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Maksimum değerin otomatik olarak atandığını gösterir. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Maksimum değerin otomatik olarak atandığını gösterir. |
| [getMaxValue()](#getMaxValue--) | Değer eksenindeki maksimum değeri temsil eder. |
| [setMaxValue(double value)](#setMaxValue-double-) | Değer eksenindeki maksimum değeri temsil eder. |
| [getMinorUnit()](#getMinorUnit--) | Tarih veya değer ekseni için alt birimleri temsil eder. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Tarih veya değer ekseni için alt birimleri temsil eder. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Eksenin alt biriminin otomatik olarak atandığını gösterir. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Eksenin alt biriminin otomatik olarak atandığını gösterir. |
| [getMajorUnit()](#getMajorUnit--) | Tarih veya değer ekseni için ana birimleri temsil eder. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Tarih veya değer ekseni için ana birimleri temsil eder. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Eksenin ana biriminin otomatik olarak atandığını gösterir. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Eksenin ana biriminin otomatik olarak atandığını gösterir. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Minimum değerin otomatik olarak atandığını gösterir. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Minimum değerin otomatik olarak atandığını gösterir. |
| [getMinValue()](#getMinValue--) | Değer eksenindeki minimum değeri temsil eder. |
| [setMinValue(double value)](#setMinValue-double-) | Değer eksenindeki minimum değeri temsil eder. |
| [isLogarithmic()](#isLogarithmic--) | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [getLogBase()](#getLogBase--) | Logaritmik tabanı temsil eder. |
| [setLogBase(double value)](#setLogBase-double-) | Logaritmik tabanı temsil eder. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint'in veri noktalarını sonundan birincisine doğru çizmeyi temsil eder. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint'in veri noktalarını sonundan birincisine doğru çizmeyi temsil eder. |
| [isVisible()](#isVisible--) | Eksenin görünür olup olmadığını temsil eder. |
| [setVisible(boolean value)](#setVisible-boolean-) | Eksenin görünür olup olmadığını temsil eder. |
| [getMajorTickMark()](#getMajorTickMark--) | Belirtilen eksen için ana tik işaretinin tipini temsil eder. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Belirtilen eksen için ana tik işaretinin tipini temsil eder. |
| [getMinorTickMark()](#getMinorTickMark--) | Belirtilen eksen için alt tik işaretinin tipini temsil eder. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Belirtilen eksen için alt tik işaretinin tipini temsil eder. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Belirtilen eksende tik işareti etiketlerinin konumunu temsil eder. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Belirtilen eksende tik işareti etiketlerinin konumunu temsil eder. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Bir çizelge eksenindeki alt ızgara çizgileri biçimini temsil eder. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Bir çizelge eksenindeki ana ızgara çizgileri biçimini temsil eder. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Alt ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Ana ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. |
| [getFormat()](#getFormat--) | Eksenin biçimini temsil eder. |
| [getTitle()](#getTitle--) | Eksenin başlığını alır. |
| [getCrossType()](#getCrossType--) | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. |
| [setCrossType(int value)](#setCrossType-int-) | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. |
| [getPosition()](#getPosition--) | Eksenin konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Eksenin konumunu temsil eder. |
| [hasTitle()](#hasTitle--) | Bir eksenin görünür başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir eksenin görünür başlığı olup olmadığını belirler. |
| [getNumberFormat()](#getNumberFormat--) | Eksen Etiketleri için biçim dizgisini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Eksen Etiketleri için biçim dizgisini temsil eder. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Biçimin bağlı kaynak verisi olup olmadığını gösterir. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Biçimin bağlı kaynak verisi olup olmadığını gösterir. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Tik etiketlerinin döndürme açısını temsil eder. Okunur/yazılabilir float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Tik etiketlerinin döndürme açısını temsil eder. Okunur/yazılabilir float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Çizilen etiketler arasında kaç tik etiketinin atlanacağını belirtir. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Çizilen etiketler arasında kaç tik etiketinin atlanacağını belirtir. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Otomatik tik etiket aralığı değerini belirtir. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Otomatik tik etiket aralığı değerini belirtir. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Bir sonraki tik işareti çizilmeden önce kaç tik işaretinin atlanacağını belirtir. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Bir sonraki tik işareti çizilmeden önce kaç tik işaretinin atlanacağını belirtir. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Otomatik tik işaretleri aralığı değerini belirtir. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Otomatik tik işaretleri aralığı değerini belirtir. |
| [getLabelOffset()](#getLabelOffset--) | Etiketlerin eksenden uzaklığını belirtir. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Etiketlerin eksenden uzaklığını belirtir. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Axis verilerine dayanarak otomatik olarak belirlenen bir değerle IAxis.CategoryAxisType özelliğini ayarlar. |
| [getAggregationType()](#getAggregationType--) | Kategori ekseninin toplama tipini (binleme) temsil eder. |
| [setAggregationType(int value)](#setAggregationType-int-) | Kategori ekseninin toplama tipini (binleme) temsil eder. |
| [getBinWidth()](#getBinWidth--) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. |
| [isOverflowBin()](#isOverflowBin--) | Taşma bininin uygulanıp uygulanmadığını belirtir. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Taşma bininin uygulanıp uygulanmadığını belirtir. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Otomatik taşma bin değeri belirtir. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Otomatik taşma bin değeri belirtir. |
| [getOverflowBin()](#getOverflowBin--) | Taşma bin özel değerini belirtir. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Taşma bin özel değerini belirtir. |
| [isUnderflowBin()](#isUnderflowBin--) | Alt akış bininin uygulanıp uygulanmadığını belirtir. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Alt akış bininin uygulanıp uygulanmadığını belirtir. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Otomatik alt akış bin değeri belirtir. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Otomatik alt akış bin değeri belirtir. |
| [getUnderflowBin()](#getUnderflowBin--) | Alt akış bin özel değerini belirtir. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Alt akış bin özel değerini belirtir. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D çizelgelere uygulanmaz. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D çizelgelere uygulanmaz. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Eksenin, dik eksenin kesiştiği noktayı temsil eder. Okunur/yazılabilir float.

**Döndürür:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Eksenin, dik eksenin kesiştiği noktayı temsil eder. Okunur/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Değer ekseni için gösterim birimlerinin ölçekleme değerini belirtir. Okunur/yazılabilir [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Döndürür:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Değer ekseni için gösterim birimlerinin ölçekleme değerini belirtir. Okunur/yazılabilir [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Eksenin gerçek ana birimini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Eksenin gerçek alt birimini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Eksenin gerçek ana birim ölçeğini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Eksenin gerçek alt birim ölçeğini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Maksimum değerin otomatik olarak atandığını gösterir. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Maksimum değerin otomatik olarak atandığını gösterir. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Değer eksenindeki maksimum değeri temsil eder. Okunur/yazılabilir double.

**Döndürür:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Değer eksenindeki maksimum değeri temsil eder. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Tarih veya değer ekseni için alt birimleri temsil eder. Okunur/yazılabilir double.

**Döndürür:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Tarih veya değer ekseni için alt birimleri temsil eder. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Eksenin alt biriminin otomatik olarak atandığını gösterir. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Eksenin alt biriminin otomatik olarak atandığını gösterir. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Tarih veya değer ekseni için ana birimleri temsil eder. Okunur/yazılabilir double.

**Döndürür:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Tarih veya değer ekseni için ana birimleri temsil eder. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Eksenin ana biriminin otomatik olarak atandığını gösterir. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Değer eksenindeki minimum değeri temsil eder. Okunur/Yazılır double.

**Döndürür:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Değer eksenindeki minimum değeri temsil eder. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Değer ekseninin ölçek türünün logaritmik olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Değer ekseninin ölçek türünün logaritmik olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Logaritmik tabanı temsil eder. Varsayılan değer 10’dur. Okunur/Yazılır double.

**Döndürür:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Logaritmik tabanı temsil eder. Varsayılan değer 10’dur. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

MS PowerPoint’in veri noktalarını sondan başlayarak çizip çizmediğini temsil eder. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

MS PowerPoint’in veri noktalarını sondan başlayarak çizip çizmediğini temsil eder. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Eksenin görünür olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Eksenin görünür olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Belirtilen eksenin ana tik işareti türünü temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Belirtilen eksenin ana tik işareti türünü temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Belirtilen eksenin yan tik işareti türünü temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Belirtilen eksenin yan tik işareti türünü temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Belirtilen eksende tik etiketi konumunu temsil eder. Okunur/Yazılır [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Döndürür:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Belirtilen eksende tik etiketi konumunu temsil eder. Okunur/Yazılır [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Bir grafik eksenindeki yan ızgara çizgileri formatını temsil eder. Sadece Okunur [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Bir grafik eksenindeki ana ızgara çizgileri formatını temsil eder. Sadece Okunur [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Yan ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Sadece Okunur boolean.

**Döndürür:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Ana ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Sadece Okunur boolean.

**Döndürür:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Eksenin formatını temsil eder. Sadece Okunur [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Döndürür:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Eksenin başlığını alır. Sadece Okunur [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Diğer eksenin kesiştiği belirtilen eksende CrossType’ı temsil eder. Okunur/Yazılır [CrossesType](../../com.aspose.slides/crossestype).

**Döndürür:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Diğer eksenin kesiştiği belirtilen eksende CrossType’ı temsil eder. Okunur/Yazılır [CrossesType](../../com.aspose.slides/crossestype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Eksenin konumunu temsil eder. Okunur/Yazılır [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Döndürür:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Eksenin konumunu temsil eder. Okunur/Yazılır [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bir eksenin görünür bir başlığa sahip olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bir eksenin görünür bir başlığa sahip olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Eksen Etiketleri için biçim dizesini temsil eder. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Eksen Etiketleri için biçim dizesini temsil eder. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Biçimin kaynak veriye bağlı olup olmadığını gösterir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Biçimin kaynak veriye bağlı olup olmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Tik etiketlerinin dönüş açısını temsil eder. Okunur/Yazılır float.

**Döndürür:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Tik etiketlerinin dönüş açısını temsil eder. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Çizilen etiket arasında kaç tik etiketinin atlanacağını belirtir. Okunur/Yazılır long.

**Döndürür:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Çizilen etiket arasında kaç tik etiketinin atlanacağını belirtir. Okunur/Yazılır long.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Otomatik tik etiketi aralığı değerini belirtir. false ise TickLabelSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Otomatik tik etiketi aralığı değerini belirtir. false ise TickLabelSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Bir sonraki tik işareti çizilmeden önce kaç tik işaretinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/Yazılır int.

**Döndürür:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Bir sonraki tik işareti çizilmeden önce kaç tik işaretinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Otomatik tik işareti aralığı değerini belirtir. false ise TickMarksSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Otomatik tik işareti aralığı değerini belirtir. false ise TickMarksSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer %0 ile %1000 arasında olmalıdır. Okunur/Yazılır int.

**Döndürür:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer %0 ile %1000 arasında olmalıdır. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Kategori ekseninin türünü belirtir. Okunur/Yazılır [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Döndürür:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Kategori ekseninin türünü belirtir. Okunur/Yazılır [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType özelliğini eksen verisine göre otomatik olarak belirlenen bir değerle ayarlar.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Kategori ekseninin (gruplama) toplama türünü temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Kategori ekseninin (gruplama) toplama türünü temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```


AggregationType özelliği değeri AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```


AggregationType özelliği değeri AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```


AggregationType özelliği değeri AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```


AggregationType özelliği değeri AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```


Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin özelliklerini kullanın.

**Döndürür:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```


Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin özelliklerini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```


Otomatik taşma kutusu değerini belirtir. Yanlış ise: OverflowBin özelliğini kullanın.

**Döndürür:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```


Otomatik taşma kutusu değerini belirtir. Yanlış ise: OverflowBin özelliğini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```


Taşma kutusu özel değerini belirtir. IsAutomaticOverflowBin özelliği false olarak ayarlandığında ve IsOverflowBin özelliği true olduğunda uygulanır.

**Döndürür:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```


Taşma kutusu özel değerini belirtir. IsAutomaticOverflowBin özelliği false olarak ayarlandığında ve IsOverflowBin özelliği true olduğunda uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```


Alt akış kutusunun uygulanıp uygulanmadığını belirtir. Alt akış kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin özelliklerini kullanın.

**Döndürür:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```


Alt akış kutusunun uygulanıp uygulanmadığını belirtir. Alt akış kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin özelliklerini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```


Otomatik alt akış kutusu değerini belirtir. Yanlış ise: UnderflowBin özelliğini kullanın.

**Döndürür:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```


Otomatik alt akış kutusu değerini belirtir. Yanlış ise: UnderflowBin özelliğini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```


Alt akış kutusu özel değerini belirtir. IsAutomaticUnderflowBin özelliği false olarak ayarlandığında ve IsUnderflowBin özelliği true olduğunda uygulanır.

**Döndürür:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```


Alt akış kutusu özel değerini belirtir. IsAutomaticUnderflowBin özelliği false olarak ayarlandığında ve IsUnderflowBin özelliği true olduğunda uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |