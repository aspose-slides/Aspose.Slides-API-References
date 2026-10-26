---
title: Trendline
second_title: Aspose.Slides Java API Referansı
description: Sınıf, grafik serisinin trend çizgisini temsil eder.
type: docs
url: /tr/com.aspose.slides/trendline/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Sınıf, grafik serisinin trend çizgisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Trend çizgisinin adını alır veya ayarlar. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Trend çizgisinin adını alır veya ayarlar. |
| [getTrendlineType()](#getTrendlineType--) | Trend çizgisinin tipini alır veya ayarlar. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Trend çizgisinin tipini alır veya ayarlar. |
| [getFormat()](#getFormat--) | Trend çizgisinin biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Trend çizgisinin biçimini temsil eder. |
| [getBackward()](#getBackward--) | Trend çizgisinin, serinin trendi alındığı veriden önce uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. |
| [setBackward(double value)](#setBackward-double-) | Trend çizgisinin, serinin trendi alındığı veriden önce uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. |
| [getForward()](#getForward--) | Trend çizgisinin, serinin trendi alındığı veriden sonra uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. |
| [setForward(double value)](#setForward-double-) | Trend çizgisinin, serinin trendi alındığı veriden sonra uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. |
| [getIntercept()](#getIntercept--) | Trend çizgisinin y eksenini kestiği değeri belirtir. |
| [setIntercept(double value)](#setIntercept-double-) | Trend çizgisinin y eksenini kestiği değeri belirtir. |
| [getDisplayEquation()](#getDisplayEquation--) | Trend çizgisinin denkleminin grafik üzerinde (Rsquaredvalue ile aynı etiket içinde) gösterileceğini belirtir. |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Trend çizgisinin denkleminin grafik üzerinde (Rsquaredvalue ile aynı etiket içinde) gösterileceğini belirtir. |
| [getOrder()](#getOrder--) | Polinom trend çizgisinin mertebesini belirtir. |
| [setOrder(byte value)](#setOrder-byte-) | Polinom trend çizgisinin mertebesini belirtir. |
| [getPeriod()](#getPeriod--) | Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirtir. |
| [setPeriod(byte value)](#setPeriod-byte-) | Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirtir. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Trend çizgisinin R-kare değerinin grafik üzerinde (denklemin aynı etiketi içinde) gösterileceğini belirtir. |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Trend çizgisinin R-kare değerinin grafik üzerinde (denklemin aynı etiketi içinde) gösterileceğini belirtir. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu trend çizgisiyle ilgili gösterge girdisini temsil eder. Sadece okuma [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding'i parametre "text" içindeki metinle başlat. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş metin içerebilir. |
| [getTextFormat()](#getTextFormat--) | Metin biçimini döndürür. |
| [getChart()](#getChart--) | Üst (ebeveyn) grafiği döndürür. |
| [getSlide()](#getSlide--) | FillFormat'in üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'in üst sunumunu döndürür. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Trend çizgisinin adını alır veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Trend çizgisinin adını alır veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Trend çizgisinin tipini alır veya ayarlar. Okuma/Yazma [TrendlineType](../../com.aspose.slides/trendlinetype).

**Döndürür:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Trend çizgisinin tipini alır veya ayarlar. Okuma/Yazma [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Trend çizgisinin biçimini temsil eder. Okuma/Yazma [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Trend çizgisinin biçimini temsil eder. Okuma/Yazma [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Trend çizgisinin, serinin trendi alındığı veriden önce uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. Scatter ve scatter olmayan grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okuma/Yazma double.

**Döndürür:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Trend çizgisinin, serinin trendi alındığı veriden önce uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. Scatter ve scatter olmayan grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Trend çizgisinin, serinin trendi alındığı veriden sonra uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. Scatter ve scatter olmayan grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okuma/Yazma double.

**Döndürür:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Trend çizgisinin, serinin trendi alındığı veriden sonra uzandığı kategori (veya dağılım grafiğinde birimler) sayısını belirtir. Scatter ve scatter olmayan grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Trend çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca trend çizgisi türü exp, linear veya poly olduğunda desteklenir. Okuma/Yazma double.

**Döndürür:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Trend çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca trend çizgisi türü exp, linear veya poly olduğunda desteklenir. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Trend çizgisinin denkleminin grafik üzerinde (Rsquaredvalue ile aynı etiket içinde) gösterileceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Trend çizgisinin denkleminin grafik üzerinde (Rsquaredvalue ile aynı etiket içinde) gösterileceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Polinom trend çizgisinin mertebesini belirtir. Diğer trend çizgi türleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır. Okuma/Yazma byte.

**Döndürür:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Polinom trend çizgisinin mertebesini belirtir. Diğer trend çizgi türleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır. Okuma/Yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirtir. Diğer trend çizgi varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır. Okuma/Yazma byte.

**Döndürür:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirtir. Diğer trend çizgi varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır. Okuma/Yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Trend çizgisinin R-kare değerinin grafik üzerinde (denklemin aynı etiketi içinde) gösterileceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Trend çizgisinin R-kare değerinin grafik üzerinde (denklemin aynı etiketi içinde) gösterileceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Bu trend çizgisiyle ilgili gösterge girdisini temsil eder. Sadece okuma [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding'i parametre "text" içindeki metinle başlat. TextFrameForOverriding zaten başlatıldıysa sadece metnini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni TextFrameForOverriding için metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri veri etiketi otomatik oluşturulmuş metnini geçersiz kılar. Veri etiketi otomatik oluşturulmuş metin, ShowSeriesName, ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilmiş metindir. Sadece okuma [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Metin biçimini döndürür. Sadece okuma [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst (ebeveyn) grafiği döndürür. Sadece okuma [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'in üst slaytını döndürür. Sadece okuma [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'in üst sunumunu döndürür. Sadece okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)