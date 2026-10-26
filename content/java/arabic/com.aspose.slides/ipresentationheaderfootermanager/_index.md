---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides لمرجع API لجافا
description: يمثّل مديرًا يحتفظ بسلوك جميع عناصر نُسخ التذييل، التاريخ-الوقت ورقم الصفحة في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/ipresentationheaderfootermanager/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

يمثّل مديرًا يحتفظ بسلوك جميع عناصر نُسخ التذييل، التاريخ-الوقت ورقم الصفحة في العرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | يغيّر إظهار جميع عناصر نُسخ الرأس، بما في ذلك القالب الرئيسي للملاحظات، شرائح الملاحظات والقالب الرئيسي للملخص. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | يغيّر إظهار جميع عناصر نُسخ التذييل، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | يغيّر إظهار جميع عناصر نُسخ أرقام الصفحات، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | يغيّر إظهار جميع عناصر نُسخ التاريخ-الوقت، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | يحدد النص لجميع عناصر نُسخ الرأس، بما في ذلك القالب الرئيسي للملاحظات، شرائح الملاحظات والقالب الرئيسي للملخص. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | يحدد النص لجميع عناصر نُسخ التذييل، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | يحدد النص لجميع عناصر نُسخ التاريخ-الوقت، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | يغيّر إظهار عناصر نُسخ التذييل، التاريخ-الوقت وأرقام الصفحات لجميع شرائح العنوان ولشريحة التخطيط الأولى. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

يغيّر إظهار جميع عناصر نُسخ الرأس، بما في ذلك القالب الرئيسي للملاحظات، شرائح الملاحظات والقالب الرئيسي للملخص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نُسخ الرأس مرئية، وإلا - يخفيها. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

يغيّر إظهار جميع عناصر نُسخ التذييل، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نُسخ التذييل مرئية، وإلا - يخفيها. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

يغيّر إظهار جميع عناصر نُسخ أرقام الصفحات، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نُسخ أرقام الصفحات مرئية، وإلا - يخفيها. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

يغيّر إظهار جميع عناصر نُسخ التاريخ-الوقت، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نُسخ التاريخ-الوقت مرئية، وإلا - يخفيها. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

يحدد النص لجميع عناصر نُسخ الرأس، بما في ذلك القالب الرئيسي للملاحظات، شرائح الملاحظات والقالب الرئيسي للملخص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

يحدد النص لجميع عناصر نُسخ التذييل، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

يحدد النص لجميع عناصر نُسخ التاريخ-الوقت، بما في ذلك الشرائح الرئيسية، شرائح التخطيط والشرائح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

يغيّر إظهار عناصر نُسخ التذييل، التاريخ-الوقت وأرقام الصفحات لجميع شرائح العنوان ولشريحة التخطيط الأولى. شرائح العنوان \u2013 شرائح مستندة إلى شريحة التخطيط الأولى (بغض النظر عن نوع هذه الشريحة الأولى).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل العناصر مرئية، وإلا - يخفيها. |