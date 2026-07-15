---
title: ITrendline
second_title: Aspose.Slides for Android via Java API 參考
description: 類別代表圖表系列的趨勢線
type: docs
url: /zh-hant/com.aspose.slides/itrendline/
---
**All Implemented Interfaces:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

類別代表圖表系列的趨勢線
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | 取得或設定趨勢線的名稱。 |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | 取得或設定趨勢線的名稱。 |
| [getTrendlineType()](#getTrendlineType--) | 取得或設定趨勢線的類型。 |
| [setTrendlineType(int value)](#setTrendlineType-int-) | 取得或設定趨勢線的類型。 |
| [getFormat()](#getFormat--) | 表示趨勢線的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示趨勢線的格式。 |
| [getBackward()](#getBackward--) | 指定趨勢線在被趨勢化之系列資料之前延伸的類別數（或散佈圖上的單位）。 |
| [setBackward(double value)](#setBackward-double-) | 指定趨勢線在被趨勢化之系列資料之前延伸的類別數（或散佈圖上的單位）。 |
| [getForward()](#getForward--) | 指定趨勢線在被趨勢化之系列資料之後延伸的類別數（或散佈圖上的單位）。 |
| [setForward(double value)](#setForward-double-) | 指定趨勢線在被趨勢化之系列資料之後延伸的類別數（或散佈圖上的單位）。 |
| [getIntercept()](#getIntercept--) | 指定趨勢線應穿過 y 軸的值。 |
| [setIntercept(double value)](#setIntercept-double-) | 指定趨勢線應穿過 y 軸的值。 |
| [getDisplayEquation()](#getDisplayEquation--) | 指定趨勢線的方程式顯示於圖表上（與 Rsquaredvalue 同一標籤中）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 指定趨勢線的方程式顯示於圖表上（與 Rsquaredvalue 同一標籤中）。 |
| [getOrder()](#getOrder--) | 指定多項式趨勢線的階次。 |
| [setOrder(byte value)](#setOrder-byte-) | 指定多項式趨勢線的階次。 |
| [getPeriod()](#getPeriod--) | 指定移動平均趨勢線的週期。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 指定移動平均趨勢線的週期。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 指定趨勢線的 R 平方值顯示於圖表上（與方程式同一標籤中）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 指定趨勢線的 R 平方值顯示於圖表上（與方程式同一標籤中）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示與此趨勢線相關的圖例項目。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```


取得或設定趨勢線的名稱。可讀寫 String。

**傳回值:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```


取得或設定趨勢線的名稱。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```


取得或設定趨勢線的類型。可讀寫 [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int))。

**傳回值:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```


取得或設定趨勢線的類型。可讀寫 [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int))。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


表示趨勢線的格式。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**傳回值:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


表示趨勢線的格式。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```


指定趨勢線在被趨勢化之系列資料之前延伸的類別數（或散佈圖上的單位）。在散佈圖與非散佈圖上，該值應為非負值。可讀寫 double。

**傳回值:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```


指定趨勢線在被趨勢化之系列資料之前延伸的類別數（或散佈圖上的單位）。在散佈圖與非散佈圖上，該值應為非負值。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```


指定趨勢線在被趨勢化之系列資料之後延伸的類別數（或散佈圖上的單位）。在散佈圖與非散佈圖上，該值應為非負值。可讀寫 double。

**傳回值:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```


指定趨勢線在被趨勢化之系列資料之後延伸的類別數（或散佈圖上的單位）。在散佈圖與非散佈圖上，該值應為非負值。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```


指定趨勢線應穿過 y 軸的值。此屬性僅在趨勢線類型為 exp、linear 或 poly 時支援。可讀寫 double。

**傳回值:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```


指定趨勢線應穿過 y 軸的值。此屬性僅在趨勢線類型為 exp、linear 或 poly 時支援。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```


指定趨勢線的方程式顯示於圖表上（與 Rsquaredvalue 同一標籤中）。可讀寫 boolean。

**傳回值:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```


指定趨勢線的方程式顯示於圖表上（與 Rsquaredvalue 同一標籤中）。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```


指定多項式趨勢線的階次。對其他趨勢線類型此屬性會被忽略。值必須介於 2 與 6 之間。可讀寫 byte。

**傳回值:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```


指定多項式趨勢線的階次。對其他趨勢線類型此屬性會被忽略。值必須介於 2 與 6 之間。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```


指定移動平均趨勢線的週期。對其他趨勢線變體此屬性會被忽略。值必須介於 2 與 255 之間。可讀寫 byte。

**傳回值:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```


指定移動平均趨勢線的週期。對其他趨勢線變體此屬性會被忽略。值必須介於 2 與 255 之間。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```


指定趨勢線的 R 平方值顯示於圖表上（與方程式同一標籤中）。可讀寫 boolean。

**傳回值:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```


指定趨勢線的 R 平方值顯示於圖表上（與方程式同一標籤中）。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


表示與此趨勢線相關的圖例項目。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**傳回值:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)