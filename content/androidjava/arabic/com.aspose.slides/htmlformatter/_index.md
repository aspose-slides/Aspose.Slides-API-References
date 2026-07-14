---
title: HtmlFormatter
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل قالب ملف HTML.
type: docs
url: /ar/com.aspose.slides/htmlformatter/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

يمثل قالب ملف HTML.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | ينشئ ويعيد مُنسق HTML لعرض مستند بسيط يتكون من تسلسلات من الشرائح واحدة تحت الأخرى. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | ينشئ ويعيد مُنسق HTML لعرض شرائح بسيط يُظهر الشرائح واحدة تلو الأخرى. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | ينشئ ويعيد مُنسق HTML لتوليد HTML مخصص يعتمد على ردود نداء. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

ينشئ ويعيد مُنسق HTML لعرض مستند بسيط يتكون من تسلسلات من الشرائح واحدة تحت الأخرى.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| css | java.lang.String | يحدد CSS لهذا الملف. |
| showSlideTitle | boolean | يضيف عنوان الشريحة إذا كان هناك عنوان فوق صورة الشريحة. |

**القيمة المرجعة:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - كائن [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

ينشئ ويعيد مُنسق HTML لعرض شرائح بسيط يُظهر الشرائح واحدة تلو الأخرى.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| css | java.lang.String | يحدد URL لملف CSS المستخدم. |
| showSlideTitle | boolean | يضيف عنوان الشريحة إذا كان هناك عنوان فوق صورة الشريحة. |

**القيمة المرجعة:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - كائن [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

ينشئ ويعيد مُنسق HTML لتوليد HTML مخصص يعتمد على ردود نداء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | واجهة رد الاتصال التي تتحكم في إنشاء ملف HTML. |

**القيمة المرجعة:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - كائن [HtmlFormatter](../../com.aspose.slides/htmlformatter).