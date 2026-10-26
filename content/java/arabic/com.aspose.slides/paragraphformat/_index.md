---
title: ParagraphFormat
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: هذا الصنف يحتوي على خصائص تنسيق الفقرة.
type: docs
url: /ar/com.aspose.slides/paragraphformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

هذا الصنف يحتوي على خصائص تنسيق الفقرة. على عكس [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)، جميع خصائص هذا الصنف قابلة للكتابة.

--------------------

يُستخدم هذا الصنف لإرجاع وتعديل خصائص تنسيق الفقرة المحددة للفقرة المعينة. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) التي تُعيد مثالاً من [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | ينشئ مثالاً جديداً من صنف [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBullet()](#getBullet--) | يعيد تنسيق الفتلة للفقرة. |
| [getDepth()](#getDepth--) | يعيد أو يضبط عمق الفقرة. |
| [setDepth(short value)](#setDepth-short-) | يعيد أو يضبط عمق الفقرة. |
| [getAlignment()](#getAlignment--) | يعيد أو يضبط محاذاة النص في فقرة بدون وراثة. |
| [setAlignment(int value)](#setAlignment-int-) | يعيد أو يضبط محاذاة النص في فقرة بدون وراثة. |
| [getSpaceWithin()](#getSpaceWithin--) | يعيد أو يضبط مقدار المسافة بين الخطوط الأساسية في الفقرة. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | يعيد أو يضبط مقدار المسافة بين الخطوط الأساسية في الفقرة. |
| [getSpaceBefore()](#getSpaceBefore--) | يعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة بدون وراثة. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | يعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة بدون وراثة. |
| [getSpaceAfter()](#getSpaceAfter--) | يعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة بدون وراثة. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | يعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة بدون وراثة. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | يحدد ما إذا كان فاصل السطر الشرق-آسيوي مستخدماً في الفقرة. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | يحدد ما إذا كان فاصل السطر الشرق-آسيوي مستخدماً في الفقرة. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان الكتابة من اليمين إلى اليسار مستخدمة في الفقرة. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | يحدد ما إذا كان الكتابة من اليمين إلى اليسار مستخدمة في الفقرة. |
| [getLatinLineBreak()](#getLatinLineBreak--) | يحدد ما إذا كان فاصل السطر اللاتيني مستخدماً في الفقرة. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | يحدد ما إذا كان فاصل السطر اللاتيني مستخدماً في الفقرة. |
| [getHangingPunctuation()](#getHangingPunctuation--) | يحدد ما إذا كانت علامات الترقيم المتدلية مستخدمة في الفقرة. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | يحدد ما إذا كانت علامات الترقيم المتدلية مستخدمة في الفقرة. |
| [getMarginLeft()](#getMarginLeft--) | يعيد أو يضبط الهامش الأيسر في فقرة بدون وراثة. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | يعيد أو يضبط الهامش الأيسر في فقرة بدون وراثة. |
| [getMarginRight()](#getMarginRight--) | يعيد أو يضبط الهامش الأيمن في فقرة بدون وراثة. |
| [setMarginRight(float value)](#setMarginRight-float-) | يعيد أو يضبط الهامش الأيمن في فقرة بدون وراثة. |
| [getIndent()](#getIndent--) | يعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة بدون وراثة. |
| [setIndent(float value)](#setIndent-float-) | يعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة بدون وراثة. |
| [getDefaultTabSize()](#getDefaultTabSize--) | يعيد أو يضبط حجم التبويب الافتراضي بدون وراثة. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | يعيد أو يضبط حجم التبويب الافتراضي بدون وراثة. |
| [getTabs()](#getTabs--) | يعيد تبويبات الفقرة. |
| [getFontAlignment()](#getFontAlignment--) | يعيد أو يضبط محاذاة الخط في فقرة بدون وراثة. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | يعيد أو يضبط محاذاة الخط في فقرة بدون وراثة. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | يعيد تنسيق الجزء الافتراضي للفقرة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الفقرة الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

ينشئ مثالاً جديداً من صنف [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

يعيد تنسيق الفتلة للفقرة. للقراءة فقط [IBulletFormat](../../com.aspose.slides/ibulletformat).

**الإرجاع:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

يعيد أو يضبط عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة  short .

**الإرجاع:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

يعيد أو يضبط عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة  short .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

يعيد أو يضبط محاذاة النص في فقرة بدون وراثة. قراءة/كتابة [TextAlignment](../../com.aspose.slides/textalignment).

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
>      // محاذاة فقرة النص إلى المركز
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //كتابة العرض التقديمي كملف PPTX
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

يعيد أو يضبط محاذاة النص في فقرة بدون وراثة. قراءة/كتابة [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation يمثل ملف PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // الوصول إلى الشريحة الأولى
>      ISlide slide = pres.getSlides().get_Item(0);
>      // الوصول إلى العنصر النائب الأول والثاني في الشريحة وتحويلهما إلى AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // تغيير النص في كلا العنصرين النائبين
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // الحصول على الفقرة الأولى من العناصر النائبة
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // محاذاة فقرة النص إلى المركز
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //كتابة العرض التقديمي كملف PPTX
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

يعيد أو يضبط مقدار المسافة بين الخطوط الأساسية في الفقرة. القيمة الموجبة تعني نسبة مئوية، والسالبة حجم بالنقاط. لا يتم تطبيق الوراثة. قراءة/كتابة  float .

**الإرجاع:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

يعيد أو يضبط مقدار المسافة بين الخطوط الأساسية في الفقرة. القيمة الموجبة تعني نسبة مئوية، والسالبة حجم بالنقاط. لا يتم تطبيق الوراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

يعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة بدون وراثة. القيمة الموجبة تحدد نسبة حجم الخط التي يجب أن يكون عليها الفراغ. القيمة السالبة تحدد حجم الفراغ بالنقاط. قراءة/كتابة  float .

**الإرجاع:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

يعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة بدون وراثة. القيمة الموجبة تحدد نسبة حجم الخط التي يجب أن يكون عليها الفراغ. القيمة السالبة تحدد حجم الفراغ بالنقاط. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

يعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة بدون وراثة. القيمة الموجبة تحدد نسبة حجم الخط التي يجب أن يكون عليها الفراغ. القيمة السالبة تحدد حجم الفراغ بالنقاط. قراءة/كتابة  float .

**الإرجاع:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

يعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة بدون وراثة. القيمة الموجبة تحدد نسبة حجم الخط التي يجب أن يكون عليها الفراغ. القيمة السالبة تحدد حجم الفراغ بالنقاط. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

يحدد ما إذا كان فاصل السطر الشرق-آسيوي مستخدماً في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

يحدد ما إذا كان فاصل السطر الشرق-آسيوي مستخدماً في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

يحدد ما إذا كانت الكتابة من اليمين إلى اليسار مستخدمة في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

يحدد ما إذا كانت الكتابة من اليمين إلى اليسار مستخدمة في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

يحدد ما إذا كان فاصل السطر اللاتيني مستخدماً في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

يحدد ما إذا كان فاصل السطر اللاتيني مستخدماً في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

يحدد ما إذا كانت علامات الترقيم المتدلية مستخدمة في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

يحدد ما إذا كانت علامات الترقيم المتدلية مستخدمة في الفقرة. لا يتم تطبيق الوراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

يعيد أو يضبط الهامش الأيسر في فقرة بدون وراثة. قراءة/كتابة  float .

**الإرجاع:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

يعيد أو يضبط الهامش الأيسر في فقرة بدون وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

يعيد أو يضبط الهامش الأيمن في فقرة بدون وراثة. قراءة/كتابة  float .

**الإرجاع:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

يعيد أو يضبط الهامش الأيمن في فقرة بدون وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

يعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة بدون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سلبية. قراءة/كتابة  float .

**الإرجاع:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

يعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة بدون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سلبية. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

يعيد أو يضبط حجم التبويب الافتراضي بدون وراثة. قراءة/كتابة  float .

**الإرجاع:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

يعيد أو يضبط حجم التبويب الافتراضي بدون وراثة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

يعيد تبويبات الفقرة. لا يتم تطبيق الوراثة. للقراءة فقط [ITabCollection](../../com.aspose.slides/itabcollection).

**الإرجاع:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

يعيد أو يضبط محاذاة الخط في فقرة بدون وراثة. قراءة/كتابة [FontAlignment](../../com.aspose.slides/fontalignment).

**الإرجاع:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

يعيد أو يضبط محاذاة الخط في فقرة بدون وراثة. قراءة/كتابة [FontAlignment](../../com.aspose.slides/fontalignment).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

يعيد تنسيق الجزء الافتراضي للفقرة. لا يتم تطبيق الوراثة. للقراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

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