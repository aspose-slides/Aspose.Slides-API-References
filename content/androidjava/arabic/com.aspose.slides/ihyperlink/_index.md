---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل ارتباطًا تشعبيًا.
type: docs
url: /ar/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

يمثل ارتباطًا تشعبيًا.
## الطرق

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | يعيد نوع إجراء HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | يحدد عنوان URL الخارجي. إذا أصبحت هذه الخاصية غير فارغة فإن الخاصية TargetSlide تصبح فارغة. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء بغض النظر عن المحتوى الفعلي للجزء. |
| [getTargetSlide()](#getTargetSlide--) | إذا كان HyperlinkEx يستهدف شريحة محددة، يعيد هذه الشريحة. |
| [getTargetFrame()](#getTargetFrame--) | يعيد الإطار داخل مجموعة إطارات HTML الأب للهدف من الارتباط التشعبي الأب عندما يكون موجودًا. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | يعيد الإطار داخل مجموعة إطارات HTML الأب للهدف من الارتباط التشعبي الأب عندما يكون موجودًا. |
| [getTooltip()](#getTooltip--) | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأب. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأب. |
| [getHistory()](#getHistory--) | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأب إلى قائمة الارتباطات التي تم عرضها عند تنفيذه. |
| [setHistory(boolean value)](#setHistory-boolean-) | يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأب إلى قائمة الارتباطات التي تم عرضها عند تنفيذه. |
| [getHighlightClick()](#getHighlightClick--) | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. |
| [getSound()](#getSound--) | يمثل الصوت المشغل للارتباط التشعبي. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | يمثل الصوت المشغل للارتباط التشعبي. |
| [getColorSource()](#getColorSource--) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. |
| [setColorSource(int value)](#setColorSource-int-) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | يحدد ما إذا كان كائنان Hyperlink متساويين. |

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

PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be changed to match the text portion. This property represents the original value of the hyperlink.

**الإرجاع:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

إذا كان HyperlinkEx يستهدف شريحة محددة، يعيد هذه الشريحة. إذا أصبحت الخاصية غير فارغة فإن الخاصية ExternalUrl تصبح فارغة. للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

يعيد الإطار داخل مجموعة إطارات HTML الأب للهدف من الارتباط التشعبي الأب عندما يكون موجودًا. للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

يعيد الإطار داخل مجموعة إطارات HTML الأب للهدف من الارتباط التشعبي الأب عندما يكون موجودًا. للقراءة والكتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأب. للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

يعيد السلسلة التي قد تُظهر في واجهة المستخدم كمرتبطة بالارتباط التشعبي الأب. للقراءة والكتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأب إلى قائمة الارتباطات التي تم عرضها عند تنفيذه. للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

يحدد ما إذا كان يجب إضافة هدف الارتباط التشعبي الأب إلى قائمة الارتباطات التي تم عرضها عند تنفيذه. للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر. للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي. للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

يمثل الصوت المشغل للارتباط التشعبي. للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // الحصول على أول ارتباط تشعبي للشكل
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

يمثل الصوت المشغل للارتباط التشعبي. للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // الحصول على أول ارتباط تشعبي للشكل
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

يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. للقراءة والكتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**الإرجاع:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء. للقراءة والكتابة [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

يحدد ما إذا كان كائنان Hyperlink متساويين.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | الارتباط التشعبي للمقارنة مع الارتباط التشعبي الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الارتباط التشعبي المحدد يساوي الارتباط التشعبي الحالي؛ وإلا **false**.