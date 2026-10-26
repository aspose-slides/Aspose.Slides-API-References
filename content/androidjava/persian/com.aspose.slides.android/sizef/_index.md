---
title: SizeF
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاسی برای توصیف ابعاد عرض و ارتفاع در یک واحد دلخواه با مقادیر شناور.
type: docs
url: /fa/com.aspose.slides.android/sizef/
---
**Inheritance:**
java.lang.Object
```
public class SizeF
```

کلاسی برای توصیف ابعاد عرض و ارتفاع در یک واحد دلخواه با مقادیر شناور.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | یک نمونه جدید از SizeF ایجاد کنید. |

## متدها

| متد | توضیح |
| --- | --- |
| [getWidth()](#getWidth--) | عرض اندازه را دریافت کنید. |
| [getHeight()](#getHeight--) | ارتفاع اندازه را دریافت کنید. |
| [equals(Object obj)](#equals-java.lang.Object-) | بررسی می‌کند که آیا این اندازه با اندازه دیگری برابر است یا خیر. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | اندازه را به شکل رشته‌ای با قالب «WxH» برمی‌گرداند. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

یک نمونه جدید از SizeF ایجاد کنید.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض اندازه |
| height | float | ارتفاع اندازه |

### getWidth() {#getWidth--}
```
public float getWidth()
```

عرض اندازه را دریافت کنید.

**Returns:**
float - width

### getHeight() {#getHeight--}
```
public float getHeight()
```

ارتفاع اندازه را دریافت کنید.

**Returns:**
float - height

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

بررسی می‌کند که آیا این اندازه با اندازه دیگری برابر است یا خیر.

دو اندازه فقط زمانی برابر هستند که هر دو عرض و ارتفاع آنها یکسان باشد.

برای این منظور، مقادیر شناور عرض/ارتفاع تنها در صورتی یکسان در نظر گرفته می‌شوند که متد Float#floatToIntBits(float).floatToIntBits(float) مقدار صحیح (int) یکسانی را هنگام اعمال بر هر کدام بازگرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean -  true  if the objects were equal,  false  otherwise

### hashCode() {#hashCode--}
```
public int hashCode()
```

**Returns:**
int

### toString() {#toString--}
```
public String toString()
```

اندازه را به شکل رشته‌ای با قالب «WxH» برمی‌گرداند.

**Returns:**
java.lang.String - string representation of the size