---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: نمایندهٔ مقدار تنظیم شکل هندسی.
type: docs
url: /fa/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

نمایندهٔ مقدار تنظیم شکل هندسی است. این مقادیر شکل را تحت تأثیر قرار می‌دهند.
## متدها

| متد | توضیحات |
| --- | --- |
| [getRawValue()](#getRawValue--) | مقدار تنظیم را همان‌طور که است برمی‌گرداند یا تنظیم می‌کند. |
| [setRawValue(long value)](#setRawValue-long-) | مقدار تنظیم را همان‌طور که است برمی‌گرداند یا تنظیم می‌کند. |
| [getAngleValue()](#getAngleValue--) | مقدار را برمی‌گرداند یا تنظیم می‌کند و آن را به عنوان زاویهٔ درجه‌ای تفسیر می‌کند. |
| [setAngleValue(float value)](#setAngleValue-float-) | مقدار را برمی‌گرداند یا تنظیم می‌کند و آن را به عنوان زاویهٔ درجه‌ای تفسیر می‌کند. |
| [getName()](#getName--) | نام این مقدار تنظیم را برمی‌گرداند. |
| [getType()](#getType--) | نوع تنظیم شکل را برمی‌گرداند. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

مقدار تنظیم را همان‌طور که است برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**بازگشت:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

مقدار تنظیم را همان‌طور که است برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

مقدار را برمی‌گرداند یا تنظیم می‌کند و آن را به عنوان زاویهٔ درجه‌ای تفسیر می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

مقدار را برمی‌گرداند یا تنظیم می‌کند و آن را به عنوان زاویهٔ درجه‌ای تفسیر می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

نام این مقدار تنظیم را برمی‌گرداند. فقط‌خواندنی String.

**بازگشت:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

نوع تنظیم شکل را برمی‌گرداند. فقط‌خواندنی [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**بازگشت:**
int