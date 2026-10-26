---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: نمایانگر نقطهٔ انیمیشن.
type: docs
url: /fa/com.aspose.slides/ipoint/
---```
public interface IPoint
```

نمایانگر نقطهٔ انیمیشن.
## متدها

| متد | توضیح |
| --- | --- |
| [getTime()](#getTime--) | نمایش مقدار زمان. |
| [setTime(float value)](#setTime-float-) | نمایش مقدار زمان. |
| [getValue()](#getValue--) | نمایش مقدار نقطه. |
| [setValue(Object value)](#setValue-java.lang.Object-) | نمایش مقدار نقطه. |
| [getFormula()](#getFormula--) | فرمول‌ها درون مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | فرمول‌ها درون مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```


نمایش مقدار زمان. خواندنی/نوشتنی float.

**بازگرداندن:**
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


نمایش مقدار نقطه. تنها: bool, ColorFormat, float, int, string. خواندنی/نوشتنی Object.

**بازگرداندن:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


نمایش مقدار نقطه. تنها: bool, ColorFormat, float, int, string. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


فرمول‌ها درون مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


فرمول‌ها درون مقادیر، ویژگی‌های from، to، by می‌توانند از این‌ها ساخته شوند: اپراتورهای ریاضی استاندارد: '+', '-', '*', '/', '^', '%' (mod) ثابت‌ها: 'pi' 'e' اپراتورهای شرطی: 'abs', 'min', 'max', '?' (if) اپراتورهای مقایسه: '==', '>=', '', '!=', '!' اپراتورهای مثلثاتی: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' لگاریتم طبیعی 'ln()' ارجاعات ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان) برای مثال: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |