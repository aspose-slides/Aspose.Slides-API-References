---
title: Hyperlink
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل ارتباطًا تشعبيًا.
type: docs
url: /ar/com.aspose.slides/hyperlink/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

يمثل ارتباطًا تشعبيًا.
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | ينشئ مثالًا جديدًا من ارتباط تشعبي. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | ينشئ مثالًا جديدًا من ارتباط تشعبي يشير إلى شريحة محددة. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | ينشئ مثالًا جديدًا من ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، متجاوزًا الخصائص الثانوية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | تُرجِع ارتباطًا تشعبيًا خاصًا "لا تفعل شيئًا". |
| [getMedia()](#getMedia--) | تُرجِع ارتباطًا تشعبيًا خاصًا "تشغيل ملف وسائط". |
| [getNextSlide()](#getNextSlide--) | تُرجِع ارتباطًا تشعبيًا إلى الشريحة التالية. |
| [getPreviousSlide()](#getPreviousSlide--) | تُرجِع ارتباطًا تشعبيًا إلى الشريحة السابقة. |
| [getFirstSlide()](#getFirstSlide--) | تُرجِع ارتباطًا تشعبيًا إلى الشريحة الأولى في العرض. |
| [getLastSlide()](#getLastSlide--) | تُرجِع ارتباطًا تشعبيًا إلى الشريحة الأخيرة في العرض. |
| [getLastVievedSlide()](#getLastVievedSlide--) | تُرجِع ارتباطًا تشعبيًا إلى الشريحة التي تم عرضها آخر مرة. |
| [getEndShow()](#getEndShow--) | تُرجِع ارتباطًا تشعبيًا ينهي العرض. |
| [getActionType()](#getActionType--) | تُرجِع نوع إجراء الارتباط التشعبي. |
| [getExternalUrl()](#getExternalUrl--) | تحدد عنوان URL الخارجي. |
| [getTargetSlide()](#getTargetSlide--) | إذا كان الارتباط التشعبي يستهدف شريحة محددة تُرجِع هذه الشريحة. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | يمثل ارتباطًا تشعبيًا يُحدد لهذا الجزء دون اعتبار لمحتوى الجزء الفعلي. |
| [getTargetFrame()](#getTargetFrame--) | تُرجِع الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | تُرجِع الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. |
| [getTooltip()](#getTooltip--) | تُرجِع السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | تُرجِع السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. |
| [getHistory()](#getHistory--) | تحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات التي تم مشاهدتها عند تنفيذه. |
| [setHistory(boolean value)](#setHistory-boolean-) | تحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات التي تم مشاهدتها عند تنفيذه. |
| [getHighlightClick()](#getHighlightClick--) | تحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | تحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | تحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | تحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [getSound()](#getSound--) | يمثل الصوت المشغل للارتباط التشعبي. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | يمثل الصوت المشغل للارتباط التشعبي. |
| [getColorSource()](#getColorSource--) | يمثل مصدر لون الارتباط التشعبي – إما الأنماط أو تنسيق الجزء. |
| [setColorSource(int value)](#setColorSource-int-) | يمثل مصدر لون الارتباط التشعبي – إما الأنماط أو تنسيق الجزء. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحدد ما إذا كان مثالاَين من Hyperlink متساويين. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | تحدد ما إذا كان مثالاَين من Hyperlink متساويين. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | يختبر مساواة ارتباطين تشعبيين. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | يختبر عدم مساواة ارتباطين تشعبيين. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البيانية مثل جدول التجزئة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

ينشئ مثالًا جديدًا من ارتباط تشعبي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

ينشئ مثالًا جديدًا من ارتباط تشعبي يشير إلى شريحة محددة. ملاحظة: يجب ربط الارتباط التشعبي المُنشأ بكائن من نفس العرض؛ وإلا سيُحفظ كـ NoAction.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة الهدف. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

ينشئ مثالًا جديدًا من ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، متجاوزًا الخصائص الثانوية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | الارتباط التشعبي المصدر |
| targetFrame | java.lang.String | إطار الهدف |
| tooltip | java.lang.String | نص التلميح |
| history | boolean | تحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات التي تم مشاهدتها عند تنفيذه. |
| stopSoundsOnClick | boolean | تحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| highlightClick | boolean | تحدد ما إذا يجب تمييز الارتباط التشعبي عند النقر. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط من نوع long.

**القيمة المرجعة:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

تُرجِع ارتباطًا تشعبيًا خاصًا "لا تفعل شيئًا". قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

تُرجِع ارتباطًا تشعبيًا خاصًا "تشغيل ملف وسائط". يُستخدم في AudioFrame و VideoFrame. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

تُرجِع ارتباطًا تشعبيًا إلى الشريحة التالية. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

تُرجِع ارتباطًا تشعبيًا إلى الشريحة السابقة. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

تُرجِع ارتباطًا تشعبيًا إلى الشريحة الأولى في العرض. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

تُرجِع ارتباطًا تشعبيًا إلى الشريحة الأخيرة في العرض. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

تُرجِع ارتباطًا تشعبيًا إلى الشريحة التي تم عرضها آخر مرة. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

تُرجِع ارتباطًا تشعبيًا ينهي العرض. قراءة فقط [Hyperlink](../../com.aspose.slides/hyperlink).

**القيمة المرجعة:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

تُرجِع نوع إجراء الارتباط التشعبي. قراءة فقط [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**القيمة المرجعة:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

تحدد عنوان URL الخارجي. قراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

إذا كان الارتباط التشعبي يستهدف شريحة محددة تُرجِع هذه الشريحة. قراءة فقط [ISlide](../../com.aspose.slides/islide).

**القيمة المرجعة:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

يمثل ارتباطًا تشعبيًا يُحدد لهذا الجزء دون اعتبار لمحتوى الجزء الفعلي.

--------------------

يتميز PowerPoint بسلوك خاص للروابط والنص المقابل لها في جزء. يسمح بإنشاء نص للارتباط التشعبي على شكل عنوان URL صالح، مختلف عن العنوان الفعلي للربط. في هذه الحالة، عند عرض الرابط في نافذة التحرير، سيتغير ليتطابق مع نص الجزء. تمثل هذه الخاصية القيمة الأصلية للارتباط التشعبي.

**القيمة المرجعة:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

تُرجِع الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

تُرجِع الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

تُرجِع السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

تُرجِع السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

تحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات التي تم مشاهدتها عند تنفيذه. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

تحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات التي تم مشاهدتها عند تنفيذه. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

تحدد ما إذا يجب تمييز الارتباط التشعبي عند النقر. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

تحدد ما إذا يجب تمييز الارتباط التشعبي عند النقر. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

تحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

تحدد ما إذا يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة boolean.

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
>      // احصل على الارتباط التشعبي للشكل الأول
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

**القيمة المرجعة:**
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
>      // احصل على الارتباط التشعبي للشكل الأول
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صوت الارتباط التشعبي في مصفوفة بايت
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

يمثل مصدر لون الارتباط التشعبي – إما الأنماط أو تنسيق الجزء. قراءة/كتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**القيمة المرجعة:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

يمثل مصدر لون الارتباط التشعبي – إما الأنماط أو تنسيق الجزء. قراءة/كتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تحدد ما إذا كان مثالاَين من Hyperlink متساويين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الارتباط التشعبي للمقارنة مع الارتباط التشعبي الحالي. |

**القيمة المرجعة:**
boolean - **true** إذا كان الارتباط التشعبي المحدد مساويًا للارتباط التشعبي الحالي؛ وإلا **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
``` 
public final boolean equals(IHyperlink hlink)
```

تحدد ما إذا كان مثالاَين من Hyperlink متساويين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | الارتباط التشعبي للمقارنة مع الارتباط التشعبي الحالي. |

**القيمة المرجعة:**
boolean - **true** إذا كان الارتباط التشعبي المحدد مساويًا للارتباط التشعبي الحالي؛ وإلا **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

يختبر مساواة ارتباطين تشعبيين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | أول ارتباط تشعبي يُختبر. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | ثاني ارتباط تشعبي يُختبر. |

**القيمة المرجعة:**
boolean - **true** إذا كان الارتباطان متساويين.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

يختبر عدم مساواة ارتباطين تشعبيين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | أول ارتباط تشعبي يُختبر. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | ثاني ارتباط تشعبي يُختبر. |

**القيمة المرجعة:**
boolean - **false** إذا كان الارتباطان متساويين.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البيانية مثل جدول التجزئة.

**القيمة المرجعة:**
int - رمز التجزئة لعنوان URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يُرجِع كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject