---
title: Hyperlink
second_title: مرجع API Aspose.Slides للجافا
description: يمثل ارتباطًا تشعبيًا.
type: docs
url: /ar/com.aspose.slides/hyperlink/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

يمثل ارتباطًا تشعبيًا.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | إنشاء كائن ارتباط تشعبي. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | إنشاء كائن ارتباط تشعبي يشير إلى شريحة محددة. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | إنشاء كائن ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، مع تجاوز الخصائص الثانوية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | يعيد ارتباطًا تشعبيًا خاصًا "لا تفعل شيئًا". |
| [getMedia()](#getMedia--) | يعيد ارتباطًا تشعبيًا خاصًا "تشغيل ملف وسائط". |
| [getNextSlide()](#getNextSlide--) | يعيد ارتباطًا تشعبيًا إلى الشريحة التالية. |
| [getPreviousSlide()](#getPreviousSlide--) | يعيد ارتباطًا تشعبيًا إلى الشريحة السابقة. |
| [getFirstSlide()](#getFirstSlide--) | يعيد ارتباطًا تشعبيًا إلى الشريحة الأولى للعرض. |
| [getLastSlide()](#getLastSlide--) | يعيد ارتباطًا تشعبيًا إلى الشريحة الأخيرة للعرض. |
| [getLastVievedSlide()](#getLastVievedSlide--) | يعيد ارتباطًا تشعبيًا إلى الشريحة التي تم عرضها آخرًا. |
| [getEndShow()](#getEndShow--) | يعيد ارتباطًا تشعبيًا ينهي العرض. |
| [getActionType()](#getActionType--) | يعيد نوع إجراء الارتباط التشعبي. |
| [getExternalUrl()](#getExternalUrl--) | يحدد عنوان URL الخارجي. |
| [getTargetSlide()](#getTargetSlide--) | إذا كان الارتباط التشعبي يستهدف شريحة محددة، يعيد هذه الشريحة. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء بغض النظر عن المحتوى الفعلي للجزء. |
| [getTargetFrame()](#getTargetFrame--) | يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف من الارتباط التشعبي الأصلي عندما يكون موجودًا. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف من الارتباط التشعبي الأصلي عندما يكون موجودًا. |
| [getTooltip()](#getTooltip--) | يعيد السلسلة التي قد تظهر في واجهة المستخدم المرتبطة بالارتباط التشعبي الأصلي. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | يعيد السلسلة التي قد تظهر في واجهة المستخدم المرتبطة بالارتباط التشعبي الأصلي. |
| [getHistory()](#getHistory--) | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الروابط المشاهدة عندما يتم استدعاؤه. |
| [setHistory(boolean value)](#setHistory-boolean-) | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الروابط المشاهدة عندما يتم استدعاؤه. |
| [getHighlightClick()](#getHighlightClick--) | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [getSound()](#getSound--) | يمثل الصوت المشغل للارتباط التشعبي. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | يمثل الصوت المشغل للارتباط التشعبي. |
| [getColorSource()](#getColorSource--) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. |
| [setColorSource(int value)](#setColorSource-int-) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت كائني الارتباط التشعبي متساويين. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | يحدد ما إذا كانت كائني الارتباط التشعبي متساويين. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | يفحص ارتباطين تشابيين للتساوي. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | يفحص ارتباطين تشابيين لعدم التساوي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

إنشاء كائن ارتباط تشعبي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

إنشاء كائن ارتباط تشعبي يشير إلى شريحة محددة. ملاحظة: يجب إسناد الارتباط التشعبي المُنشأ إلى كائن من نفس العرض، وإلا سيُحفظ الرابط كـ NoAction.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة المستهدفة. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

إنشاء كائن ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، مع تجاوز الخصائص الثانوية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | الارتباط التشعبي المصدر |
| targetFrame | java.lang.String | الإطار الهدف |
| tooltip | java.lang.String | نص تلميح الأدوة |
| history | boolean | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الروابط المشاهدة عندما يتم استدعاؤه. |
| stopSoundsOnClick | boolean | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| highlightClick | boolean | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

يعيد ارتباطًا تشعبيًا خاصًا "لا تفعل شيئًا". قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

يعيد ارتباطًا تشعبيًا خاصًا "تشغيل ملف وسائط". يُستخدم في AudioFrame و VideoFrame. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

يعيد ارتباطًا تشعبيًا إلى الشريحة التالية. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

يعيد ارتباطًا تشعبيًا إلى الشريحة السابقة. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

يعيد ارتباطًا تشعبيًا إلى الشريحة الأولى للعرض. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

يعيد ارتباطًا تشعبيًا إلى الشريحة الأخيرة للعرض. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

يعيد ارتباطًا تشعبيًا إلى الشريحة التي تم عرضها آخرًا. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

يعيد ارتباطًا تشعبيًا ينهي العرض. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**الإرجاع:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

يعيد نوع إجراء الارتباط التشعبي. قراءة فقط [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**الإرجاع:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

يحدد عنوان URL الخارجي. قراءة فقط String.

**الإرجاع:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

إذا كان الارتباط التشعبي يستهدف شريحة معينة، يعيد هذه الشريحة. قراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء دون النظر إلى المحتوى الفعلي للجزء.

--------------------

يتعامل PowerPoint بطريقة خاصة مع الروابط والنص المقابل لها في الجزء. يسمح بإنشاء نص للارتباط التشعبي على شكل URL صالح، مختلف عن العنوان الفعلي للربط. في هذه الحالة، عند مشاهدة الرابط في نافذة التحرير، سيتغير ليتطابق مع جزء النص. تمثل هذه الخاصية القيمة الأصلية للارتباط التشعبي.

**الإرجاع:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف من الارتباط التشعبي الأصلي عندما يكون موجودًا. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف من الارتباط التشعبي الأصلي عندما يكون موجودًا. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

يعيد السلسلة التي قد تظهر في واجهة المستخدم المرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

يعيد السلسلة التي قد تظهر في واجهة المستخدم المرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الروابط المشاهدة عندما يتم استدعاؤه. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الروابط المشاهدة عندما يتم استدعاؤه. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

يمثل الصوت المشغل للارتباط التشعبي. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // الحصول على ارتباط الشكل الأول
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صوت الارتباط التشعبي في مصفوفة البايت
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

يمثل الصوت المشغل للارتباط التشعبي. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // الحصول على ارتباط الشكل الأول
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صوت الارتباط التشعبي في مصفوفة البايت
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**الإرجاع:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كانت كائني الارتباط التشعبي متساويين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الارتباط التشعبي للمقارنة مع الارتباط التشعبي الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الارتباط التشعبي المحدد متساويًا مع الارتباط التشعبي الحالي؛ **false** خلاف ذلك.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

يحدد ما إذا كانت كائني الارتباط التشعبي متساويين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | الارتباط التشعبي للمقارنة مع الارتباط التشعبي الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الارتباط التشعبي المحدد متساويًا مع الارتباط التشعبي الحالي؛ **false** خلاف ذلك.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

يفحص ارتباطين تشابيين للتساوي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | الارتباط التشعبي الأول للاختبار. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | الارتباط التشعبي الثاني للاختبار. |

**الإرجاع:**
boolean - **true** إذا كانت الروابط التشعبية متساوية.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

يفحص ارتباطين تشابيين لعدم التساوي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | الارتباط التشعبي الأول للاختبار. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | الارتباط التشعبي الثاني للاختبار. |

**الإرجاع:**
boolean - **false** إذا كانت الروابط التشعبية متساوية.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

**الإرجاع:**
int - قيمة تجزئة لعنوان URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject