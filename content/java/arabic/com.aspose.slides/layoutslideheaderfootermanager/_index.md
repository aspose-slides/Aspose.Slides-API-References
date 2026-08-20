---
title: LayoutSlideHeaderFooterManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مديرًا يتحكم في سلوك عناصر التذييل، والوقت-التاريخ، ورقم الصفحة في شريحة التخطيط وجميع العناصر النائبة للمتفرعات.
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

يمثل مديرًا يتحكم في سلوك تذييل شريحة التخطيط، وعناصر الوقت-التاريخ، ورقم الصفحة، بالإضافة إلى جميع العناصر النائبة للمتفرعات. العناصر النائبة للمتفرعات تعني أن العناصر النائبة موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes layout slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes layout slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes layout slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to layout slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to layout slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر نائب لتذييل شريحة التخطيط وجميع عناصر التذييل للمتفرعات. العناصر النائبة للمتفرعات تعني أن العناصر النائبة موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر التذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر نائب لرقم شريحة التخطيط وجميع عناصر رقم الصفحات للمتفرعات. العناصر النائبة للمتفرعات تعني أن العناصر النائبة موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر رقم الصفحة مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية عنصر نائب للوقت-التاريخ في شريحة التخطيط وجميع عناصر الوقت-التاريخ للمتفرعات. العناصر النائبة للمتفرعات تعني أن العناصر النائبة موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر الوقت-التاريخ مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

يضبط النص في عنصر نائب لتذييل شريحة التخطيط وجميع عناصر التذييل للمتفرعات. العناصر النائبة للمتفرعات تعني أن العناصر النائبة موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص في عنصر نائب للوقت-التاريخ في شريحة التخطيط وجميع عناصر الوقت-التاريخ للمتفرعات. العناصر النائبة للمتفرعات تعني أن العناصر النائبة موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |