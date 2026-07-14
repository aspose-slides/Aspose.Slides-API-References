---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثّل المدير الذي يحمل سلوك تذييل شريحة التخطيط وعناصر النائب للوقت والتاريخ ورقم الصفحة وجميع العناصر الفرعية.
type: docs
url: /ar/com.aspose.slides/layoutslideheaderfootermanager/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)  
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

يمثل المدير الذي يحمل سلوك تذييل شريحة التخطيط وعناصر النائب للوقت والتاريخ ورقم الصفحة وجميع العناصر الفرعية. تعني العناصر الفرعية أن العناصر النائبة موجودة على الشرائح المعتمدة. تستخدم الشرائح المعتمدة وتعتمد على شريحة التخطيط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر رؤية تذييل شريحة التخطيط وجميع تذييلات العناصر الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر رؤية رقم صفحة شريحة التخطيط وجميع أرقام الصفحات للعناصر الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر رؤية عنصر النائب للوقت والتاريخ في شريحة التخطيط وجميع عناصر الوقت والتاريخ للعناصر الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يحدد النص لتذييل شريحة التخطيط وجميع تذييلات العناصر الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يحدد النص لعنصر النائب للوقت والتاريخ في شريحة التخطيط وجميع عناصر الوقت والتاريخ للعناصر الفرعية. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية تذييل شريحة التخطيط وجميع تذييلات العناصر الفرعية. تعني العناصر الفرعية أن العناصر النائبة موجودة على الشرائح المعتمدة. تستخدم الشرائح المعتمدة وتعتمد على شريحة الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل تذييلات العناصر مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية رقم صفحة شريحة التخطيط وجميع أرقام الصفحات للعناصر الفرعية. تعني العناصر الفرعية أن العناصر النائبة موجودة على الشرائح المعتمدة. تستخدم الشرائح المعتمدة وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل أرقام الصفحات مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب للوقت والتاريخ في شريحة التخطيط وجميع عناصر الوقت والتاريخ للعناصر الفرعية. تعني العناصر الفرعية أن العناصر النائبة موجودة على الشرائح المعتمدة. تستخدم الشرائح المعتمدة وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر الوقت والتاريخ مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

يحدد النص لتذييل شريحة التخطيط وجميع تذييلات العناصر الفرعية. تعني العناصر الفرعية أن العناصر النائبة موجودة على الشرائح المعتمدة. تستخدم الشرائح المعتمدة وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

يحدد النص لعنصر النائب للوقت والتاريخ في شريحة التخطيط وجميع عناصر الوقت والتاريخ للعناصر الفرعية. تعني العناصر الفرعية أن العناصر النائبة موجودة على الشرائح المعتمدة. تستخدم الشرائح المعتمدة وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |