---
title: HtmlFormatter
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل قالب ملف HTML.
type: docs
url: /ar/com.aspose.slides/htmlformatter/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

يمثل قالب ملف HTML.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | ينشئ ويُعيد مُنسق HTML لعرض مستند بسيط يتكون من تسلسلات من الشرائح واحدة تحت الأخرى. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | ينشئ ويُعيد مُنسق HTML لعرض شرائح بسيط يُظهر الشرائح واحدة تلو الأخرى. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | ينشئ ويُعيد مُنسق HTML لتوليد HTML مخصص يعتمد على رد نداء. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


ينشئ ويُعيد مُنسق HTML لعرض مستند بسيط يتكون من تسلسلات من الشرائح واحدة تحت الأخرى.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| css | java.lang.String | يحدد CSS لهذا الملف. |
| showSlideTitle | boolean | إضافة عنوان الشريحة إذا كان موجودًا فوق صورة الشريحة. |

**القيمة المرجعة:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - الكائن [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


ينشئ ويُعيد مُنسق HTML لعرض شرائح بسيط يُظهر الشرائح واحدة تلو الأخرى.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| css | java.lang.String | يحدد عنوان URL لملف CSS المستخدم. |
| showSlideTitle | boolean | إضافة عنوان الشريحة إذا كان موجودًا فوق صورة الشريحة. |

**القيمة المرجعة:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - الكائن [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


ينشئ ويُعيد مُنسق HTML لتوليد HTML مخصص يعتمد على رد نداء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | واجهة رد النداء التي تتحكم في توليد ملف HTML. |

**القيمة المرجعة:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - الكائن [HtmlFormatter](../../com.aspose.slides/htmlformatter).