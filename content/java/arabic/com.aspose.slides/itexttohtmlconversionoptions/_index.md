---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: خيارات استخراج HTML من نص Pptx.
type: docs
url: /ar/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

خيارات استخراج HTML من نص Pptx.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | إرجاع أو ضبط القيمة، مما يدل على ما إذا كان يجب إضافة رؤوس الحافظة. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | إرجاع أو ضبط القيمة، مما يدل على ما إذا كان يجب إضافة رؤوس الحافظة. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | إرجاع أو ضبط عمق الوراثة لخصائص النص. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | إرجاع أو ضبط عمق الوراثة لخصائص النص. |
| [getLinkEmbedController()](#getLinkEmbedController--) | إرجاع أو ضبط كائن الاستدعاء الذي يتحكم في كيفية تخزين الكائن الخارجي. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | إرجاع أو ضبط كائن الاستدعاء الذي يتحكم في كيفية تخزين الكائن الخارجي. |
| [getEncodingName()](#getEncodingName--) | إرجاع أو ضبط اسم ترميز html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | إرجاع أو ضبط اسم ترميز html. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


إرجاع أو ضبط القيمة، مما يدل على ما إذا كان يجب إضافة رؤوس الحافظة. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


إرجاع أو ضبط القيمة، مما يدل على ما إذا كان يجب إضافة رؤوس الحافظة. قراءة/كتابة منطقية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


إرجاع أو ضبط عمق الوراثة لخصائص النص. قراءة/كتابة [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**الإرجاع:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


إرجاع أو ضبط عمق الوراثة لخصائص النص. قراءة/كتابة [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


إرجاع أو ضبط كائن الاستدعاء الذي يتحكم في كيفية تخزين الكائن الخارجي. قراءة/كتابة [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**الإرجاع:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


إرجاع أو ضبط كائن الاستدعاء الذي يتحكم في كيفية تخزين الكائن الخارجي. قراءة/كتابة [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


إرجاع أو ضبط اسم ترميز html. سيتم حفظ هذه القيمة في ملف HTML المنشأ، ولكن على المتصل ضمان حفظ الملف بهذا الترميز. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


إرجاع أو ضبط اسم ترميز html. سيتم حفظ هذه القيمة في ملف HTML المنشأ، ولكن على المتصل ضمان حفظ الملف بهذا الترميز. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |