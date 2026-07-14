---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: خيارات استخراج HTML من نص Pptx.
type: docs
url: /ar/com.aspose.slides/texttohtmlconversionoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

خيارات استخراج HTML من نص الـ Pptx.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## الدوال

| الطريقة | الوصف |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | إرجاع أو تعيين قيمة، تُشير إلى ما إذا كان يجب إضافة رؤوس الحافظة. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | إرجاع أو تعيين قيمة، تُشير إلى ما إذا كان يجب إضافة رؤوس الحافظة. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | إرجاع أو تعيين عمق الوراثة للخصائص النصية. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | إرجاع أو تعيين عمق الوراثة للخصائص النصية. |
| [getLinkEmbedController()](#getLinkEmbedController--) | إرجاع أو تعيين كائن رد نداء يتحكم في كيفية تخزين الكائن الخارجي. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | إرجاع أو تعيين كائن رد نداء يتحكم في كيفية تخزين الكائن الخارجي. |
| [getEncodingName()](#getEncodingName--) | إرجاع أو تعيين اسم ترميز HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | إرجاع أو تعيين اسم ترميز HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


إرجاع أو تعيين قيمة، تُشير إلى ما إذا كان يجب إضافة رؤوس الحافظة. قابل للقراءة/الكتابة boolean.

**الإرجاع:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


إرجاع أو تعيين قيمة، تُشير إلى ما إذا كان يجب إضافة رؤوس الحافظة. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


إرجاع أو تعيين عمق الوراثة للخصائص النصية. قابل للقراءة/الكتابة [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**الإرجاع:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


إرجاع أو تعيين عمق الوراثة للخصائص النصية. قابل للقراءة/الكتابة [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


إرجاع أو تعيين كائن رد نداء يتحكم في كيفية تخزين الكائن الخارجي. قابل للقراءة/الكتابة [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**الإرجاع:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


إرجاع أو تعيين كائن رد نداء يتحكم في كيفية تخزين الكائن الخارجي. قابل للقراءة/الكتابة [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


إرجاع أو تعيين اسم ترميز HTML. سيتم حفظ هذه القيمة في ملف HTML المُنشأ، لكن الأمر متروك للمتصل لضمان حفظ الملف بهذا الترميز. قابل للقراءة/الكتابة String.

**الإرجاع:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


إرجاع أو تعيين اسم ترميز HTML. سيتم حفظ هذه القيمة في ملف HTML المُنشأ، لكن الأمر متروك للمتصل لضمان حفظ الملف بهذا الترميز. قابل للقراءة/الكتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |