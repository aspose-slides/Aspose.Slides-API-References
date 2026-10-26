---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مديرًا يحتفظ بسلوك عناصر تذييل شريحة الملاحظات الرئيسة وعناصر تاريخ-الوقت ورقم الصفحة وجميع العناصر الفرعية.
type: docs
url: /ar/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

يمثل مديرًا يحتفظ بسلوك تذييل شريحة الملاحظات الرئيسة، وتاريخ-الوقت، وعناصر رقم الصفحة، وجميع العناصر الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | يغير رؤية عنصر ناصية شريحة الملاحظات الرئيسة وجميع عناصر الناصية الفرعية. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | يضبط النص لعنصر ناصية شريحة الملاحظات الرئيسة وجميع عناصر الناصية الفرعية. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغير رؤية عنصر تذييل شريحة الملاحظات الرئيسة وجميع عناصر التذييل الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغير رؤية عنصر رقم الصفحة في شريحة الملاحظات الرئيسة وجميع عناصر رقم الصفحة الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغير رؤية عنصر تاريخ-الوقت في شريحة الملاحظات الرئيسة وجميع عناصر تاريخ-الوقت الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضبط النص لعنصر تذييل شريحة الملاحظات الرئيسة وجميع عناصر التذييل الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضبط النص لعنصر تاريخ-الوقت في شريحة الملاحظات الرئيسة وجميع عناصر تاريخ-الوقت الفرعية. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

يغير رؤية عنصر ناصية شريحة الملاحظات الرئيسة وجميع عناصر الناصية الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر الناصية مرئية، وإلا - يخفيها. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

يضبط النص لعنصر ناصية شريحة الملاحظات الرئيسة وجميع عناصر الناصية الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغير رؤية عنصر تذييل شريحة الملاحظات الرئيسة وجميع عناصر التذييل الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر التذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغير رؤية عنصر رقم الصفحة في شريحة الملاحظات الرئيسة وجميع عناصر رقم الصفحة الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر رقم الصفحة مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغير رؤية عنصر تاريخ-الوقت في شريحة الملاحظات الرئيسة وجميع عناصر تاريخ-الوقت الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر تاريخ-الوقت مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

يضبط النص لعنصر تذييل شريحة الملاحظات الرئيسة وجميع عناصر التذييل الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص لعنصر تاريخ-الوقت في شريحة الملاحظات الرئيسة وجميع عناصر تاريخ-الوقت الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح الملاحظة التابعة. تستخدم الشرائح الملاحظة التابعة وتعتمد على شريحة الملاحظات الرئيسة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |