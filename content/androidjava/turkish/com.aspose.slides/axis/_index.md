---
title: Axis
second_title: Aspose.Slides for Android via Java API Referansı
description: Grafik eksenini temsil eden nesneyi kapsüller.
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

Bir grafik eksenini temsil eden nesneyi kapsüller.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Kategori ekseninin tipini belirtir. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | IAxis.CategoryAxisType özelliğini eksen verilerine göre otomatik olarak belirlenen bir değerle ayarlar. |
| [getCrossAt()](#getCrossAt--) | Dikey eksenin ekseni kestiği noktayı temsil eder. |
| [setCrossAt(float value)](#setCrossAt-float-) | Dikey eksenin ekseni kestiği noktayı temsil eder. |
| [getDisplayUnit()](#getDisplayUnit--) | Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. |
| [getActualMaxValue()](#getActualMaxValue--) | Eksen üzerindeki gerçek maksimum değeri belirtir. |
| [getActualMinValue()](#getActualMinValue--) | Eksen üzerindeki gerçek minimum değeri belirtir. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Eksenin gerçek ana birimini belirtir. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Eksenin gerçek yardımcı birimini belirtir. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Eksenin gerçek ana birim ölçeğini belirtir. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Eksenin gerçek yardımcı birim ölçeğini belirtir. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [getMaxValue()](#getMaxValue--) | Değer eksenindeki maksimum değeri temsil eder. |
| [setMaxValue(double value)](#setMaxValue-double-) | Değer eksenindeki maksimum değeri temsil eder. |
| [getMinorUnit()](#getMinorUnit--) | Tarih veya değer ekseni için yardımcı birimleri temsil eder. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Tarih veya değer ekseni için yardımcı birimleri temsil eder. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Eksenin yardımcı biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Eksenin yardımcı biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [getMajorUnit()](#getMajorUnit--) | Tarih veya değer ekseni için ana birimleri temsil eder. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Tarih veya değer ekseni için ana birimleri temsil eder. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. |
| [getMinValue()](#getMinValue--) | Değer eksenindeki minimum değeri temsil eder. |
| [setMinValue(double value)](#setMinValue-double-) | Değer eksenindeki minimum değeri temsil eder. |
| [isLogarithmic()](#isLogarithmic--) | Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. |
| [getLogBase()](#getLogBase--) | Logaritmik tabanı temsil eder. |
| [setLogBase(double value)](#setLogBase-double-) | Logaritmik tabanı temsil eder. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint'in veri noktalarını sondan başa doğru çizmeyi temsil eder. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint'in veri noktalarını sondan başa doğru çizmeyi temsil eder. |
| [isVisible()](#isVisible--) | Ekseni görünür olup olmadığını temsil eder. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ekseni görünür olup olmadığını temsil eder. |
| [getMajorTickMark()](#getMajorTickMark--) | Belirtilen eksen için ana işaret çubuğu tipini temsil eder. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Belirtilen eksen için ana işaret çubuğu tipini temsil eder. |
| [getMinorTickMark()](#getMinorTickMark--) | Belirtilen eksen için yardımcı işaret çubuğu tipini temsil eder. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Belirtilen eksen için yardımcı işaret çubuğu tipini temsil eder. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Belirtilen eksen üzerindeki işaret çubuğu etiketlerinin konumunu temsil eder. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Belirtilen eksen üzerindeki işaret çubuğu etiketlerinin konumunu temsil eder. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Tarih ekseni için ana birim ölçeğini temsil eder. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Bir grafik eksenindeki yardımcı ızgara çizgisi biçimini temsil eder. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Bir grafik eksenindeki ana ızgara çizgisi biçimini temsil eder. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Yardımcı ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType değerini FillType.NoFill olarak ayarlayın. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Ana ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType değerini FillType.NoFill olarak ayarlayın. |
| [getFormat()](#getFormat--) | Eksenin biçimini temsil eder. |
| [getTextFormat()](#getTextFormat--) | Metnin biçimini temsil eder. |
| [getTitle()](#getTitle--) | Eksenin başlığını alır. |
| [getCrossType()](#getCrossType--) | Diğer eksenin kesildiği belirtilen eksendeki CrossType değerini temsil eder. |
| [setCrossType(int value)](#setCrossType-int-) | Diğer eksenin kesildiği belirtilen eksendeki CrossType değerini temsil eder. |
| [getPosition()](#getPosition--) | Eksenin konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Eksenin konumunu temsil eder. |
| [hasTitle()](#hasTitle--) | Bir eksenin görünür bir başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir eksenin görünür bir başlığı olup olmadığını belirler. |
| [getNumberFormat()](#getNumberFormat--) | Eksen Etiketleri için biçim dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Eksen Etiketleri için biçim dizesini temsil eder. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Biçimin kaynak veriye bağlı olup olmadığını gösterir. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Biçimin kaynak veriye bağlı olup olmadığını gösterir. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | İşaret çubuğu etiketlerinin dönüş açıını temsil eder. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | İşaret çubuğu etiketlerinin dönüş açıını temsil eder. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Çizilen etiketler arasında kaç işaret çubuğu etiketinin atlanacağını belirtir. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Çizilen etiketler arasında kaç işaret çubuğu etiketinin atlanacağını belirtir. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Otomatik işaret çubuğu etiketi aralığı değerini belirtir. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Otomatik işaret çubuğu etiketi aralığı değerini belirtir. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Bir sonraki işaret çubuğu çizilmeden önce kaç işaret çubuğunun atlanacağını belirtir. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Bir sonraki işaret çubuğu çizilmeden önce kaç işaret çubuğunun atlanacağını belirtir. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Otomatik işaret çubuğu aralığı değerini belirtir. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Otomatik işaret çubuğu aralığı değerini belirtir. |
| [getLabelOffset()](#getLabelOffset--) | Etiketlerin eksenden olan uzaklığını belirtir. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Etiketlerin eksenden olan uzaklığını belirtir. |
| [getAggregationType()](#getAggregationType--) | Kategori ekseninin toplama tipini (bini) temsil eder. |
| [setAggregationType(int value)](#setAggregationType-int-) | Kategori ekseninin toplama tipini (bini) temsil eder. |
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
| [getSlide()](#getSlide--) | Bir FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir FillFormat'un üst sunumunu döndürür. |
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

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenleri için geçerlidir ve 3-D grafiklerde uygulanmaz. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenleri için geçerlidir ve 3-D grafiklerde uygulanmaz. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Kategori ekseninin tipini belirtir. Okuma/yazma [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Döndürür:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Kategori ekseninin tipini belirtir. Okuma/yazma [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parametreler:**
| Parameter | Type | Description |
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

Dikey eksenin ekseni kestiği noktayı temsil eder. Okuma/yazma float.

**Döndürür:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Dikey eksenin ekseni kestiği noktayı temsil eder. Okuma/yazma float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. Okuma/yazma [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Döndürür:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. Okuma/yazma [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Eksenin gerçek ana birimini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Eksenin gerçek yardımcı birimini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Eksenin gerçek ana birim ölçeğini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Eksenin gerçek yardımcı birim ölçeğini belirtir. Gerçek değeri elde etmek için önce IChart.ValidateChartLayout() metodunu çağırın.

**Döndürür:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Değer eksenindeki maksimum değeri temsil eder. Okuma/yazma double.

**Döndürür:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Değer eksenindeki maksimum değeri temsil eder. Okuma/yazma double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Tarih veya değer ekseni için yardımcı birimleri temsil eder. Okuma/yazma double.

**Döndürür:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Tarih veya değer ekseni için yardımcı birimleri temsil eder. Okuma/yazma double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Eksenin yardımcı biriminin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Eksenin yardımcı biriminin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Tarih veya değer ekseni için ana birimleri temsil eder. Okuma/yazma double.

**Döndürür:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Tarih veya değer ekseni için ana birimleri temsil eder. Okuma/yazma double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Değer eksenindeki minimum değeri temsil eder. Okuma/yazma double.

**Döndürür:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Değer eksenindeki minimum değeri temsil eder. Okuma/yazma double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Okuma/yazma boolean.

**Döndürür:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okuma/yazma double.

**Döndürür:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okuma/yazma double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

MS PowerPoint'in veri noktalarını sondan başa doğru çizmeyi temsil eder. Okuma/yazma boolean.

**Döndürür:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

MS PowerPoint'in veri noktalarını sondan başa doğru çizmeyi temsil eder. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Eksenin görünür olup olmadığını temsil eder. Okuma/yazma boolean.

**Döndürür:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Eksenin görünür olup olmadığını temsil eder. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Belirtilen eksen için ana işaret çubuğu tipini temsil eder. Okuma/yazma [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Belirtilen eksen için ana işaret çubuğu tipini temsil eder. Okuma/yazma [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Belirtilen eksen için yardımcı işaret çubuğu tipini temsil eder. Okuma/yazma [TickMarkType](../../com.aspose.slides/tickmarktype).

**Döndürür:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Belirtilen eksen için yardımcı işaret çubuğu tipini temsil eder. Okuma/yazma [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Belirtilen eksen üzerindeki işaret çubuğu etiketlerinin konumunu temsil eder. Okuma/yazma [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Döndürür:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Belirtilen eksen üzerindeki işaret çubuğu etiketlerinin konumunu temsil eder. Okuma/yazma [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okuma/yazma [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okuma/yazma [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okuma/yazma [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Tarih ekseni için ana birim ölçeğini temsil eder. Okuma/yazma [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okuma/yazma [TimeUnitType](../../com.aspose.slides/timeunittype).

**Döndürür:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okuma/yazma [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Bir grafik eksenindeki yardımcı ızgara çizgisi biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Bir grafik eksenindeki ana ızgara çizgisi biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Yardımcı ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType değerini FillType.NoFill olarak ayarlayın. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Ana ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType değerini FillType.NoFill olarak ayarlayın. Yalnızca okuma boolean.

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

Belirtilen eksende diğer eksenin kesildiği CrossType değerini temsil eder. Okuma/yazma [CrossesType](../../com.aspose.slides/crossestype).

**Döndürür:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Belirtilen eksende diğer eksenin kesildiği CrossType değerini temsil eder. Okuma/yazma [CrossesType](../../com.aspose.slides/crossestype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Eksenin konumunu temsil eder. Okuma/yazma [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Eksenin konumunu temsil eder. Okuma/yazma [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bir eksenin görünür bir başlığı olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bir eksenin görünür bir başlığı olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Eksen Etiketleri için biçim dizesini temsil eder. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Eksen Etiketleri için biçim dizesini temsil eder. Okuma/yazma String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Biçimin kaynak veriye bağlı olup olmadığını gösterir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Biçimin kaynak veriye bağlı olup olmadığını gösterir. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

İşaret çubuğu etiketlerinin dönüş açıını temsil eder. Okuma/yazma float.

**Döndürür:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

İşaret çubuğu etiketlerinin dönüş açıını temsil eder. Okuma/yazma float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Çizilen etiketler arasında kaç işaret çubuğu etiketinin atlanacağını belirtir. Kategori veya seriler eksenine uygulanır. Okuma/yazma long.

**Döndürür:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Çizilen etiketler arasında kaç işaret çubuğu etiketinin atlanacağını belirtir. Kategori veya seriler eksenine uygulanır. Okuma/yazma long.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Otomatik işaret çubuğu etiketi aralığı değeri. false ise TickLabelSpacing özelliği kullanılır. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Otomatik işaret çubuğu etiketi aralığı değeri. false ise TickLabelSpacing özelliği kullanılır. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Bir sonraki işaret çubuğu çizilmeden önce kaç işaret çubuğunun atlanacağını belirtir. Kategori veya seriler eksenine uygulanır. Okuma/yazma int.

**Döndürür:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Bir sonraki işaret çubuğu çizilmeden önce kaç işaret çubuğunun atlanacağını belirtir. Kategori veya seriler eksenine uygulanır. Okuma/yazma int.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Otomatik işaret çubuğu aralığı değeri. false ise TickMarksSpacing özelliği kullanılır. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Otomatik işaret çubuğu aralığı değeri. false ise TickMarksSpacing özelliği kullanılır. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Etiketlerin eksenden olan uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer %0 ile %1000 arasında olmalıdır. Okuma/yazma int.

**Döndürür:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Etiketlerin eksenden olan uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer %0 ile %1000 arasında olmalıdır. Okuma/yazma int.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Kategori ekseninin toplama tipini (binleme) temsil eder. Kategori üzerinde uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Kategori ekseninin toplama tipini (binleme) temsil eder. Kategori üzerinde uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerinde uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerinde uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerinde uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Döndürür:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerinde uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın.

**Döndürür:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Otomatik taşma bin değerini belirtir. false ise OverflowBin özelliği kullanılır.

**Döndürür:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Otomatik taşma bin değerini belirtir. false ise OverflowBin özelliği kullanılır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Taşma bin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır.

**Döndürür:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Taşma bin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Alt akış bininin uygulanıp uygulanmadığını belirtir. Alt akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın.

**Döndürür:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Alt akış bininin uygulanıp uygulanmadığını belirtir. Alt akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Otomatik alt akış bin değerini belirtir. false ise UnderflowBin özelliği kullanılır.

**Döndürür:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Otomatik alt akış bin değerini belirtir. false ise UnderflowBin özelliği kullanılır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Alt akış bin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır.

**Döndürür:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Alt akış bin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Bir FillFormat'un üst slaytını döndürür. Yalnızca okuma [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir FillFormat'un üst sunumunu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)