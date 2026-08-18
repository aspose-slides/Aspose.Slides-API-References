---
title: Axis
second_title: Aspose.Slides for Java API Referansı
description: Grafik eksenini temsil eden nesneyi kapsar.
type: docs
url: /tr/com.aspose.slides/axis/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Bir grafiğin eksenini temsil eden nesneyi kapsüller.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | IAxis.CategoryAxisType özelliğini eksen verilerine göre otomatik olarak belirlenen bir değerle ayarlar. |
| [getCrossAt()](#getCrossAt--) | Dikey eksenin kesiştiği eksen üzerindeki noktayı temsil eder. |
| [setCrossAt(float value)](#setCrossAt-float-) | Dikey eksenin kesiştiği eksen üzerindeki noktayı temsil eder. |
| [getDisplayUnit()](#getDisplayUnit--) | Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. |
| [getActualMaxValue()](#getActualMaxValue--) | Eksen üzerindeki gerçek maksimum değeri belirtir. |
| [getActualMinValue()](#getActualMinValue--) | Eksen üzerindeki gerçek minimum değeri belirtir. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Eksenin gerçek büyük birimini belirtir. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Eksenin gerçek küçük birimini belirtir. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Eksenin gerçek büyük birim ölçeğini belirtir. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Eksenin gerçek küçük birim ölçeğini belirtir. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [getMaxValue()](#getMaxValue--) | Değer eksenindeki maksimum değeri temsil eder. |
| [setMaxValue(double value)](#setMaxValue-double-) | Değer eksenindeki maksimum değeri temsil eder. |
| [getMinorUnit()](#getMinorUnit--) | Tarih veya değer ekseni için küçük birimleri temsil eder. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Tarih veya değer ekseni için küçük birimleri temsil eder. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [getMajorUnit()](#getMajorUnit--) | Tarih veya değer ekseni için büyük birimleri temsil eder. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Tarih veya değer ekseni için büyük birimleri temsil eder. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [getMinValue()](#getMinValue--) | Değer eksenindeki minimum değeri temsil eder. |
| [setMinValue(double value)](#setMinValue-double-) | Değer eksenindeki minimum değeri temsil eder. |
| [isLogarithmic()](#isLogarithmic--) | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [getLogBase()](#getLogBase--) | Logaritmik tabanı temsil eder. |
| [setLogBase(double value)](#setLogBase-double-) | Logaritmik tabanı temsil eder. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint'in veri noktalarını sondan başa doğru çizip çizmediğini temsil eder. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint'in veri noktalarını sondan başa doğru çizip çizmediğini temsil eder. |
| [isVisible()](#isVisible--) | Eksenin görünür olup olmadığını temsil eder. |
| [setVisible(boolean value)](#setVisible-boolean-) | Eksenin görünür olup olmadığını temsil eder. |
| [getMajorTickMark()](#getMajorTickMark--) | Belirtilen eksen için büyük işaret tipini temsil eder. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Belirtilen eksen için büyük işaret tipini temsil eder. |
| [getMinorTickMark()](#getMinorTickMark--) | Belirtilen eksen için küçük işaret tipini temsil eder. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Belirtilen eksen için küçük işaret tipini temsil eder. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Belirtilen eksende işaret etiketi konumunu temsil eder. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Belirtilen eksende işaret etiketi konumunu temsil eder. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Tarih ekseni için büyük birim ölçeğini temsil eder. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Tarih ekseni için büyük birim ölçeğini temsil eder. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Tarih ekseni için büyük birim ölçeğini temsil eder. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Tarih ekseni için büyük birim ölçeğini temsil eder. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Grafik eksenindeki küçük ızgara çizgileri biçimini temsil eder. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Grafik eksenindeki büyük ızgara çizgileri biçimini temsil eder. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Küçük ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType değerini FillType.NoFill olarak ayarlayın. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Büyük ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType değerini FillType.NoFill olarak ayarlayın. |
| [getFormat()](#getFormat--) | Eksenin biçimini temsil eder. |
| [getTextFormat()](#getTextFormat--) | Metnin biçimini temsil eder. |
| [getTitle()](#getTitle--) | Eksenin başlığını alır. |
| [getCrossType()](#getCrossType--) | Diğer eksenin kesildiği belirtilen eksende CrossType'ı temsil eder. |
| [setCrossType(int value)](#setCrossType-int-) | Diğer eksenin kesildiği belirtilen eksende CrossType'ı temsil eder. |
| [getPosition()](#getPosition--) | Eksen konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Eksen konumunu temsil eder. |
| [hasTitle()](#hasTitle--) | Bir eksenin görünür başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir eksenin görünür başlığı olup olmadığını belirler. |
| [getNumberFormat()](#getNumberFormat--) | Eksen Etiketleri için biçim dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Eksen Etiketleri için biçim dizesini temsil eder. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Biçimin bağlı kaynak verisi olup olmadığını gösterir. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Biçimin bağlı kaynak verisi olup olmadığını gösterir. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | İşaret etiketlerinin dönüş açısını temsil eder. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | İşaret etiketlerinin dönüş açısını temsil eder. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirler. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirler. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Otomatik işaret etiketi aralığı değerini belirtir. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Otomatik işaret etiketi aralığı değerini belirtir. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Bir sonraki işaret çizilmeden önce kaç işaretin atlanacağını belirler. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Bir sonraki işaret çizilmeden önce kaç işaretin atlanacağını belirler. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Otomatik işaret aralığı değerini belirtir. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Otomatik işaret aralığı değerini belirtir. |
| [getLabelOffset()](#getLabelOffset--) | Etiketlerin eksenden olan mesafesini belirler. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Etiketlerin eksenden olan mesafesini belirler. |
| [getAggregationType()](#getAggregationType--) | Kategori ekseninin toplama türünü (gruplama) temsil eder. |
| [setAggregationType(int value)](#setAggregationType-int-) | Kategori ekseninin toplama türünü (gruplama) temsil eder. |
| [getBinWidth()](#getBinWidth--) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında grup genişliğini belirtir. |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında grup genişliğini belirtir. |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında grup sayısını belirtir. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında grup sayısını belirtir. |
| [isOverflowBin()](#isOverflowBin--) | Taşma grubunun uygulanıp uygulanmadığını belirtir. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Taşma grubunun uygulanıp uygulanmadığını belirtir. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Otomatik taşma grup değerini belirtir. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Otomatik taşma grup değerini belirtir. |
| [getOverflowBin()](#getOverflowBin--) | Taşma grup özel değerini belirtir. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Taşma grup özel değerini belirtir. |
| [isUnderflowBin()](#isUnderflowBin--) | Alt akış grubunun uygulanıp uygulanmadığını belirtir. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Alt akış grubunun uygulanıp uygulanmadığını belirtir. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Otomatik alt akış grup değerini belirtir. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Otomatik alt akış grup değerini belirtir. |
| [getUnderflowBin()](#getUnderflowBin--) | Alt akış grup özel değerini belirtir. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Alt akış grup özel değerini belirtir. |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Yalnızca okuma [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenleri için geçerlidir ve 3D grafiklere uygulanmaz. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenleri için geçerlidir ve 3D grafiklere uygulanmaz. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Kategori ekseninin tipini belirtir. Okuma/Yazma [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Döndürür:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Kategori ekseninin tipini belirtir. Okuma/Yazma [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType özelliğini eksen verilerine göre otomatik olarak belirlenen bir değerle ayarlar.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Dikey eksenin kesiştiği eksen üzerindeki noktayı temsil eder. Okuma/Yazma float.

**Döndürür:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Dikey eksenin kesiştiği eksen üzerindeki noktayı temsil eder. Okuma/Yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. Okuma/Yazma [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Döndürür:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. Okuma/Yazma [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Eksenin gerçek büyük birimini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Eksenin gerçek küçük birimini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Eksenin gerçek büyük birim ölçeğini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Değer eksenindeki maksimum değeri temsil eder. Okuma/Yazma double.

**Döndürür:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Değer eksenindeki maksimum değeri temsil eder. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Tarih veya değer ekseni için küçük birimleri temsil eder. Okuma/Yazma double.

**Döndürür:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Tarih veya değer ekseni için küçük birimleri temsil eder. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Tarih veya değer ekseni için büyük birimleri temsil eder. Okunur/Yazılır double.

**Döndürür:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Tarih veya değer ekseni için büyük birimleri temsil eder. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Değer eksenindeki minimum değeri temsil eder. Okunur/Yazılır double.

**Döndürür:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Değer eksenindeki minimum değeri temsil eder. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunur/Yazılır double.

**Döndürür:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


MS PowerPoint’in veri noktalarını sondan başa doğru çizip çizmediğini temsil eder. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


MS PowerPoint’in veri noktalarını sondan başa doğru çizip çizmediğini temsil eder. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Eksenin görünür olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Eksenin görünür olup olmadığını temsil eder. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Belirtilen eksen için büyük tik işaretinin tipini temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Belirtilen eksen için büyük tik işaretinin tipini temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Belirtilen eksen için küçük tik işaretinin tipini temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Belirtilen eksen için küçük tik işaretinin tipini temsil eder. Okunur/Yazılır [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Belirtilen eksen üzerindeki tik etiketi konumunu temsil eder. Okunur/Yazılır [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Döndürür:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Belirtilen eksen üzerindeki tik etiketi konumunu temsil eder. Okunur/Yazılır [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Tarih ekseni için büyük birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Tarih ekseni için büyük birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Tarih ekseni için büyük birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Tarih ekseni için büyük birim ölçeğini temsil eder. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunur/Yazılır [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Bir grafik eksenindeki küçük ızgara çizgilerinin biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Bir grafik eksenindeki büyük ızgara çizgilerinin biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


Küçük ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


Büyük ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Eksenin biçimini temsil eder. Yalnızca okuma [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Döndürür:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Metnin biçimini temsil eder. Yalnızca okuma [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Eksenin başlığını alır. Yalnızca okuma [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Belirtilen eksende diğer eksenin kesiştiği noktadaki CrossType'ı temsil eder. Okunur/Yazılır [CrossesType](../../com.aspose.slides/crossestype).

**Döndürür:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Belirtilen eksende diğer eksenin kesiştiği noktadaki CrossType'ı temsil eder. Okunur/Yazılır [CrossesType](../../com.aspose.slides/crossestype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Eksenin konumunu temsil eder. Okunur/Yazılır [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Eksenin konumunu temsil eder. Okunur/Yazılır [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Bir eksenin görünür başlığa sahip olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Bir eksenin görünür başlığa sahip olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Eksen Etiketleri için format dizesini temsil eder. Okunur/Yazılır String.

**Döndürür:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Eksen Etiketleri için format dizesini temsil eder. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Formatın kaynak veriye bağlı olup olmadığını gösterir. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Formatın kaynak veriye bağlı olup olmadığını gösterir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Tik etiketlerinin döndürme açısını temsil eder. Okunur/Yazılır float.

**Döndürür:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Tik etiketlerinin döndürme açısını temsil eder. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Çizilen etiketler arasında kaç tik etiketinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/Yazılır long.

**Döndürür:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Çizilen etiketler arasında kaç tik etiketinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/Yazılır long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Otomatik tik etiketi aralığı değerini belirtir. false ise TickLabelSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Otomatik tik etiketi aralığı değerini belirtir. false ise TickLabelSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Bir sonraki yanıp sönmeden önce kaç tik işaretinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/Yazılır int.

**Döndürür:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Bir sonraki yanıp sönmeden önce kaç tik işaretinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Otomatik tik işareti aralığı değerini belirtir. false ise TickMarksSpacing özelliği kullanılır. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Otomatik tik işareti aralığı değerini belirtir. false ise TickMarksSpacing özelliği kullanılır. Okunur/Yazılık boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih ekseni için uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunur/Yazılır int.

**Döndürür:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih ekseni için uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```


Kategori ekseninin (binleme) toplama türünü temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```


Kategori ekseninin (binleme) toplama türünü temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```


AggregationType özelliği değeri AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```


AggregationType özelliği değeri AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```


AggregationType özelliği değeri AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```


AggregationType özelliği değeri AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```


Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın.

**Döndürür:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```


Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```


Otomatik taşma kutusu değerini belirtir. Yanlış ise: OverflowBin özelliğini kullanın.

**Döndürür:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```


Otomatik taşma kutusu değerini belirtir. Yanlış ise: OverflowBin özelliğini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```


Taşma kutusunun özel değerini belirtir. IsAutomaticOverflowBin özelliği false olarak ayarlandığında ve IsOverflowBin özelliği true olduğunda uygulanır.

**Döndürür:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```


Taşma kutusunun özel değerini belirtir. IsAutomaticOverflowBin özelliği false olarak ayarlandığında ve IsOverflowBin özelliği true olduğunda uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```


Alt akış kutusunun uygulanıp uygulanmadığını belirtir. Alt akış kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın.

**Döndürür:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```


Alt akış kutusunun uygulanıp uygulanmadığını belirtir. Alt akış kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```


Otomatik alt akış kutusu değerini belirtir. Yanlış ise: UnderflowBin özelliğini kullanın.

**Döndürür:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```


Otomatik alt akış kutusu değerini belirtir. Yanlış ise: UnderflowBin özelliğini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```


Alt akış kutusunun özel değerini belirtir. IsAutomaticUnderflowBin özelliği false olarak ayarlandığında ve IsUnderflowBin özelliği true olduğunda uygulanır.

**Döndürür:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```


Alt akış kutusunun özel değerini belirtir. IsAutomaticUnderflowBin özelliği false olarak ayarlandığında ve IsUnderflowBin özelliği true olduğunda uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Üst slaytı döndürür. Salt-okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Üst sunumu döndürür. Salt-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)