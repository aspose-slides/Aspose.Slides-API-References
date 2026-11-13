---
title: DataLabel
second_title: Aspose.Slides for Java API Referansı
description: Seri etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabel/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Bir dizi etiketini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel sınıfının yeni bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [isVisible()](#isVisible--) | False, veri etiketinin görünür olmadığını (ve dolayısıyla tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) belirtir. |
| [hide()](#hide--) | Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş bir metin içerebilir. |
| [getTextFormat()](#getTextFormat--) | Metin biçimini döndürür. |
| [getX()](#getX--) | Grafiğin genişliğinin bir oranı olarak başlığın x koordinatını döndürür veya ayarlar. |
| [setX(float value)](#setX-float-) | Grafiğin genişliğinin bir oranı olarak başlığın x koordinatını döndürür veya ayarlar. |
| [getY()](#getY--) | Grafiğin yüksekliğinin bir oranı olarak başlığın y koordinatını döndürür veya ayarlar. |
| [setY(float value)](#setY-float-) | Grafiğin yüksekliğinin bir oranı olarak başlığın y koordinatını döndürür veya ayarlar. |
| [getWidth()](#getWidth--) | Grafiğin genişliğinin bir oranı olarak başlığın genişliğini döndürür veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Grafiğin genişliğinin bir oranı olarak başlığın genişliğini döndürür veya ayarlar. |
| [getHeight()](#getHeight--) | Grafiğin yüksekliğinin bir oranı olarak başlığın yüksekliğini döndürür veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Grafiğin yüksekliğinin bir oranı olarak başlığın yüksekliğini döndürür veya ayarlar. |
| [getRight()](#getRight--) | Sağ. |
| [getBottom()](#getBottom--) | Alt. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Veri etiketi biçimini döndürür. |
| [getValueFromCell()](#getValueFromCell--) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [getLabelShapeType()](#getLabelShapeType--) | Veri etiketinin şekil tipini alır veya ayarlar. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Veri etiketinin şekil tipini alır veya ayarlar. |
| [getActualX()](#getActualX--) | Grafik öğesinin sol üst köşesine göre gerçek x konumunu (sol) belirtir. |
| [getActualY()](#getActualY--) | Grafik öğesinin sol üst köşesine göre gerçek üst konumunu belirtir. |
| [getActualWidth()](#getActualWidth--) | Grafik öğesinin gerçek genişliğini belirtir. |
| [getActualHeight()](#getActualHeight--) | Grafik öğesinin gerçek yüksekliğini belirtir. |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel sınıfının yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Üst ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Salt-okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False, veri etiketinin görünür olmadığını (ve dolayısıyla tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. Salt-okunur boolean.

--------------------

Eğer veri etiketi görünürse Hide() yöntemiyle gizleyebilirsiniz. Veri etiketi görünür değilse (IsVisible false) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak görünür hâle getirebilirsiniz.

**Döndürür:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. Bu işlemden sonra IsVisible false olur.

--------------------

Veri etiketi görünür değilse (IsVisible false) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak görünür hâle getirebilirsiniz.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür.

**Döndürür:**
java.lang.String - The java.lang.String object.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir TextFrameForOverriding için metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Zengin biçimlendirilmiş bir metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri veri etiketinin otomatik oluşturulan metninin üzerine yazar. Otomatik oluşturulan veri etiketi metni, ShowSeriesName, ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilmiş metindir. Salt-okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Metin biçimini döndürür. Salt-okunur [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

Grafiğin genişliğinin bir oranı olarak başlığın x koordinatını döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Grafiğin genişliğinin bir oranı olarak başlığın x koordinatını döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Grafiğin yüksekliğinin bir oranı olarak başlığın y koordinatını döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Grafiğin yüksekliğinin bir oranı olarak başlığın y koordinatını döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Grafiğin genişliğinin bir oranı olarak başlığın genişliğini döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Grafiğin genişliğinin bir oranı olarak başlığın genişliğini döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Grafiğin yüksekliğinin bir oranı olarak başlığın yüksekliğini döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Grafiğin yüksekliğinin bir oranı olarak başlığın yüksekliğini döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Sağ. Salt-okunur float.

**Döndürür:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

Alt. Salt-okunur float.

**Döndürür:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Veri etiketi biçimini döndürür. Salt-okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true ise uygulanır.

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true ise uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Veri etiketinin şekil tipini alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk veri etiketinin şekil tipini Elips olarak ayarla.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Veri etiketinin şekil tipini alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk veri etiketinin şekil tipini Elips olarak ayarla.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Grafik öğesinin sol üst köşesine göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Salt-okunur float.

**Döndürür:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Grafik öğesinin sol üst köşesine göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Salt-okunur float.

**Döndürür:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Salt-okunur float.

**Döndürür:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Salt-okunur float.

**Döndürür:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'un üst slaytını döndürür. Salt-okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'un üst sunumunu döndürür. Salt-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)