---
title: Trendline
second_title: Aspose.Slides for Android için Java API Referansı
description: Sınıf, grafik serisinin trend çizgisini temsil eder
type: docs
url: /tr/com.aspose.slides/trendline/
---
**Miras:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Sınıf, grafik serisinin trend çizgisini temsil eder
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Trend çizgisinin adını alır veya ayarlar. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Trend çizgisinin adını alır veya ayarlar. |
| [getTrendlineType()](#getTrendlineType--) | Trend çizgisinin tipini alır veya ayarlar. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Trend çizgisinin tipini alır veya ayarlar. |
| [getFormat()](#getFormat--) | Trend çizgisinin biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Trend çizgisinin biçimini temsil eder. |
| [getBackward()](#getBackward--) | Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden önce uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. |
| [setBackward(double value)](#setBackward-double-) | Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden önce uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. |
| [getForward()](#getForward--) | Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden sonra uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. |
| [setForward(double value)](#setForward-double-) | Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden sonra uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. |
| [getIntercept()](#getIntercept--) | Trend çizgisinin y eksenini keseceği değeri belirler. |
| [setIntercept(double value)](#setIntercept-double-) | Trend çizgisinin y eksenini keseceği değeri belirler. |
| [getDisplayEquation()](#getDisplayEquation--) | Trend çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etiket içinde) görüntüleneceğini belirler. |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Trend çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etiket içinde) görüntüleneceğini belirler. |
| [getOrder()](#getOrder--) | Polinom trend çizgisinin derecesini belirler. |
| [setOrder(byte value)](#setOrder-byte-) | Polinom trend çizgisinin derecesini belirler. |
| [getPeriod()](#getPeriod--) | Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirler. |
| [setPeriod(byte value)](#setPeriod-byte-) | Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirler. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Trend çizgisinin R-kare değerinin grafikte (denklemle aynı etiket içinde) görüntüleneceğini belirler. |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Trend çizgisinin R-kare değerinin grafikte (denklemle aynı etiket içinde) görüntüleneceğini belirler. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu trend çizgisiyle ilişkili lejand girişini temsil eder Salt Okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Parametre "text" içindeki metinle TextFrameForOverriding'i başlatır. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş metin içerebilir. |
| [getTextFormat()](#getTextFormat--) | Metin biçimini döndürür. |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getSlide()](#getSlide--) | FillFormat'in üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'in üst sunumunu döndürür. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Trend çizgisinin adını alır veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Trend çizgisinin adını alır veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Trend çizgisinin tipini alır veya ayarlar. Okunabilir/Yazılabilir [TrendlineType](../../com.aspose.slides/trendlinetype).

**Döndürür:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Trend çizgisinin tipini alır veya ayarlar. Okunabilir/Yazılabilir [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Trend çizgisinin biçimini temsil eder. Okunabilir/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Trend çizgisinin biçimini temsil eder. Okunabilir/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden önce uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. Serpilme ve serpilme dışı grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden önce uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. Serpilme ve serpilme dışı grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden sonra uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. Serpilme ve serpilme dışı grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Trend çizgisinin, trendi uygulanmakta olan serinin verilerinden sonra uzadığı kategori (veya serpilme grafiğinde birimler) sayısını belirler. Serpilme ve serpilme dışı grafiklerde değer herhangi bir negatif olmayan değer olabilir. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Trend çizgisinin y eksenini keseceği değeri belirler. Bu özellik yalnızca trend çizgi tipi exp, linear veya poly olduğunda desteklenir. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Trend çizgisinin y eksenini keseceği değeri belirler. Bu özellik yalnızca trend çizgi tipi exp, linear veya poly olduğunda desteklenir. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Trend çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etiket içinde) görüntüleneceğini belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Trend çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etiket içinde) görüntüleneceğini belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Polinom trend çizgisinin derecesini belirler. Diğer trend çizgi tipleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır. Okunabilir/Yazılabilir byte.

**Döndürür:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Polinom trend çizgisinin derecesini belirler. Diğer trend çizgi tipleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır. Okunabilir/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirler. Diğer trend çizgi varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır. Okunabilir/Yazılabilir byte.

**Döndürür:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirler. Diğer trend çizgi varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır. Okunabilir/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Trend çizgisinin R-kare değerinin grafikte (denklemle aynı etiket içinde) görüntüleneceğini belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Trend çizgisinin R-kare değerinin grafikte (denklemle aynı etiket içinde) görüntüleneceğini belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Bu trend çizgisiyle ilişkili lejand girişini temsil eder Salt Okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Parametre "text" içindeki metinle TextFrameForOverriding'i başlatır. TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir.

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

Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri veri etiketi için otomatik oluşturulan metni geçersiz kılar. Otomatik oluşturulan veri etiketi metni, ShowSeriesName, ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilen metindir. Salt Okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Metin biçimini döndürür. Salt Okunur [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Salt Okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'in üst slaytını döndürür. Salt Okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'in üst sunumunu döndürür. Salt Okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)