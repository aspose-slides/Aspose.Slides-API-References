---
title: ILayoutSlideHeaderFooterManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مديرًا يحتفظ بسلوك حجزات الفوتر وتاريخ-الوقت ورقم الصفحة في شريحة التخطيط وجميع الحجزات التابعة.
type: docs
url: /ar/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**كل الواجهات التي تم تنفيذها:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك الفوتر في شريحة التخطيط، وحجزات التاريخ-الوقت، ورقم الصفحة، وجميع الحجزات التابعة. الحجزات التابعة تعني أن الحجزات موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر رؤية حجز الفوتر في شريحة التخطيط وجميع الحجزات التابعة للفوتر. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر رؤية حجز رقم الصفحة في شريحة التخطيط وجميع الحجزات التابعة لرقم الصفحة. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر رؤية حجز التاريخ-الوقت في شريحة التخطيط وجميع الحجزات التابعة للتاريخ-الوقت. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضبط النص لحجز الفوتر في شريحة التخطيط وجميع الحجزات التابعة للفوتر. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضبط النص لحجز التاريخ-الوقت في شريحة التخطيط وجميع الحجزات التابعة للتاريخ-الوقت. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر رؤية حجز الفوتر في شريحة التخطيط وجميع الحجزات التابعة للفوتر. الحجزات التابعة تعني أن الحجزات موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة الرئيسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل حجز الفوتر مرئيًا، وإلا - يخفيه. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر رؤية حجز رقم الصفحة في شريحة التخطيط وجميع الحجزات التابعة لرقم الصفحة. الحجزات التابعة تعني أن الحجزات موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل حجز رقم الصفحة مرئيًا، وإلا - يخفيه. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر رؤية حجز التاريخ-الوقت في شريحة التخطيط وجميع الحجزات التابعة للتاريخ-الوقت. الحجزات التابعة تعني أن الحجزات موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل حجز التاريخ-الوقت مرئيًا، وإلا - يخفيه. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

يضبط النص لحجز الفوتر في شريحة التخطيط وجميع الحجزات التابعة للفوتر. الحجزات التابعة تعني أن الحجزات موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص لحجز التاريخ-الوقت في شريحة التخطيط وجميع الحجزات التابعة للتاريخ-الوقت. الحجزات التابعة تعني أن الحجزات موجودة في الشرائح المعتمدة. الشرائح المعتمدة تستخدم وتعتمد على شريحة التخطيط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |