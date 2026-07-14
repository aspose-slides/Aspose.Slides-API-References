---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة جافا
description: يمثل مديرًا يحتفظ بسلوك جميع عناصر نائب التذييل، التاريخ-الوقت، ورقم الصفحة في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/ipresentationheaderfootermanager/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

يمثل المدير الذي يحتفظ بسلوك جميع العناصر النائبة للتذييل، التاريخ-الوقت، ورقم الصفحة في العرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | يغيّر رؤية جميع عناصر نائب الرأس، بما في ذلك ملاحظات القالب، شرائح الملاحظات، وقالب النشرة. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | يغيّر رؤية جميع عناصر نائب التذييل، بما في ذلك الشرائح القالبية، شرائح التخطيط، والشرائح. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | يغيّر رؤية جميع عناصر نائب رقم الصفحة، بما في ذلك الشرائح القالبية، شرائح التخطيط، والشرائح. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | يغيّر رؤية جميع عناصر نائب التاريخ-الوقت، بما في ذلك الشرائح القالبية، شرائح التخطيط، والشرائح. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | يضبط النص لجميع عناصر نائب الرأس، بما في ذلك ملاحظات القالب، شرائح الملاحظات، وقالب النشرة. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | يضبط النص لجميع عناصر نائب التذييل، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | يضبط النص لجميع عناصر نائب التاريخ-الوقت، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | يغيّر رؤية عناصر نائب التذييل، التاريخ-الوقت، ورقم الصفحة لجميع شرائح العنوان وللشريحة التخطيطية الأولى. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```


يغيّر رؤية جميع عناصر نائب الرأس، بما في ذلك ملاحظات القالب، شرائح الملاحظات، وقالب النشرة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نائب الرأس مرئية، وإلا - يخفيها. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```


يغيّر رؤية جميع عناصر نائب التذييل، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نائب التذييل مرئية، وإلا - يخفيها. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```


يغيّر رؤية جميع عناصر نائب رقم الصفحة، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نائب رقم الصفحة مرئية، وإلا - يخفيها. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```


يغيّر رؤية جميع عناصر نائب التاريخ-الوقت، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر نائب التاريخ-الوقت مرئية، وإلا - يخفيها. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```


يضبط النص لجميع عناصر نائب الرأس، بما في ذلك ملاحظات القالب، شرائح الملاحظات، وقالب النشرة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```


يضبط النص لجميع عناصر نائب التذييل، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```


يضبط النص لجميع عناصر نائب التاريخ-الوقت، بما تشمل الشرائح القالبية، شرائح التخطيط، والشرائح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```


يغيّر رؤية عناصر نائب التذييل، التاريخ-الوقت، ورقم الصفحة لجميع شرائح العنوان وللشريحة التخطيطية الأولى. شرائح العنوان – شرائح مستندة إلى الشريحة التخطيطية الأولى (بغض النظر عن نوع هذه الشريحة التخطيطية الأولى).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل العناصر النائبة مرئية، وإلا - يخفيها. |