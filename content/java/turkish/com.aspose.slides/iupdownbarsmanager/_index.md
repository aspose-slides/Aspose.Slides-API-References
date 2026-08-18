---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Referansı
description: Satır veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar.
type: docs
url: /tr/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Satır veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Yukarı çubukların biçimini döndürür. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Aşağı çubukların biçimini döndürür. |
| [hasUpDownBars()](#hasUpDownBars--) | Grafiğin yukarı/aşağı çubuklarına sahip olup olmadığını belirler. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Grafiğin yukarı/aşağı çubuklarına sahip olup olmadığını belirler. |
| [getGapWidth()](#getGapWidth--) | Boşluk genişliğini döndürür veya ayarlar. |
| [setGapWidth(int value)](#setGapWidth-int-) | Boşluk genişliğini döndürür veya ayarlar. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Yukarı çubukların biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Aşağı çubukların biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Grafiğin yukarı/aşağı çubuklarına sahip olup olmadığını belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Grafiğin yukarı/aşağı çubuklarına sahip olup olmadığını belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Boşluk genişliğini döndürür veya ayarlar. Okunur/Yazılabilir int.

**Döndürür:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Boşluk genişliğini döndürür veya ayarlar. Okunur/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |