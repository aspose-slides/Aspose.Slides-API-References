---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: خيارات استخراج HTML من نص Pptx.
type: docs
url: /ar/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

خيارات استخراج HTML من نص Pptx.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | يعيد أو يضبط القيمة، مشيراً إلى ما إذا كان يجب إضافة رؤوس الحافظة. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | يعيد أو يضبط القيمة، مشيراً إلى ما إذا كان يجب إضافة رؤوس الحافظة. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | يعيد أو يضبط عمق الوراثة للخصائص النصية. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | يعيد أو يضبط عمق الوراثة للخصائص النصية. |
| [getLinkEmbedController()](#getLinkEmbedController--) | يعيد أو يضبط كائن رد النداء الذي يتحكم في كيفية تخزين الكائن الخارجي. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | يعيد أو يضبط كائن رد النداء الذي يتحكم في كيفية تخزين الكائن الخارجي. |
| [getEncodingName()](#getEncodingName--) | يعيد أو يضبط اسم ترميز HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | يعيد أو يضبط اسم ترميز HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

يعيد أو يضبط القيمة، مشيراً إلى ما إذا كان يجب إضافة رؤوس الحافظة. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

يعيد أو يضبط القيمة، مشيراً إلى ما إذا كان يجب إضافة رؤوس الحافظة. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

يعيد أو يضبط عمق الوراثة للخصائص النصية. قراءة/كتابة [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**الإرجاع:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

يعيد أو يضبط عمق الوراثة للخصائص النصية. قراءة/كتابة [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

يعيد أو يضبط كائن رد النداء الذي يتحكم في كيفية تخزين الكائن الخارجي. قراءة/كتابة [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**الإرجاع:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

يعيد أو يضبط كائن رد النداء الذي يتحكم في كيفية تخزين الكائن الخارجي. قراءة/كتابة [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

يعيد أو يضبط اسم ترميز HTML. سيتم حفظ هذه القيمة في ملف HTML المُولد، لكن على المتصل التأكد من حفظ الملف بهذا الترميز. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

يعيد أو يضبط اسم ترميز HTML. سيتم حفظ هذه القيمة في ملف HTML المُولد، لكن على المتصل التأكد من حفظ الملف بهذا الترميز. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |