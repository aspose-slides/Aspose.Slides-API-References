---
title: ParagraphFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: تحتوي هذه الفئة على خصائص تنسيق الفقرة.
type: docs
url: /ar/com.aspose.slides/paragraphformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

هذه الفئة تحتوي على خصائص تنسيق الفقرة. على عكس [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق الفقرة المعرفة للفقرة المحددة. وهذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام الطريقة [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) التي تُرجع كائنًا من نوع [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | يُنشئ نسخة جديدة من الفئة [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBullet()](#getBullet--) | يعيد تنسيق الرصاصة للفقرة. |
| [getDepth()](#getDepth--) | يعيد أو يعيّن عمق الفقرة. |
| [setDepth(short value)](#setDepth-short-) | يعيد أو يعيّن عمق الفقرة. |
| [getAlignment()](#getAlignment--) | يعيد أو يعيّن محاذاة النص في الفقرة دون وراثة. |
| [setAlignment(int value)](#setAlignment-int-) | يعيد أو يعيّن محاذاة النص في الفقرة دون وراثة. |
| [getSpaceWithin()](#getSpaceWithin--) | يعيد أو يعيّن مقدار المسافة بين الأسطر الأساسية في الفقرة. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | يعيد أو يعيّن مقدار المسافة بين الأسطر الأساسية في الفقرة. |
| [getSpaceBefore()](#getSpaceBefore--) | يعيد أو يعيّن مقدار المسافة قبل السطر الأول في الفقرة دون وراثة. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | يعيد أو يعيّن مقدار المسافة قبل السطر الأول في الفقرة دون وراثة. |
| [getSpaceAfter()](#getSpaceAfter--) | يعيد أو يعيّن مقدار المسافة بعد السطر الأخير في الفقرة دون وراثة. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | يعيد أو يعيّن مقدار المسافة بعد السطر الأخير في الفقرة دون وراثة. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | يحدد ما إذا كان يتم استخدام فاصل السطر شرق آسيا في الفقرة. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | يحدد ما إذا كان يتم استخدام فاصل السطر شرق آسيا في الفقرة. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. |
| [getLatinLineBreak()](#getLatinLineBreak--) | يحدد ما إذا كان يتم استخدام فاصل السطر اللاتيني في الفقرة. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | يحدد ما إذا كان يتم استخدام فاصل السطر اللاتيني في الفقرة. |
| [getHangingPunctuation()](#getHangingPunctuation--) | يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. |
| [getMarginLeft()](#getMarginLeft--) | يعيد أو يعيّن الهامش الأيسر في الفقرة دون وراثة. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | يعيد أو يعيّن الهامش الأيسر في الفقرة دون وراثة. |
| [getMarginRight()](#getMarginRight--) | يعيد أو يعيّن الهامش الأيمن في الفقرة دون وراثة. |
| [setMarginRight(float value)](#setMarginRight-float-) | يعيد أو يعيّن الهامش الأيمن في الفقرة دون وراثة. |
| [getIndent()](#getIndent--) | يعيد أو يعيّن إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. |
| [setIndent(float value)](#setIndent-float-) | يعيد أو يعيّن إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. |
| [getDefaultTabSize()](#getDefaultTabSize--) | يعيد أو يعيّن حجم الجدولة الافتراضي دون وراثة. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | يعيد أو يعيّن حجم الجدولة الافتراضي دون وراثة. |
| [getTabs()](#getTabs--) | يعيد فواصل الجدولة للفقرة. |
| [getFontAlignment()](#getFontAlignment--) | يعيد أو يعيّن محاذاة الخط في الفقرة دون وراثة. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | يعيد أو يعيّن محاذاة الخط في الفقرة دون وراثة. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | يعيد تنسيق الجزء الافتراضي للفقرة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الفقرة الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

يُنشئ نسخة جديدة من الفئة [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

يعيد تنسيق الرصادة للفقرة. للقراءة فقط [IBulletFormat](../../com.aspose.slides/ibulletformat).

**الإرجاع:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

يعيد أو يعيّن عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة  short .

**الإرجاع:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

يعيد أو يعيّن عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة  short .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

يعيد أو يعيّن محاذاة النص في الفقرة دون وراثة. قراءة/كتابة [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a PPTX file
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accessing first slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accessing the first and second placeholder in the slide and typecasting it as AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Change the text in both placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Getting the first paragraph of the placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligning the text paragraph to center
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing the presentation as a PPTX file
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

يعيد أو يعيّن محاذاة النص في الفقرة دون وراثة. قراءة/كتابة [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation يمثل ملف PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // الوصول إلى الشريحة الأولى
>      ISlide slide = pres.getSlides().get_Item(0);
>      // الوصول إلى العنصر النائب الأول والثاني في الشريحة وتحويله إلى AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // تغيير النص في كلا العنصرين النائبين
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // الحصول على الفقرة الأولى من العناصر النائبة
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // محاذاة فقرة النص إلى الوسط
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // كتابة العرض التقديمي كملف PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

يعيد أو يعيّن مقدار المسافة بين الأسطر الأساسية في الفقرة. القيمة الموجبة تعني نسبة مئوية، والسالبة تعني حجم بالنقاط. لا تطبيق وراثة. قراءة/كتابة  float .

**الإرجاع:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

يعيد أو يعيّن مقدار المسافة بين الأسطر الأساسية في الفقرة. القيمة الموجبة تعني نسبة مئوية، والسالبة تعني حجم بالنقاط. لا تطبيق وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

يعيد أو يعيّن مقدار المسافة قبل السطر الأول في الفقرة دون وراثة. القيمة الموجبة تحدد نسبة مئوية من حجم الخط للمسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقاط. قراءة/كتابة  float .

**الإرجاع:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

يعيد أو يعيّن مقدار المسافة قبل السطر الأول في الفقرة دون وراثة. القيمة الموجبة تحدد نسبة مئوية من حجم الخط للمسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقاط. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

يعيد أو يعيّن مقدار المسافة بعد السطر الأخير في الفقرة دون وراثة. القيمة الموجبة تحدد نسبة مئوية من حجم الخط للمسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقاط. قراءة/كتابة  float .

**الإرجاع:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

يعيد أو يعيّن مقدار المسافة بعد السطر الأخير في الفقرة دون وراثة. القيمة الموجبة تحدد نسبة مئوية من حجم الخط للمسافة البيضاء. القيمة السالبة تحدد حجم المسافة البيضاء بالنقاط. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

يحدد ما إذا كان يتم استخدام فاصل السطر شرق آسيا في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

يحدد ما إذا كان يتم استخدام فاصل السطر شرق آسيا في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

يحدد ما إذا كان يتم استخدام فاصل السطر اللاتيني في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

يحدد ما إذا كان يتم استخدام فاصل السطر اللاتيني في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. لا تطبيق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

يعيد أو يعيّن الهامش الأيسر في الفقرة دون وراثة. قراءة/كتابة  float .

**الإرجاع:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

يعيد أو يعيّن الهامش الأيسر في الفقرة دون وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

يعيد أو يعيّن الهامش الأيمن في الفقرة دون وراثة. قراءة/كتابة  float .

**الإرجاع:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

يعيد أو يعيّن الهامش الأيمن في الفقرة دون وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public final float getIndent()
```

يعيد أو يعيّن إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. قراءة/كتابة  float .

**الإرجاع:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

يعيد أو يعيّن إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

يعيد أو يعيّن حجم الجدولة الافتراضي دون وراثة. قراءة/كتابة  float .

**الإرجاع:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

يعيد أو يعيّن حجم الجدولة الافتراضي دون وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

يعيد فواصل الجدولة للفقرة. لا تطبيق وراثة. للقراءة فقط [ITabCollection](../../com.aspose.slides/itabcollection).

**الإرجاع:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

يعيد أو يعيّن محاذاة الخط في الفقرة دون وراثة. قراءة/كتابة [FontAlignment](../../com.aspose.slides/fontalignment).

**الإرجاع:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

يعيد أو يعيّن محاذاة الخط في الفقرة دون وراثة. قراءة/كتابة [FontAlignment](../../com.aspose.slides/fontalignment).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

يعيد تنسيق الجزء الافتراضي للفقرة. لا تطبيق وراثة. للقراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الفقرة الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> هذا المثال يوضح الحصول على بعض خصائص تنسيق الفقرة الفعّالة.
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

**الإرجاع:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long