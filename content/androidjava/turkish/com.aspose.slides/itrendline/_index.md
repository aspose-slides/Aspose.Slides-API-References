---
title: ITrendline
second_title: Aspose.Slides for Android via Java API Referansı
description: Sınıf, grafik serisinin eğri çizgisini temsil eder.
type: docs
url: /tr/com.aspose.slides/itrendline/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Sınıf, grafik serisinin eğri çizgisini temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Eğim çizgisinin adını alır veya ayarlar. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Eğim çizgisinin adını alır veya ayarlar. |
| [getTrendlineType()](#getTrendlineType--) | Eğim çizgisinin tipini alır veya ayarlar. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Eğim çizgisinin tipini alır veya ayarlar. |
| [getFormat()](#getFormat--) | Eğim çizgisinin biçimini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Eğim çizgisinin biçimini temsil eder. |
| [getBackward()](#getBackward--) | Eğri çizgisinin, trendi alınan serinin verilerinden önce uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [setBackward(double value)](#setBackward-double-) | Eğri çizgisinin, trendi alınan serinin verilerinden önce uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [getForward()](#getForward--) | Eğri çizgisinin, trendi alınan serinin verilerinden sonra uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [setForward(double value)](#setForward-double-) | Eğri çizgisinin, trendi alınan serinin verilerinden sonra uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. |
| [getIntercept()](#getIntercept--) | Eğri çizgisinin y eksenini kestiği değeri belirtir. |
| [setIntercept(double value)](#setIntercept-double-) | Eğri çizgisinin y eksenini kestiği değeri belirtir. |
| [getDisplayEquation()](#getDisplayEquation--) | Eğri çizgisinin denkleminin grafikte (R^2 değeriyle aynı etikette) gösterilip gösterilmeyeceğini belirtir. |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Eğri çizgisinin denkleminin grafikte (R^2 değeriyle aynı etikette) gösterilip gösterilmeyeceğini belirtir. |
| [getOrder()](#getOrder--) | Polinom eğri çizgisinin derecesini belirtir. |
| [setOrder(byte value)](#setOrder-byte-) | Polinom eğri çizgisinin derecesini belirtir. |
| [getPeriod()](#getPeriod--) | Hareketli ortalama eğri çizgisi için periyodu belirtir. |
| [setPeriod(byte value)](#setPeriod-byte-) | Hareketli ortalama eğri çizgisi için periyodu belirtir. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Eğri çizgisinin R^2 değerinin grafikte (denklemin aynı etiketi içinde) gösterilip gösterilmeyeceğini belirtir. |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Eğri çizgisinin R^2 değerinin grafikte (denklemin aynı etiketi içinde) gösterilip gösterilmeyeceğini belirtir. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu eğri çizgisiyle ilişkili gösterge girişini temsil eder. Yalnızca okuma [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Eğim çizgisinin adını alır veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Eğim çizgisinin adını alır veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Eğim çizgisinin tipini alır veya ayarlar. Okuma/Yazma [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Döndürür:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Eğim çizgisinin tipini alır veya ayarlar. Okuma/Yazma [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Eğim çizgisinin biçimini temsil eder. Okuma/Yazma [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Eğim çizgisinin biçimini temsil eder. Okuma/Yazma [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Eğim çizgisinin, trendi alınan serinin verilerinden önce uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer sıfır veya pozitif bir sayı olmalıdır. Okuma/Yazma double.

**Döndürür:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Eğim çizgisinin, trendi alınan serinin verilerinden önce uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer sıfır veya pozitif bir sayı olmalıdır. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Eğim çizgisinin, trendi alınan serinin verilerinden sonra uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer sıfır veya pozitif bir sayı olmalıdır. Okuma/Yazma double.

**Döndürür:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Eğim çizgisinin, trendi alınan serinin verilerinden sonra uzandığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer sıfır veya pozitif bir sayı olmalıdır. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Eğim çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca eğri tipi exp, linear veya poly olduğunda desteklenir. Okuma/Yazma double.

**Döndürür:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Eğim çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca eğri tipi exp, linear veya poly olduğunda desteklenir. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Eğri denkleminin grafikte (R^2 değeriyle aynı etikette) gösterilip gösterilmeyeceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Eğri denkleminin grafikte (R^2 değeriyle aynı etikette) gösterilip gösterilmeyeceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Polinom eğri çizgisinin derecesini belirtir. Diğer eğri tipleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır. Okuma/Yazma byte.

**Döndürür:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Polinom eğri çizgisinin derecesini belirtir. Diğer eğri tipleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır. Okuma/Yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Hareketli ortalama eğri çizgisi için periyodu belirtir. Diğer eğri varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır. Okuma/Yazma byte.

**Döndürür:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Hareketli ortalama eğri çizgisi için periyodu belirtir. Diğer eğri varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır. Okuma/Yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Eğri çizgisinin R^2 değerinin grafikte (denklemin aynı etiketi içinde) gösterilip gösterilmeyeceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Eğri çizgisinin R^2 değerinin grafikte (denklemin aynı etiketi içinde) gösterilip gösterilmeyeceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Bu eğri çizgisiyle ilişkili gösterge girişini temsil eder. Yalnızca okuma [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)