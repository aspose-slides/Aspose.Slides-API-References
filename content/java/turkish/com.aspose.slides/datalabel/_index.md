---
title: DataLabel
second_title: Aspose.Slides for Java API Referansı
description: Seri etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabel/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Seri etiketlerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel sınıfının yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [isVisible()](#isVisible--) | False, veri etiketinin görünür olmadığı anlamına gelir (ve bu nedenle tüm Show*-bayrakları (ShowValue, ...) false olur). |
| [hide()](#hide--) | Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat ayarları ya da TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş bir metin içerebilir. |
| [getTextFormat()](#getTextFormat--) | Metin formatını döndürür. |
| [getX()](#getX--) | Başlığın x koordinatını, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [setX(float value)](#setX-float-) | Başlığın x koordinatını, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [getY()](#getY--) | Başlığın y koordinatını, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [setY(float value)](#setY-float-) | Başlığın y koordinatını, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [getWidth()](#getWidth--) | Başlığın genişliğini, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Başlığın genişliğini, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. |
| [getHeight()](#getHeight--) | Başlığın yüksekliğini, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Başlığın yüksekliğini, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. |
| [getRight()](#getRight--) | Sağ. |
| [getBottom()](#getBottom--) | Alt. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Veri etiketi formatını döndürür. |
| [getValueFromCell()](#getValueFromCell--) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [getActualX()](#getActualX--) | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirler. |
| [getActualY()](#getActualY--) | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirler. |
| [getActualWidth()](#getActualWidth--) | Grafik öğesinin gerçek genişliğini belirler. |
| [getActualHeight()](#getActualHeight--) | Grafik öğesinin gerçek yüksekliğini belirler. |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel sınıfının yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Üst ChartDataPoint. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Salt okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False, veri etiketinin görünür olmadığı anlamına gelir (ve bu nedenle tüm Show*-bayrakları (ShowValue, ...) false olur). Salt okunur  boolean .

--------------------
Veri etiketi görünürse, Hide() yöntemiyle gizleyebilirsiniz. Ancak veri etiketi görünür değilse (IsVisible false ise), Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. Bu işlemden sonra IsVisible false olur.

--------------------
Veri etiketi görünür değilse (IsVisible false ise), Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.
### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat ayarları ya da TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür.

**Döndürür:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa, yalnızca metnini değiştirir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni TextFrameForOverriding için metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Zengin biçimlendirilmiş bir metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri veri etiketinin otomatik oluşturulan metninin üzerine yazar. Veri etiketinin otomatik oluşturulan metni, ShowSeriesName, ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilen metni ifade eder. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Metin formatını döndürür. Salt okunur [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Başlığın x koordinatını, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Döndürür:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Başlığın x koordinatını, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Başlığın y koordinatını, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Döndürür:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Başlığın y koordinatını, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Başlığın genişliğini, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Döndürür:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Başlığın genişliğini, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Başlığın yüksekliğini, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Döndürür:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Başlığın yüksekliğini, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar. Okunur/Yazılabilir  float .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Sağ. Salt okunur  float .

**Döndürür:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Alt. Salt okunur  float .

**Döndürür:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Veri etiketi formatını döndürür. Salt okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

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

Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur  float .

**Döndürür:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur  float .

**Döndürür:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur  float .

**Döndürür:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur  float .

**Döndürür:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'un üst slaytını döndürür. Salt okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'un üst sunumunu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)