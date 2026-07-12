---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /tr/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Satır veya hisse senedi grafiğinin yükselme/düşme çubuklarına erişim sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Yukarı çubuklarının biçimini döndürür. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Aşağı çubuklarının biçimini döndürür. |
| [hasUpDownBars()](#hasUpDownBars--) | Grafiğin yükselme/düşme çubukları olup olmadığını belirler. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Grafiğin yükselme/düşme çubukları olup olmadığını belirler. |
| [getGapWidth()](#getGapWidth--) | Boşluk genişliğini alır ya da ayarlar. |
| [setGapWidth(int value)](#setGapWidth-int-) | Boşluk genişliğini alır ya da ayarlar. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Yukarı çubuklarının biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Aşağı çubuklarının biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Grafiğin yükselme/düşme çubukları olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Grafiğin yükselme/düşme çubukları olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Boşluk genişliğini alır ya da ayarlar. Okuma/yazma int.

**Döndürür:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Boşluk genişliğini alır ya da ayarlar. Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |