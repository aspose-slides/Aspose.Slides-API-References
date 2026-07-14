---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل المدير الذي يتحكم في سلوك عناصر النائب لتذييل الشريحة الرئيسية، والوقت والتاريخ، ورقم الصفحة، وجميع العناصر النائبة الفرعية.
type: docs
url: /ar/com.aspose.slides/imasterslideheaderfootermanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

يمثل المدير الذي يحتفظ بسلوك تذييل الشريحة الرئيسية، وعناصر العنصر النائب للوقت والتاريخ، وأرقام الصفحات، وجميع العناصر النائبة الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على تخطيط معين والشرائح المعتمدة. تستخدم الشرائح المعتمدة على التخطيط وتتعتمد على الشريحة الرئيسية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغير رؤية عنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل الشرائح الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغير رؤية عنصر النائب لرقم صفحة الشريحة الرئيسية وجميع عناصر النائب لأرقام صفحات الشرائح الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغير رؤية عنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ في الشرائح الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضع النص في عنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل الشرائح الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضع النص في عنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ في الشرائح الفرعية. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغير رؤية عنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على تخطيط معين والشرائح المعتمدة. تستخدم الشرائح المعتمدة على التخطيط وتتعتمد على الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائب للتذييل مرئية، وإلا – يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغير رؤية عنصر النائب لرقم صفحة الشريحة الرئيسية وجميع عناصر النائب لأرقام صفحات الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على تخطيط معين والشرائح المعتمدة. تستخدم الشرائح المعتمدة على التخطيط وتتعتمد على الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائب لأرقام الصفحات مرئية، وإلا – يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغير رؤية عنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ في الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على تخطيط معين والشرائح المعتمدة. تستخدم الشرائح المعتمدة على التخطيط وتتعتمد على الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر النائب للوقت والتاريخ مرئية، وإلا – يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

يضع النص في عنصر النائب لتذييل الشريحة الرئيسية وجميع عناصر النائب لتذييل الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على تخطيط معين والشرائح المعتمدة. تستخدم الشرائح المعتمدة على التخطيط وتتعتمد على الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

يضع النص في عنصر النائب للوقت والتاريخ في الشريحة الرئيسية وجميع عناصر النائب للوقت والتاريخ في الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على تخطيط معين والشرائح المعتمدة. تستخدم الشرائح المعتمدة على التخطيط وتتعتمد على الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |