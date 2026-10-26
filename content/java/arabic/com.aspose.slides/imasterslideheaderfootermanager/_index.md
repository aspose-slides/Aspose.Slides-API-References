---
title: IMasterSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مديرًا يحتوي على سلوك عناصر النائب لتذييل الشريحة الرئيسية والوقت/التاريخ ورقم الصفحة وجميع العناصر النائبة الفرعية.
type: docs
url: /ar/com.aspose.slides/imasterslideheaderfootermanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

يمثل مديرًا يحتوي على سلوك تذييل الشريحة الرئيسية، وعناصر النائب للوقت والتاريخ، وعناصر النائب لرقم الصفحة، وجميع العناصر الفرعية. العناصر الفرعية تعني أن العناصر النائبة موجودة على الشرائح ذات التخطيط المعتمد وعلى الشرائح المعتمدة. الشرائح ذات التخطيط المعتمد والشرائح تستخدم وتعتمد على الشريحة الرئيسية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر رؤية عنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل العناصر الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر رؤية عنصر النائب لرقم صفحة الشريحة الرئيسية وجميع عناصر النائب لأرقام الصفحات الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر رؤية عنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يحدد النص لعنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل العناصر الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يحدد النص لعنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ الفرعية. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل العناصر الفرعية. العناصر الفرعية تعني أن العناصر النائبة موجودة على الشرائح ذات التخطيط المعتمد وعلى الشرائح المعتمدة. الشرائح ذات التخطيط المعتمد والشرائح تستخدم وتعتمد على الشريحة الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائب للتذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب لرقم صفحة الشريحة الرئيسية وجميع عناصر النائب لأرقام الصفحات الفرعية. العناصر الفرعية تعني أن العناصر النائبة موجودة على الشرائح ذات التخطيط المعتمد وعلى الشرائح المعتمدة. الشرائح ذات التخطيط المعتمد والشرائح تستخدم وتعتمد على الشريحة الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائب لأرقام الصفحات مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ الفرعية. العناصر الفرعية تعني أن العناصر النائبة موجودة على الشرائح ذات التخطيط المعتمد وعلى الشرائح المعتمدة. الشرائح ذات التخطيط المعتمد والشرائح تستخدم وتعتمد على الشريحة الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائب للوقت والتاريخ مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

يحدد النص لعنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل العناصر الفرعية. العناصر الفرعية تعني أن العناصر النائبة موجودة على الشرائح ذات التخطيط المعتمد وعلى الشرائح المعتمدة. الشرائح ذات التخطيط المعتمد والشرائح تستخدم وتعتمد على الشريحة الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المطلوب تعيينه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

يحدد النص لعنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ الفرعية. العناصر الفرعية تعني أن العناصر النائبة موجودة على الشرائح ذات التخطيط المعتمد وعلى الشرائح المعتمدة. الشرائح ذات التخطيط المعتمد والشرائح تستخدم وتعتمد على الشريحة الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المطلوب تعيينه. |