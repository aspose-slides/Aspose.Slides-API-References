---
title: ITrendline
second_title: Aspose.Slides için Java API Referansı
description: Sınıf, grafik serisinin trend çizgisini temsil eder
type: docs
url: /tr/com.aspose.slides/itrendline/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Sınıf, grafik serisinin eğri çizgisini temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Eğri çizgisinin adını alır veya ayarlar. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Eğri çizgisinin adını alır veya ayarlar. |
| [getTrendlineType()](#getTrendlineType--) | Eğri çizgisinin türünü alır veya ayarlar. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Eğri çizgisinin türünü alır veya ayarlar. |
| [getFormat()](#getFormat--) | Eğri çizgisinin biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Eğri çizgisinin biçimini temsil eder. |
| [getBackward()](#getBackward--) | Eğri çizgisinin, eğri çizilen serinin verilerinden önce uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [setBackward(double value)](#setBackward-double-) | Eğri çizgisinin, eğri çizilen serinin verilerinden önce uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [getForward()](#getForward--) | Eğri çizgisinin, eğri çizilen serinin verilerinden sonra uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [setForward(double value)](#setForward-double-) | Eğri çizgisinin, eğri çizilen serinin verilerinden sonra uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [getIntercept()](#getIntercept--) | Eğri çizgisinin y eksenini keseceği değeri belirtir. |
| [setIntercept(double value)](#setIntercept-double-) | Eğri çizgisinin y eksenini keseceği değeri belirtir. |
| [getDisplayEquation()](#getDisplayEquation--) | Eğri çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etikette) görüntüleneceğini belirtir. |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Eğri çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etikette) görüntüleneceğini belirtir. |
| [getOrder()](#getOrder--) | Polinom eğri çizgisinin derecesini belirtir. |
| [setOrder(byte value)](#setOrder-byte-) | Polinom eğri çizgisinin derecesini belirtir. |
| [getPeriod()](#getPeriod--) | Hareketli ortalama eğri çizgisi için eğri çizgisinin periyodunu belirtir. |
| [setPeriod(byte value)](#setPeriod-byte-) | Hareketli ortalama eğri çizgisi için eğri çizgisinin periyodunu belirtir. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Eğri çizgisinin R-kare değerinin grafikte (denklemle aynı etikette) görüntüleneceğini belirtir. |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Eğri çizgisinin R-kare değerinin grafikte (denklemle aynı etikette) görüntüleneceğini belirtir. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu eğri çizgisiyle ilgili lejand girdisini temsil eder Salt Okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Eğri çizgisinin adını alır veya ayarlar. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Eğri çizgisinin adını alır veya ayarlar. Okunur/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Eğri çizgisinin türünü alır veya ayarlar. Okunur/Yazılabilir [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Döndürür:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Eğri çizgisinin türünü alır veya ayarlar. Okunur/Yazılabilir [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Eğri çizgisinin biçimini temsil eder. Okunur/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Eğri çizgisinin biçimini temsil eder. Okunur/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Eğri çizgisinin, verilerden önce uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir negatif olmayan değer olmalıdır. Okunur/Yazılabilir double.

**Döndürür:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Eğri çizgisinin, verilerden önce uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir negatif olmayan değer olmalıdır. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Eğri çizgisinin, verilerden sonra uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir negatif olmayan değer olmalıdır. Okunur/Yazılabilir double.

**Döndürür:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Eğri çizgisinin, verilerden sonra uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir negatif olmayan değer olmalıdır. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Eğri çizgisinin y eksenini keseceği değeri belirtir. Bu özellik yalnızca trend çizgi türü exp, linear veya poly olduğunda desteklenir. Okunur/Yazılabilir double.

**Döndürür:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Eğri çizgisinin y eksenini keseceği değeri belirtir. Bu özellik yalnızca trend çizgi türü exp, linear veya poly olduğunda desteklenir. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Eğri çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etikette) görüntüleneceğini belirtir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Eğri çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etikette) görüntüleneceğini belirtir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Polinom eğri çizgisinin derecesini belirtir. Diğer eğri çizgi türleri için yoksayılır. Değer 2 ile 6 arasında olmalıdır. Okunur/Yazılabilir byte.

**Döndürür:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Polinom eğri çizgisinin derecesini belirtir. Diğer eğri çizgi türleri için yoksayılır. Değer 2 ile 6 arasında olmalıdır. Okunur/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Hareketli ortalama eğri çizgisi için eğri çizgisinin periyodunu belirtir. Diğer eğri çizgi varyantları için yoksayılır. Değer 2 ile 255 arasında olmalıdır. Okunur/Yazılabilir byte.

**Döndürür:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Hareketli ortalama eğri çizgisi için eğri çizgisinin periyodunu belirtir. Diğer eğri çizgi varyantları için yoksayılır. Değer 2 ile 255 arasında olmalıdır. Okunur/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Eğri çizgisinin R-kare değerinin grafikte (denklemle aynı etikette) görüntüleneceğini belirtir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Eğri çizgisinin R-kare değerinin grafikte (denklemle aynı etikette) görüntüleneceğini belirtir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Bu eğri çizgisiyle ilgili lejand girdisini temsil eder Salt Okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)