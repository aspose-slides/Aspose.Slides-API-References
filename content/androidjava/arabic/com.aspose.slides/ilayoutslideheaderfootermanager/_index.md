---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مديرًا يحتفظ بسلوك تذييل شريحة التخطيط وعناصر النائب لتاريخ-الوقت ورقم الصفحة وجميع العناصر النائبة الفرعية.
type: docs
url: /ar/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك تذييل شريحة التخطيط، وتاريخ-الوقت، وعلامات ترقيم الصفحات، وجميع العناصر النائبة الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر رؤية العنصر النائب لتذييل شريحة التخطيط وجميع العناصر النائبة لتذييل الأطفال. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر رؤية العنصر النائب لرقم صفحة شريحة التخطيط وجميع العناصر النائبة لأرقام صفحات الأطفال. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر رؤية العنصر النائب لتاريخ-الوقت في شريحة التخطيط وجميع العناصر النائبة لتاريخ-الوقت للأطفال. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضبط النص في العنصر النائب لتذييل شريحة التخطيط وجميع العناصر النائبة لتذييل الأطفال. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضبط النص في العنصر النائب لتاريخ-الوقت في شريحة التخطيط وجميع العناصر النائبة لتاريخ-الوقت للأطفال. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية العنصر النائب لتذييل شريحة التخطيط وجميع العناصر النائبة لتذييل الأطفال. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل العناصر النائبة للتذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية العنصر النائب لرقم صفحة شريحة التخطيط وجميع العناصر النائبة لأرقام صفحات الأطفال. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائبة لأرقام الصفحات مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية العنصر النائب لتاريخ-الوقت في شريحة التخطيط وجميع العناصر النائبة لتاريخ-الوقت للأطفال. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائبة لتاريخ-الوقت مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

يضبط النص في العنصر النائب لتذييل شريحة التخطيط وجميع العناصر النائبة لتذييل الأطفال. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص في العنصر النائب لتاريخ-الوقت في شريحة التخطيط وجميع العناصر النائبة لتاريخ-الوقت للأطفال. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |