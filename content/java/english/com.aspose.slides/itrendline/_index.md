---
title: ITrendline
second_title: Aspose.Slides for Java API Reference
description: Class represents trend line of chart series
type: docs
url: /com.aspose.slides/itrendline/
---
**All Implemented Interfaces:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Class represents trend line of chart series
## Methods

| Method | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Gets or sets name of the trendline. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Gets or sets name of the trendline. |
| [getTrendlineType()](#getTrendlineType--) | Gets or sets type of trend line. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Gets or sets type of trend line. |
| [getFormat()](#getFormat--) | Represents the format of the trend line. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the trend line. |
| [getBackward()](#getBackward--) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. |
| [setBackward(double value)](#setBackward-double-) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. |
| [getForward()](#getForward--) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. |
| [setForward(double value)](#setForward-double-) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. |
| [getIntercept()](#getIntercept--) | Specifies the value where the trendline shall cross the y axis. |
| [setIntercept(double value)](#setIntercept-double-) | Specifies the value where the trendline shall cross the y axis. |
| [getDisplayEquation()](#getDisplayEquation--) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). |
| [getOrder()](#getOrder--) | Specifies the order of the polynomial trend line. |
| [setOrder(byte value)](#setOrder-byte-) | Specifies the order of the polynomial trend line. |
| [getPeriod()](#getPeriod--) | Specifies the period of the trend line for a moving average trend line. |
| [setPeriod(byte value)](#setPeriod-byte-) | Specifies the period of the trend line for a moving average trend line. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Represents legend entry related with this trendline Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```


Gets or sets name of the trendline. Read/write String.

**Returns:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```


Gets or sets name of the trendline. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```


Gets or sets type of trend line. Read/write [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Returns:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```


Gets or sets type of trend line. Read/write [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Represents the format of the trend line. Read/write [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Represents the format of the trend line. Read/write [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```


Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double.

**Returns:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```


Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```


Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double.

**Returns:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```


Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```


Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double.

**Returns:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```


Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```


Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean.

**Returns:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```


Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```


Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte.

**Returns:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```


Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```


Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte.

**Returns:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```


Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```


Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean.

**Returns:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```


Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Represents legend entry related with this trendline Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
