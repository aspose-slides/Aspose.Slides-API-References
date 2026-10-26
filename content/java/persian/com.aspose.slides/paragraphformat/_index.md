---
title: ParagraphFormat
second_title: Aspose.Slides برای Java مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است.
type: docs
url: /fa/com.aspose.slides/paragraphformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

این کلاس حاوی ویژگی‌های قالب‌بندی پاراگراف است. برخلاف [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

از این کلاس برای دریافت و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری دریافت می‌کنید که به معنای "تعریف‌نشده" هستند.

برای به‌دست‌آوردن مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از متد [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) استفاده کنید که یک نمونه [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) را برمی‌گرداند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | یک نمونه جدید از کلاس [ParagraphFormat](../../com.aspose.slides/paragraphformat) را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBullet()](#getBullet--) | قالب بولت پاراگراف را باز می‌گرداند. |
| [getDepth()](#getDepth--) | عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [setDepth(short value)](#setDepth-short-) | عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | تراز متن در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [setAlignment(int value)](#setAlignment-int-) | تراز متن در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceWithin()](#getSpaceWithin--) | مقدار فاصله بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | مقدار فاصله بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceBefore()](#getSpaceBefore--) | مقدار فاصله قبل از اولین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | مقدار فاصله قبل از اولین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [getSpaceAfter()](#getSpaceAfter--) | مقدار فاصله پس از آخرین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | مقدار فاصله پس از آخرین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | تعیین می‌کند که آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا خیر. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | تعیین می‌کند که آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا خیر. |
| [getRightToLeft()](#getRightToLeft--) | تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. |
| [getLatinLineBreak()](#getLatinLineBreak--) | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. |
| [getHangingPunctuation()](#getHangingPunctuation--) | تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. |
| [getMarginLeft()](#getMarginLeft--) | فاصله‌چپ در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | فاصله‌چپ در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | فاصله‌راست در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(float value)](#setMarginRight-float-) | فاصله‌راست در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [getIndent()](#getIndent--) | تو پرت (indent) خط اول/تو پرت (hanging) پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setIndent(float value)](#setIndent-float-) | تو پرت (indent) خط اول/تو پرت (hanging) پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getDefaultTabSize()](#getDefaultTabSize--) | اندازه پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | اندازه پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. |
| [getTabs()](#getTabs--) | تب‌های یک پاراگراف را باز می‌گرداند. |
| [getFontAlignment()](#getFontAlignment--) | تراز فونت در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | تراز فونت در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | قالب پیش‌فرض بخش یک پاراگراف را باز می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر قالب‌بندی پاراگراف را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

یک نمونه جدید از کلاس [ParagraphFormat](../../com.aspose.slides/paragraphformat) را مقداردهی اولیه می‌کند.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

قالب بولت پاراگراف را باز می‌گرداند. فقط-خواندنی [IBulletFormat](../../com.aspose.slides/ibulletformat).

**بازمی‌گردد:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنای مقدار تعریف‌نشده است. خواندن/نوشتن short .

**بازمی‌گردد:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

عمق پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنای مقدار تعریف‌نشده است. خواندن/نوشتن short .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

تراز متن در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```markdown
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // دسترسی به اسلاید اول
>      ISlide slide = pres.getSlides().get_Item(0);
>      // دسترسی به اولین و دومین جای‌دار در اسلاید و تبدیل نوع آن به AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // تغییر متن در هر دو جای‌دار
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // دریافت اولین پاراگراف از جای‌دارها
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // تراز کردن پاراگراف متن به مرکز
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // ذخیرهٔ ارائه به‌صورت فایل PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گردد:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

تراز متن در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // یک شی Presentation می‌سازد که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // دسترسی به اسلاید اول
>      ISlide slide = pres.getSlides().get_Item(0);
>      // دسترسی به اولین و دومین جای‌دار در اسلاید و تبدیل نوع آن به AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // تغییر متن در هر دو جای‌دار
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // دریافت اولین پاراگراف از جای‌دارها
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // تراز کردن پاراگراف متن به مرکز
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // ذخیرهٔ ارائه به‌صورت فایل PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

مقدار فاصله بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنای درصد، مقدار منفی به معنای اندازه به نقطه است. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

مقدار فاصله بین خطوط پایه در یک پاراگراف را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنای درصد، مقدار منفی به معنای اندازه به نقطه است. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

مقدار فاصله قبل از اولین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازه فونت را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

مقدار فاصله قبل از اولین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازه فونت را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

مقدار فاصله پس از آخرین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازه فونت را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

مقدار فاصله پس از آخرین خط در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازه فونت را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را به نقطه مشخص می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

تعیین می‌کند که آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گردد:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

تعیین می‌کند که آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گردد:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گردد:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گردد:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

فاصله‌چپ در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

فاصله‌چپ در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

فاصله‌راست در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

فاصله‌راست در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public final float getIndent()
```

تو پرت (indent) خط اول/تو پرت (hanging) پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. تو پرت معلق می‌تواند با مقادیر منفی تعریف شود. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

تو پرت (indent) خط اول/تو پرت (hanging) پاراگراف را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. تو پرت معلق می‌تواند با مقادیر منفی تعریف شود. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

اندازه پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**بازمی‌گردد:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

اندازه پیش‌فرض تب را بدون ارث‌بری باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

تب‌های یک پاراگراف را باز می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ITabCollection](../../com.aspose.slides/itabcollection).

**بازمی‌گردد:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

تراز فونت در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [FontAlignment](../../com.aspose.slides/fontalignment).

**بازمی‌گردد:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

تراز فونت در یک پاراگراف بدون ارث‌بری را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [FontAlignment](../../com.aspose.slides/fontalignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

قالب پیش‌فرض بخش یک پاراگراف را باز می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IPortionFormat](../../com.aspose.slides/iportionformat).

**بازمی‌گردد:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

داده‌های مؤثر قالب‌بندی پاراگراف را با اعمال ارث‌بری دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گردد:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گردد:**
long