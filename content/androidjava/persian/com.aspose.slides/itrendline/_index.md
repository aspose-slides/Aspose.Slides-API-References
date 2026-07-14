---
title: ITrendline
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاس نمایانگر خط روند سری نمودار
type: docs
url: /fa/com.aspose.slides/itrendline/
---
**All Implemented Interfaces:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

کلاس نمایانگر خط روند سری نمودار است
## Methods

| Method | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | دریافت یا تنظیم نام خط روند. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | دریافت یا تنظیم نام خط روند. |
| [getTrendlineType()](#getTrendlineType--) | دریافت یا تنظیم نوع خط روند. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | دریافت یا تنظیم نوع خط روند. |
| [getFormat()](#getFormat--) | نمایانگر قالب خط روند. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | نمایانگر قالب خط روند. |
| [getBackward()](#getBackward--) | تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند قبل از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. |
| [setBackward(double value)](#setBackward-double-) | تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند قبل از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. |
| [getForward()](#getForward--) | تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند پس از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. |
| [setForward(double value)](#setForward-double-) | تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند پس از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. |
| [getIntercept()](#getIntercept--) | مقداری را که خط روند باید محور y را قطع کند، مشخص می‌کند. |
| [setIntercept(double value)](#setIntercept-double-) | مقداری را که خط روند باید محور y را قطع کند، مشخص می‌کند. |
| [getDisplayEquation()](#getDisplayEquation--) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار Rsquaredvalue قرار دارد). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار Rsquaredvalue قرار دارد). |
| [getOrder()](#getOrder--) | ترتیب خط روند چندجمله‌ای را مشخص می‌کند. |
| [setOrder(byte value)](#setOrder-byte-) | ترتیب خط روند چندجمله‌ای را مشخص می‌کند. |
| [getPeriod()](#getPeriod--) | دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. |
| [setPeriod(byte value)](#setPeriod-byte-) | دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | نمایانگر ورودی افسانه مرتبط با این خط روند فقط خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

دریافت یا تنظیم نام خط روند. خواندنی/نوشتنی String.

**Returns:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

دریافت یا تنظیم نام خط روند. خواندنی/نوشتنی String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

دریافت یا تنظیم نوع خط روند. خواندنی/نوشتنی [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Returns:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

دریافت یا تنظیم نوع خط روند. خواندنی/نوشتنی [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

نمایانگر قالب خط روند. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

نمایانگر قالب خط روند. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند قبل از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. خواندنی/نوشتنی double.

**Returns:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند قبل از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. خواندنی/نوشتنی double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند پس از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. خواندنی/نوشتنی double.

**Returns:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

تعداد رده‌ها (یا واحدها در نمودار پراکنده) که خط روند پس از داده‌های سری مورد ترند شدن گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. خواندنی/نوشتنی double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

مقداری را که خط روند باید محور y را قطع کند، مشخص می‌کند. این ویژگی تنها زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. خواندنی/نوشتنی double.

**Returns:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

مقداری را که خط روند باید محور y را قطع کند، مشخص می‌کند. این ویژگی تنها زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. خواندنی/نوشتنی double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار Rsquaredvalue قرار دارد). خواندنی/نوشتنی boolean.

**Returns:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار Rsquaredvalue قرار دارد). خواندنی/نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

ترتیب خط روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. خواندنی/نوشتنی byte.

**Returns:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

ترتیب خط روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. خواندنی/نوشتنی byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. خواندنی/نوشتنی byte.

**Returns:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. خواندنی/نوشتنی byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). خواندنی/نوشتنی boolean.

**Returns:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). خواندنی/نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

نمایانگر ورودی افسانه مرتبط با این خط روند فقط خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)