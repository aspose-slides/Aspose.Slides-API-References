---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /ar/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

يمثل ارتباطًا تشعبيًا.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getActionType()](#getActionType--) | يعيد نوع إجراء HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | يحدد عنوان URL الخارجي. إذا أصبحت هذه الخاصية غير فارغة فإن الخاصية TargetSlide تصبح فارغة. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء بغض النظر عن المحتوى الفعلي للجزء. |
| [getTargetSlide()](#getTargetSlide--) | إذا كان HyperlinkEx يستهدف شريحة معينة فإنه يعيد هذه الشريحة. |
| [getTargetFrame()](#getTargetFrame--) | يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. |
| [getTooltip()](#getTooltip--) | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. |
| [getHistory()](#getHistory--) | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات المشاهدة عند استدعائه. |
| [setHistory(boolean value)](#setHistory-boolean-) | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات المشاهدة عند استدعائه. |
| [getHighlightClick()](#getHighlightClick--) | يحدد ما إذا كان يجب تسليط الضوء على الارتباط التشعبي عند النقر. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | يحدد ما إذا كان يجب تسليط الضوء على الارتباط التشعبي عند النقر. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [getSound()](#getSound--) | يمثل الصوت المشغل للارتباط التشعبي. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | يمثل الصوت المشغل للارتباط التشعبي. |
| [getColorSource()](#getColorSource--) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. |
| [setColorSource(int value)](#setColorSource-int-) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | يحدد ما إذا كانت مثيلات Hyperlink الاثنين متساوية. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

يعيد نوع إجراء HyperLinkEx. للقراءة فقط [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**الإرجاع:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

يحدد عنوان URL الخارجي. إذا أصبحت هذه الخاصية غير فارغة فإن الخاصية TargetSlide تصبح فارغة. للقراءة فقط String.

**الإرجاع:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء بغض النظر عن المحتوى الفعلي للجزء.

--------------------

PowerPoint يتعامل بشكل خاص مع الارتباطات النصية داخل الجزء. يسمح بإنشاء نص للارتباط التشعبي على شكل عنوان URL صالح، مختلف عن العنوان الحقيقي للارتباط. في هذه الحالة، عند عرض الارتباط في نافذة التحرير، سيتغير ليتطابق مع نص الجزء. تمثل هذه الخاصية القيمة الأصلية للارتباط التشعبي.

**الإرجاع:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

إذا كان HyperlinkEx يستهدف شريحة معينة فإنه يعيد هذه الشريحة. إذا أصبحت هذه الخاصية غير فارغة فإن الخاصية ExternalUrl تصبح فارغة. للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

يعيد الإطار داخل مجموعة إطارات HTML الأصلية للهدف عندما يكون موجودًا. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأصلي. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات المشاهدة عند استدعائه. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأصلي إلى قائمة الارتباطات المشاهدة عند استدعائه. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

يحدد ما إذا كان يجب تسليط الضوء على الارتباط التشعبي عند النقر. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

يحدد ما إذا كان يجب تسليط الضوء على الارتباط التشعبي عند النقر. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

يمثل الصوت المشغل للارتباط التشعبي. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // احصل على أول ارتباط تشعبي للشكل
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

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

يمثل الصوت المشغل للارتباط التشعبي. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // احصل على أول ارتباط تشعبي للشكل
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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**الإرجاع:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. قراءة/كتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

يحدد ما إذا كانت مثيلات Hyperlink الاثنين متساوية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | الارتباط التشعبي للمقارنة مع الارتباط التشعبي الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الارتباط التشعبي المحدد مساويًا للارتباط التشعبي الحالي؛ وإلا **false**.