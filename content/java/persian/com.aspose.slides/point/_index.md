---
title: Point
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر نقطهٔ انیمیشن.
type: docs
url: /fa/com.aspose.slides/point/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

نمایش نقطهٔ انیمیشن.
## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) | سازنده پیش‌فرض. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | ایجاد نقطهٔ انیمیشن با زمان، مقدار و فرمول. |
## متدها

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | نمایانگر مقدار زمان. |
| [setTime(float value)](#setTime-float-) | نمایانگر مقدار زمان. |
| [getValue()](#getValue--) | نمایانگر مقدار نقطه. |
| [setValue(Object value)](#setValue-java.lang.Object-) | نمایانگر مقدار نقطه. |
| [getFormula()](#getFormula--) | فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از ترکیب این‌ها ساخته شوند: عملگرهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (مد) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از ترکیب این‌ها ساخته شوند: عملگرهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (مد) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String. |
### Point() {#Point--}
```
public Point()
```

سازنده پیش‌فرض.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

ایجاد نقطهٔ انیمیشن با زمان، مقدار و فرمول.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| time | float | مقدار زمان. |
| value | java.lang.Object | مقدار نقطه. |
| formula | java.lang.String | فرمول. |

### getTime() {#getTime--}
```
public final float getTime()
```

نمایانگر مقدار زمان. خواندنی/نوشتنی float.

**باز می‌گردد:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

نمایانگر مقدار زمان. خواندنی/نوشتنی float.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

نمایانگر مقدار نقطه. فقط: bool, ColorFormat, float, int, string. خواندنی/نوشتنی Object.

**باز می‌گردد:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

نمایانگر مقدار نقطه. فقط: bool, ColorFormat, float, int, string. خواندنی/نوشتنی Object.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از ترکیب این‌ها ساخته شوند: عملگرهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (مد) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String.

**باز می‌گردد:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

فرمول‌ها در مقادیر، ویژگی‌های from، to، by می‌توانند از ترکیب این‌ها ساخته شوند: عملگرهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (مد) ثابت‌ها: 'pi' 'e' عملگرهای شرطی: 'abs', 'min', 'max', '?' (if) عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!' عملگرهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |