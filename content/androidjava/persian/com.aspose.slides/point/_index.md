---
title: Point
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش نقطه انیمیشن.
type: docs
url: /fa/com.aspose.slides/point/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

نمایش نقطه انیمیشن.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [Point()](#Point--) | سازنده پیش‌فرض. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | ایجاد نقطه انیمیشن با زمان، مقدار و فرمول. |

## متدها

| متد | توضیح |
| --- | --- |
| [getTime()](#getTime--) | نمایش مقدار زمان. |
| [setTime(float value)](#setTime-float-) | نمایش مقدار زمان. |
| [getValue()](#getValue--) | نمایش مقدار نقطه. |
| [setValue(Object value)](#setValue-java.lang.Object-) | نمایش مقدار نقطه. |
| [getFormula()](#getFormula--) | فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: عملگرهای حسابی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندن/نوشتن String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | فرمول‌ها در مقادیر, ویژگی‌های from, to, by می‌توانند از این‌ها ساخته شوند: عملگرهای حسابی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندن/نوشتن String. |

### Point() {#Point--}
```
public Point()
```

سازنده پیش‌فرض.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

ایجاد نقطه انیمیشن با زمان، مقدار و فرمول.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| time | float | مقدار زمان. |
| value | java.lang.Object | مقدار نقطه. |
| formula | java.lang.String | فرمول. |

### getTime() {#getTime--}
```
public final float getTime()
```

نمایش مقدار زمان. خواندن/نوشتن float.

**بازگشت:**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

نمایش مقدار زمان. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

نمایش مقدار نقطه. فقط: bool, ColorFormat, float, int, string. خواندن/نوشتن Object.

**بازگشت:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

نمایش مقدار نقطه. فقط: bool, ColorFormat, float, int, string. خواندن/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: عملگرهای حسابی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: عملگرهای حسابی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |