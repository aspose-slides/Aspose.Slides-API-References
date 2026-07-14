---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مديرًا يحتفظ بسلوك نائبي تذييل الشريحة الرئيسية، والتاريخ والوقت، ورقم الصفحة، وجميع النائبات الفرعية.
type: docs
url: /ar/com.aspose.slides/masterslideheaderfootermanager/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)  
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك تذييل الشريحة الرئيسية، وعناصر التاريخ والوقت، وعناصر رقم الصفحة، وجميع العناصر الفرعية. تعني العناصر الفرعية أن العناصر موجودة على شرائح التخطيط المعتمدة والشرائح المعتمدة. تستخدم شرائح التخطيط والشرائح المعتمدة وتستند إلى الشريحة الرئيسية.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر رؤية عنصر تذييل الشريحة الرئيسية وجميع عناصر تذييل العناصر الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر رؤية عنصر رقم صفحة الشريحة الرئيسية وجميع عناصر رقم الصفحة للعنصر الفرعي. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر رؤية عنصر التاريخ والوقت للشريحة الرئيسية وجميع عناصر التاريخ والوقت للعنصر الفرعي. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضبط النص لعنصر تذييل الشريحة الرئيسية وجميع عناصر تذييل العناصر الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضبط النص لعنصر التاريخ والوقت للشريحة الرئيسية وجميع عناصر التاريخ والوقت للعنصر الفرعي. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر تذييل الشريحة الرئيسية وجميع عناصر تذييل العناصر الفرعية. تعني العناصر الفرعية أن العناصر موجودة على شرائح التخطيط المعتمدة والشرائح المعتمدة. تستخدم شرائح التخطيط والشرائح المعتمدة وتستند إلى الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر التذييل مرئية، وإلا يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية عنصر رقم صفحة الشريحة الرئيسية وجميع عناصر رقم الصفحة للعنصر الفرعي. تعني العناصر الفرعية أن العناصر موجودة على شرائح التخطيط المعتمدة والشرائح المعتمدة. تستخدم شرائح التخطيط والشرائح المعتمدة وتستند إلى الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر رقم الصفحة مرئية، وإلا يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية عنصر التاريخ والوقت للشريحة الرئيسية وجميع عناصر التاريخ والوقت للعنصر الفرعي. تعني العناصر الفرعية أن العناصر موجودة على شرائح التخطيط المعتمدة والشرائح المعتمدة. تستخدم شرائح التخطيط والشرائح المعتمدة وتستند إلى الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر التاريخ والوقت مرئية، وإلا يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

يضبط النص لعنصر تذييل الشريحة الرئيسية وجميع عناصر تذييل العناصر الفرعية. تعني العناصر الفرعية أن العناصر موجودة على شرائح التخطيط المعتمدة والشرائح المعتمدة. تستخدم شرائح التخطيط والشرائح المعتمدة وتستند إلى الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص لعنصر التاريخ والوقت للشريحة الرئيسية وجميع عناصر التاريخ والوقت للعنصر الفرعي. تعني العناصر الفرعية أن العناصر موجودة على شرائح التخطيط المعتمدة والشرائح المعتمدة. تستخدم شرائح التخطيط والشرائح المعتمدة وتستند إلى الشريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |