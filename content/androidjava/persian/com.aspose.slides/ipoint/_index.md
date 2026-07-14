---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: نمایش نقطه انیمیشن.
type: docs
url: /fa/com.aspose.slides/ipoint/
---```
public interface IPoint
```

نمایش نقطه انیمیشن.

## متدها

| متد | توضیح |
| --- | --- |
| [getTime()](#getTime--) | نمایش مقدار زمان. |
| [setTime(float value)](#setTime-float-) | نمایش مقدار زمان. |
| [getValue()](#getValue--) | نمایش مقدار نقطه. |
| [setValue(Object value)](#setValue-java.lang.Object-) | نمایش مقدار نقطه. |
| [getFormula()](#getFormula--) | فرمول‌ها درون مقادیر و ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاع به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط host) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | فرمول‌ها درون مقادیر و ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاع به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط host) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String. |

### getTime() {#getTime--}
```
public abstract float getTime()
```

نمایش مقدار زمان. خواندنی/نوشتنی float.

**بازگشت:**
float

### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

نمایش مقدار زمان. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

نمایش مقدار نقطه. فقط: bool, ColorFormat, float, int, string. خواندنی/نوشتنی Object.

**بازگشت:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

نمایش مقدار نقطه. فقط: bool, ColorFormat, float, int, string. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

فرمول‌ها درون مقادیر و ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاع به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط host) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

فرمول‌ها درون مقادیر و ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاع به ویژگی‌ها (ویژگی‌های پشتیبانی‌شده توسط host) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |