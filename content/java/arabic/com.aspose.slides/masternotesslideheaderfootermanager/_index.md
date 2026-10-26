---
title: MasterNotesSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل مديرًا يحتفظ بسلوك عناصر النائب لتذييل شريحة ملاحظات الماستر، وتاريخ/وقت، ورقم الصفحة، وجميع العناصر النائبة الفرعية.
type: docs
url: /ar/com.aspose.slides/masternotesslideheaderfootermanager/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)  
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

يمثل مديرًا يتحكم بسلوك العناصر النائبة لتذييل شريحة ملاحظات الماستر، وتاريخ/وقت، ورقم الصفحة، وجميع العناصر النائبة الفرعية. تعني العناصر النائبة الفرعية أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | يغيّر قابلية ظهور العنصر النائب لرأس شريحة ملاحظات الماستر وجميع العناصر النائبة لرؤوس الشرائح الفرعية. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | يضبط النص للعنصر النائب لرأس شريحة ملاحظات الماستر وجميع العناصر النائبة لرؤوس الشرائح الفرعية. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | يغيّر قابلية ظهور العنصر النائب لتذييل شريحة الماستر وجميع العناصر النائبة لتذييل الشرائح الفرعية. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | يغيّر قابلية ظهور العنصر النائب لرقم صفحة شريحة الماستر وجميع العناصر النائبة لأرقام صفحات الشرائح الفرعية. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | يغيّر قابلية ظهور العنصر النائب لتاريخ/وقت شريحة الماستر وجميع العناصر النائبة لتواريخ/أوقات الشرائح الفرعية. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | يضبط النص للعنصر النائب لتذييل شريحة الماستر وجميع العناصر النائبة لتذييل الشرائح الفرعية. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | يضبط النص للعنصر النائب لتاريخ/وقت شريحة الماستر وجميع العناصر النائبة لتواريخ/أوقات الشرائح الفرعية. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

يغيّر قابلية ظهور العنصر النائب لرأس شريحة ملاحظات الماستر وجميع العناصر النائبة لرؤوس الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر الرأس مرئية، وإلا - يخفيها. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

يضبط النص للعنصر النائب لرأس شريحة ملاحظات الماستر وجميع العناصر النائبة لرؤوس الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

يغيّر قابلية ظهور العنصر النائب لتذييل شريحة الماستر وجميع العناصر النائبة لتذييل الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر التذييل مرئية، وإلا - يخفيها. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

يغيّر قابلية ظهور العنصر النائب لرقم صفحة شريحة الماستر وجميع العناصر النائبة لأرقام صفحات الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عناصر رقم الصفحة مرئية، وإلا - يخفيها. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

يغيّر قابلية ظهور العنصر النائب لتاريخ/وقت شريحة الماستر وجميع العناصر النائبة لتواريخ/أوقات الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل العناصر النائبة لتاريخ/وقت مرئية، وإلا - يخفيها. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

يضبط النص للعنصر النائب لتذييل شريحة الماستر وجميع العناصر النائبة لتذييل الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

يضبط النص للعنصر النائب لتاريخ/وقت شريحة الماستر وجميع العناصر النائبة لتواريخ/أوقات الشرائح الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح الملاحظات التابعة. تستخدم الشرائح الملاحظات التابعة وتعتمد على شريحة ملاحظات الماستر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |