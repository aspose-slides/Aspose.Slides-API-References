---
title: IAdjustValue
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مقدار تنظیم شکل هندسی را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

مقدار تنظیم یک شکل هندسی را نمایندگی می‌کند. این مقادیر بر فرم شکل تأثیر می‌گذارند.
## متدها

| متد | توضیحات |
| --- | --- |
| [getRawValue()](#getRawValue--) | مقدار تنظیم را همان‌گونه که هست برمی‌گرداند یا تنظیم می‌کند. |
| [setRawValue(long value)](#setRawValue-long-) | مقدار تنظیم را همان‌گونه که هست برمی‌گرداند یا تنظیم می‌کند. |
| [getAngleValue()](#getAngleValue--) | مقدار را برمی‌گرداند یا تنظیم می‌کند، به‌عنوان زاویه‌ای بر حسب درجه تفسیر می‌شود. |
| [setAngleValue(float value)](#setAngleValue-float-) | مقدار را برمی‌گرداند یا تنظیم می‌کند، به‌عنوان زاویه‌ای بر حسب درجه تفسیر می‌شود. |
| [getName()](#getName--) | نام این مقدار تنظیم را برمی‌گرداند. |
| [getType()](#getType--) | نوع تنظیم شکل را برمی‌گرداند. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

مقدار تنظیم را همان‌گونه که هست برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**بازگشت:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

مقدار تنظیم را همان‌گونه که هست برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

مقدار را برمی‌گرداند یا تنظیم می‌کند، به‌عنوان زاویه‌ای بر حسب درجه تفسیر می‌شود. خواندنی/نوشتنی float.

**بازگشت:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

مقدار را برمی‌گرداند یا تنظیم می‌کند، به‌عنوان زاویه‌ای بر حسب درجه تفسیر می‌شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

نام این مقدار تنظیم را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

نوع تنظیم شکل را برمی‌گرداند. فقط-خواندنی [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**بازگشت:**
int