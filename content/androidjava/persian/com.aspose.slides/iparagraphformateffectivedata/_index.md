---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /fa/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر پاراگراف است.

--------------------

این رابط همراه با رابط [IParagraphFormat](../../com.aspose.slides/iparagraphformat) برای برگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getBullet()](#getBullet--) | یک قالب گلوله‌ای از پاراگراف را برمی‌گرداند. |
| [getDepth()](#getDepth--) | عمق یک پاراگراف را برمی‌گرداند. |
| [getAlignment()](#getAlignment--) | ترازیابی متن در یک پاراگراف را برمی‌گرداند. |
| [getSpaceWithin()](#getSpaceWithin--) | مقدار فاصله بین خطوط پایه در یک پاراگراف را برمی‌گرداند. |
| [getSpaceBefore()](#getSpaceBefore--) | مقدار فاصله قبل از خط اول در یک پاراگراف را برمی‌گرداند. |
| [getSpaceAfter()](#getSpaceAfter--) | مقدار فاصله پس از آخرین خط در یک پاراگراف را برمی‌گرداند. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | تعیین می‌کند که آیا شکست خط شرق آسیا در یک پاراگراف استفاده می‌شود یا خیر. |
| [getRightToLeft()](#getRightToLeft--) | تعیین می‌کند که آیا نوشتن راست به چپ در یک پاراگراف استفاده می‌شود یا خیر. |
| [getLatinLineBreak()](#getLatinLineBreak--) | تعیین می‌کند که آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود یا خیر. |
| [getHangingPunctuation()](#getHangingPunctuation--) | تعیین می‌کند که آیا نقطه‌گذاری معلق در یک پاراگراف استفاده می‌شود یا خیر. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ در یک پاراگراف را برمی‌گرداند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست در یک پاراگراف را برمی‌گرداند. |
| [getIndent()](#getIndent--) | تورفتگی خط اول/تورفتگی معلق پاراگراف را برمی‌گرداند. |
| [getDefaultTabSize()](#getDefaultTabSize--) | اندازه تب پیش‌فرض را برمی‌گرداند. |
| [getTabs()](#getTabs--) | تب‌های یک پاراگراف را برمی‌گرداند. |
| [getFontAlignment()](#getFontAlignment--) | یک ترازبندی فونت در یک پاراگراف را برمی‌گرداند. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | قالب بخش پیش‌فرض یک پاراگراف را برمی‌گرداند. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


یک قالب گلوله‌ای از پاراگراف را برمی‌گرداند. فقط خواندنی [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


عمق یک پاراگراف را برمی‌گرداند. فقط خواندنی short.

**Returns:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


ترازیابی متن در یک پاراگراف را برمی‌گرداند. فقط خواندنی [TextAlignment](../../com.aspose.slides/textalignment).

**Returns:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


مقدار فاصله بین خطوط پایه در یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**Returns:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


مقدار فاصله قبل از خط اول در یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**Returns:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


مقدار فاصله پس از آخرین خط در یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**Returns:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


تعیین می‌کند که آیا شکست خط شرق آسیا در یک پاراگراف استفاده می‌شود یا خیر. فقط خواندنی boolean.

**Returns:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


تعیین می‌کند که آیا نوشتن راست به چپ در یک پاراگراف استفاده می‌شود یا خیر. فقط خواندنی boolean.

**Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


تعیین می‌کند که آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود یا خیر. فقط خواندنی boolean.

**Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


تعیین می‌کند که آیا نقطه‌گذاری معلق در یک پاراگراف استفاده می‌شود یا خیر. فقط خواندنی boolean.

**Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


حاشیه چپ در یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


حاشیه راست در یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


تورفتگی خط اول/تورفتگی معلق پاراگراف را برمی‌گرداند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. فقط خواندنی float.

**Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


اندازه تب پیش‌فرض را برمی‌گرداند. فقط خواندنی float.

**Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


تب‌های یک پاراگراف را برمی‌گرداند. فقط خواندنی ITabEffectiveData[].

**Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


یک ترازبندی فونت در یک پاراگراف را برمی‌گرداند. فقط خواندنی [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


قالب بخش پیش‌فرض یک پاراگراف را برمی‌گرداند. فقط خواندنی [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)