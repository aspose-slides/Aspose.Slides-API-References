---
title: DataLabel
second_title: Aspose.Slides Android için Java API Referansı
description: Bir seri etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabel/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Bir seri etiketlerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel sınıfının yeni bir örneğini oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Ebeveyn chart döndürür. |
| [isVisible()](#isVisible--) | False, veri etiketinin görünür olmadığını (ve tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. |
| [hide()](#hide--) | Tüm Show*-bayraklarını (ShowValue, ...) false duruma ayarlayarak veri etiketini gizli yapar. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding'i "text" parametresindeki metinle başlatır. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş metin içerebilir. |
| [getTextFormat()](#getTextFormat--) | Metin biçimini döndürür. |
| [getX()](#getX--) | Başlığın x koordinatını, chart genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [setX(float value)](#setX-float-) | Başlığın x koordinatını, chart genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [getY()](#getY--) | Başlığın y koordinatını, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [setY(float value)](#setY-float-) | Başlığın y koordinatını, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [getWidth()](#getWidth--) | Başlığın genişliğini, chart genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Başlığın genişliğini, chart genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [getHeight()](#getHeight--) | Başlığın yüksekliğini, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Başlığın yüksekliğini, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [getRight()](#getRight--) | Sağ. |
| [getBottom()](#getBottom--) | Alt. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Veri etiketi biçimini döndürür. |
| [getValueFromCell()](#getValueFromCell--) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [getActualX()](#getActualX--) | Grafik elemanının gerçek x konumunu (sol) grafik sol üst köşesine göre belirtir. |
| [getActualY()](#getActualY--) | Grafik elemanının gerçek üst konumunu, grafik sol üst köşesine göre belirtir. |
| [getActualWidth()](#getActualWidth--) | Grafik elemanının gerçek genişliğini belirtir. |
| [getActualHeight()](#getActualHeight--) | Grafik elemanının gerçek yüksekliğini belirtir. |
| [getSlide()](#getSlide--) | FillFormat'ın ebeveyn slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'ın ebeveyn sunumunu döndürür. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel sınıfının yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Ebeveyn ChartDataPoint. |
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

Ebeveyn chart döndürür. Salt-okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False, veri etiketinin görünür olmadığını (ve tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. Salt-okunur boolean.

**Döndürür:**
boolean
--------------------

Veri etiketi görünürse Hide() metodu ile gizleyebilirsiniz. Ancak veri etiketi görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. Bu işlemden sonra IsVisible false olacaktır.

--------------------

Veri etiketi görünür değilse (IsVisible false) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür.

**Döndürür:**
java.lang.String - java.lang.String nesnesi.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding'i "text" parametresindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa yalnızca metnini değiştirir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir TextFrameForOverriding için metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri veri etiketinin otomatik oluşturulan metnini geçersiz kılar. Otomatik oluşturulan veri etiketi metni, ShowSeriesName, ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliği ile biçimlendirilmiş metindir. Salt-okunur [ITextFrame](../../com.aspose.slides/itextframe).

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

Başlığın x koordinatını, chart genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Başlığın x koordinatını, chart genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Başlığın y koordinatını, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Başlığın y koordinatını, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Başlığın genişliğini, chart genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Başlığın genişliğini, chart genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Başlığın yüksekliğini, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Başlığın yüksekliğini, chart yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Grafik elemanının gerçek x konumunu (sol) grafik sol üst köşesine göre belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunan float.

**Döndürür:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Grafik elemanının gerçek üst konumunu, grafik sol üst köşesine göre belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunan float.

**Döndürür:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Grafik elemanının gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunan float.

**Döndürür:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Grafik elemanının gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunan float.

**Döndürür:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'ın ebeveyn slaytını döndürür. Salt-okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'ın ebeveyn sunumunu döndürür. Salt-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)