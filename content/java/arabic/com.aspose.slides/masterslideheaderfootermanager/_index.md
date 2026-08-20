---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides لمرجع API جافا
description: يمثل مديرًا يحتفظ بسلوك تذييل الشريحة الرئيسي وعلامات العنصر النائب للوقت والتاريخ ورقم الصفحة وجميع علامات العنصر النائب الفرعية.
type: docs
url: /ar/com.aspose.slides/masterslideheaderfootermanager/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

يمثل المُدير الذي يحتفظ بسلوك تذييل الشريحة الرئيسي، وعلامات العنصر النائب للوقت والتاريخ، ورقم الصفحة، وجميع علامات العنصر النائب الفرعية. تعني علامات العنصر النابع الفرعية أن العلامات موجودة على شرائح التخطيط المعتمدة وعلى الشرائح المعتمدة. تستخدم شرائح التخطيط المعتمدة والشرائح وتعتمد على الشريحة الرئيسى.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يُغيّر رؤية علامة العنصر النائب لتذييل الشريحة الرئيسى وجميع علامات العنصر النائب للتذييل الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يُغيّر رؤية علامة العنصر النائب لرقم صفحة الشريحة الرئيسى وجميع علامات العنصر النائب لأرقام الصفحات الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يُغيّر رؤية علامة العنصر النائب للوقت والتاريخ في الشريحة الرئيسى وجميع علامات العنصر النائب للوقت والتاريخ الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يعيّن النص إلى علامة العنصر النائب لتذييل الشريحة الرئيسى وجميع علامات العنصر النائب للتذييل الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يعيّن النص إلى علامة العنصر النائب للوقت والتاريخ في الشريحة الرئيسى وجميع علامات العنصر النائب للوقت والتاريخ الفرعية. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

يُغيّر رؤية علامة العنصر النائب لتذييل الشريحة الرئيسى وجميع علامات العنصر النائب للتذييل الفرعية. تعني علامات العنصر النائب الفرعية أن العلامات موجودة على شرائح التخطيط المعتمدة وعلى الشرائح المعتمدة. تستخدم شرائح التخطيط المعتمدة والشرائح وتعتمد على الشريحة الرئيسى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل علامات التذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يُغيّر رؤية علامة العنصر النائب لرقم صفحة الشريحة الرئيسى وجميع علامات العنصر النائب لأرقام الصفحات الفرعية. تعني علامات العنصر النائب الفرعية أن العلامات موجودة على شرائح التخطيط المعتمدة وعلى الشرائح المعتمدة. تستخدم شرائح التخطيط المعتمدة والشرائح وتعتمد على الشريحة الرئيسى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل علامات رقم الصفحة مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يُغيّر رؤية علامة العنصر النائب للوقت والتاريخ في الشريحة الرئيسى وجميع علامات العنصر النائب للوقت والتاريخ الفرعية. تعني علامات العنصر النائب الفرعية أن العلامات موجودة على شرائح التخطيط المعتمدة وعلى الشرائح المعتمدة. تستخدم شرائح التخطيط المعتمدة والشرائح وتعتمد على الشريحة الرئيسى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل علامات الوقت والتاريخ مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

يعيّن النص إلى علامة العنصر النائب لتذييل الشريحة الرئيسى وجميع علامات العنصر النائب للتذييل الفرعية. تعني علامات العنصر النائب الفرعية أن العلامات موجودة على شرائح التخطيط المعتمدة وعلى الشرائح المعتمدة. تستخدم شرائح التخطيط المعتمدة والشرائح وتعتمد على الشريحة الرئيسى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

يعيّن النص إلى علامة العنصر النائب للوقت والتاريخ في الشريحة الرئيسى وجميع علامات العنصر النائب للوقت والتاريخ الفرعية. تعني علامات العنصر النائب الفرعية أن العلامات موجودة على شرائح التخطيط المعتمدة وعلى الشرائح المعتمدة. تستخدم شرائح التخطيط المعتمدة والشرائح وتعتمد على الشريحة الرئيسى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |