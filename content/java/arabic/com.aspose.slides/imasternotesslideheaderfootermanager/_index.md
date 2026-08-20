---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل مديرًا يحتفظ بسلوك تذييل شريحة الملاحظات الرئيسية ووقت التاريخ ورقم الصفحة والعناصر النائبة للطفل وجميع العناصر النائبة للطفل.
type: docs
url: /ar/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

يمثّل مديرًا يحتفظ بسلوك تذييل شريحة الملاحظات الرئيسية، ووقت التاريخ، وعناصر رقم الصفحة، وجميع العناصر الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | يغيّر رؤية عنصر ترويسة شريحة الملاحظات الرئيسية وجميع عناصر الترويسة الفرعية. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | يضبط النص إلى عنصر ترويسة شريحة الملاحظات الرئيسية وجميع عناصر الترويسة الفرعية. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر رؤية عنصر تذييل شريحة الملاحظات الرئيسية وجميع عناصر التذييل الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر رؤية عنصر رقم صفحة شريحة الملاحظات الرئيسية وجميع عناصر رقم الصفحة الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر رؤية عنصر وقت وتاريخ شريحة الملاحظات الرئيسية وجميع عناصر الوقت والتاريخ الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضبط النص إلى عنصر تذييل شريحة الملاحظات الرئيسية وجميع عناصر التذييل الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضبط النص إلى عنصر وقت وتاريخ شريحة الملاحظات الرئيسية وجميع عناصر الوقت والتاريخ الفرعية. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر ترويسة شريحة الملاحظات الرئيسية وجميع عناصر الترويسة الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر الترويسة مرئية، وإلا - يخفيها. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

يضبط النص إلى عنصر ترويسة شريحة الملاحظات الرئيسية وجميع عناصر الترويسة الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر تذييل شريحة الملاحظات الرئيسية وجميع عناصر التذييل الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر التذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر رقم صفحة شريحة الملاحظات الرئيسية وجميع عناصر رقم الصفحة الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر رقم الصفحة مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية عنصر وقت وتاريخ شريحة الملاحظات الرئيسية وجميع عناصر الوقت والتاريخ الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر الوقت والتاريخ مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

يضبط النص إلى عنصر تذييل شريحة الملاحظات الرئيسية وجميع عناصر التذييل الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص إلى عنصر وقت وتاريخ شريحة الملاحظات الرئيسية وجميع عناصر الوقت والتاريخ الفرعية. تعني العناصر الفرعية أن العناصر موجودة على الشرائح التابعة للملاحظات. تستخدم الشرائح التابعة للملاحظات وتعتمد على شريحة الملاحظات الرئيسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |