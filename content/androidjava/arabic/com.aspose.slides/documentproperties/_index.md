---
title: DocumentProperties
second_title: مرجع API لجافا عبر Aspose.Slides لنظام Android
description: يمثل خصائص العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/documentproperties/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable  
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

يمثّل خصائص العرض التقديمي.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // إنشاء كائن من الفئة Presentation التي تمثل العرض التقديمي
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // إنشاء مرجع لكائن IDocumentProperties المرتبط بالعرض التقديمي
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // عرض الخصائص المدمجة
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // إنشاء كائن من الفئة Presentation التي تمثل العرض التقديمي
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // إنشاء مرجع لكائن IDocumentProperties المرتبط بالعرض التقديمي
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // تعيين الخصائص المدمجة
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // حفظ العرض التقديمي إلى ملف
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | ينشئ نسخة جديدة من الفئة [DocumentProperties](../../com.aspose.slides/documentproperties). |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | إرجاع نسخة التطبيق. |
| [getNameOfApplication()](#getNameOfApplication--) | إرجاع أو ضبط اسم التطبيق. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | إرجاع أو ضبط اسم التطبيق. |
| [getCompany()](#getCompany--) | إرجاع أو ضبط خاصية الشركة. |
| [setCompany(String value)](#setCompany-java.lang.String-) | إرجاع أو ضبط خاصية الشركة. |
| [getManager()](#getManager--) | إرجاع أو ضبط خاصية المدير. |
| [setManager(String value)](#setManager-java.lang.String-) | إرجاع أو ضبط خاصية المدير. |
| [getPresentationFormat()](#getPresentationFormat--) | إرجاع أو ضبط الصيغة المقصودة للعرض التقديمي. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | إرجاع أو ضبط الصيغة المقصودة للعرض التقديمي. |
| [getSharedDoc()](#getSharedDoc--) | تحديد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | تحديد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. |
| [getApplicationTemplate()](#getApplicationTemplate--) | إرجاع أو ضبط قالب التطبيق. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | إرجاع أو ضبط قالب التطبيق. |
| [getTotalEditingTime()](#getTotalEditingTime--) | إجمالي وقت التحرير للعرض التقديمي. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | إجمالي وقت التحرير للعرض التقديمي. |
| [getTitle()](#getTitle--) | إرجاع أو ضبط عنوان العرض التقديمي. |
| [setTitle(String value)](#setTitle-java.lang.String-) | إرجاع أو ضبط عنوان العرض التقديمي. |
| [getSubject()](#getSubject--) | إرجاع أو ضبط موضوع العرض التقديمي. |
| [setSubject(String value)](#setSubject-java.lang.String-) | إرجاع أو ضبط موضوع العرض التقديمي. |
| [getAuthor()](#getAuthor--) | إرجاع أو ضبط مؤلف العرض التقديمي. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | إرجاع أو ضبط مؤلف العرض التقديمي. |
| [getKeywords()](#getKeywords--) | إرجاع أو ضبط كلمات مفتاحية للعرض التقديمي. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | إرجاع أو ضبط كلمات مفتاحية للعرض التقديمي. |
| [getComments()](#getComments--) | إرجاع أو ضبط تعليقات على العرض التقديمي. |
| [setComments(String value)](#setComments-java.lang.String-) | إرجاع أو ضبط تعليقات على العرض التقديمي. |
| [getCategory()](#getCategory--) | إرجاع أو ضبط فئة للعرض التقديمي. |
| [setCategory(String value)](#setCategory-java.lang.String-) | إرجاع أو ضبط فئة للعرض التقديمي. |
| [getCreatedTime()](#getCreatedTime--) | إرجاع تاريخ إنشاء العرض التقديمي. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | إرجاع تاريخ إنشاء العرض التقديمي. |
| [getLastSavedTime()](#getLastSavedTime--) | إرجاع تاريخ آخر تعديل للعرض التقديمي. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | إرجاع تاريخ آخر تعديل للعرض التقديمي. |
| [getLastPrinted()](#getLastPrinted--) | إرجاع تاريخ آخر طباعة للعرض التقديمي. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | إرجاع تاريخ آخر طباعة للعرض التقديمي. |
| [getLastSavedBy()](#getLastSavedBy--) | إرجاع أو ضبط اسم آخر شخص عدل العرض التقديمي. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | إرجاع أو ضبط اسم آخر شخص عدل العرض التقديمي. |
| [getRevisionNumber()](#getRevisionNumber--) | إرجاع أو ضبط رقم مراجعة العرض التقديمي. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | إرجاع أو ضبط رقم مراجعة العرض التقديمي. |
| [getContentStatus()](#getContentStatus--) | إرجاع أو ضبط حالة محتوى العرض التقديمي. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | إرجاع أو ضبط حالة محتوى العرض التقديمي. |
| [getContentType()](#getContentType--) | إرجاع أو ضبط نوع محتوى العرض التقديمي. |
| [setContentType(String value)](#setContentType-java.lang.String-) | إرجاع أو ضبط نوع محتوى العرض التقديمي. |
| [getHyperlinkBase()](#getHyperlinkBase--) | إرجاع أو ضبط خاصية HyperlinkBase للمستند. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | إرجاع أو ضبط خاصية HyperlinkBase للمستند. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | إرجاع عدد الخصائص المخصصة الموجودة في المجموعة. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | إرجاع اسم خاصية مخصصة عند الفهرس المحدد. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | إزالة خاصية مخصصة مرتبطة باسم محدد. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | التحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | إرجاع أو ضبط خاصية مخصصة مرتبطة باسم محدد. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | إرجاع أو ضبط خاصية مخصصة مرتبطة باسم محدد. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | يحصل على قيمة Boolean مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | يحصل على قيمة Integer مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | يحصل على قيمة DateTime مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | يحصل على قيمة String مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | يحصل على قيمة Float مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | يحصل على قيمة Double مسماة من الخصائص المخصصة. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | يضبط خاصية مخصصة Boolean مسماة. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | يضبط خاصية مخصصة Integer مسماة. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | يضبط خاصية مخصصة DateTime مسماة. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | يضبط خاصية مخصصة String مسماة. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | يضبط خاصية مخصصة Float مسماة. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | يضبط خاصية مخصصة Double مسماة. |
| [clearCustomProperties()](#clearCustomProperties--) | إزالة جميع الخصائص المخصصة. |
| [getSensitivityLabels()](#getSensitivityLabels--) | يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | مسح وضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [getScaleCrop()](#getScaleCrop--) | يحدد وضع عرض صورة المصغرة للمستند. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | يحدد وضع عرض صورة المصغرة للمستند. |
| [getLinksUpToDate()](#getLinksUpToDate--) | يحدد ما إذا كانت الروابط التشعبية في المستند محدثة. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | يحدد ما إذا كانت الروابط التشعبية في المستند محدثة. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | يوضح أن رابطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | يوضح أن رابطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. |
| [getSlides()](#getSlides--) | إرجاع إجمالي عدد الشرائح في مستند عرض تقديمي. |
| [getHiddenSlides()](#getHiddenSlides--) | إرجاع عدد الشرائح المخفية في مستند عرض تقديمي. |
| [getNotes()](#getNotes--) | إرجاع عدد الشرائح التي تحتوي على ملاحظات في عرض تقديمي. |
| [getParagraphs()](#getParagraphs--) | إرجاع إجمالي عدد الفقرات الموجودة في المستند إذا كان ذلك قابلًا للتطبيق. |
| [getWords()](#getWords--) | إرجاع إجمالي عدد الكلمات المتضمنة في المستند. |
| [getMultimediaClips()](#getMultimediaClips--) | إرجاع إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. |
| [getTitlesOfParts()](#getTitlesOfParts--) | يحدد عنوان كل جزء من أجزاء المستند. |
| [getHeadingPairs()](#getHeadingPairs--) | يوضح تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. |
| [deepClone()](#deepClone--) | استنساخ الكائن الحالي |
| [cloneT()](#cloneT--) | استنساخ الكائن الحالي |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

ينشئ نسخة جديدة من الفئة [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

إرجاع نسخة التطبيق. **Read-only** String.

**الإرجاع:**  
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

إرجاع أو ضبط اسم التطبيق. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

إرجاع أو ضبط اسم التطبيق. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

إرجاع أو ضبط خاصية الشركة. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

إرجاع أو ضبط خاصية الشركة. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

إرجاع أو ضبط خاصية المدير. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

إرجاع أو ضبط خاصية المدير. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

إرجاع أو ضبط الصيغة المقصودة للعرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

إرجاع أو ضبط الصيغة المقصودة للعرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

تحديد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. **Read/write** boolean.

**الإرجاع:**  
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

تحديد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. **Read/write** boolean.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

إرجاع أو ضبط قالب التطبيق. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

إرجاع أو ضبط قالب التطبيق. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

إجمالي وقت التحرير للعرض التقديمي. **Read/write** double.

**الإرجاع:**  
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

إجمالي وقت التحرير للعرض التقديمي. **Read/write** double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

إرجاع أو ضبط عنوان العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

إرجاع أو ضبط عنوان العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

إرجاع أو ضبط موضوع العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

إرجاع أو ضبط موضوع العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

إرجاع أو ضبط مؤلف العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

إرجاع أو ضبط مؤلف العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

إرجاع أو ضبط الكلمات المفتاحية للعرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

إرجاع أو ضبط الكلمات المفتاحية للعرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

إرجاع أو ضبط تعليقات العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

إرجاع أو ضبط تعليقات العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

إرجاع أو ضبط فئة العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

إرجاع أو ضبط فئة العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

إرجاع تاريخ إنشاء العرض التقديمي. القيم بالتوقيت المتفق عليه (UTC). **Read/write** java.util.Date.

**الإرجاع:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

إرجاع تاريخ إنشاء العرض التقديمي. القيم بالتوقيت المتفق عليه (UTC). **Read/write** java.util.Date.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

إرجاع تاريخ آخر تعديل للعرض التقديمي. القيم بالتوقيت المتفق عليه (UTC). **Read-only** في حالة Presentation.DocumentProperties (لأنها تُحدّث داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties المرجع من الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). يرجى مراجعة المثال في ملخص الطريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**الإرجاع:**  
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

إرجاع تاريخ آخر تعديل للعرض التقديمي. القيم بالتوقيت المتفق عليه (UTC). **Read-only** في حالة Presentation.DocumentProperties (لأنها تُحدّث داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties المرجع من الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). يرجى مراجعة المثال في ملخص الطريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

إرجاع تاريخ آخر طباعة للعرض التقديمي. **Read/write** java.util.Date.

**الإرجاع:**  
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

إرجاع تاريخ آخر طباعة للعرض التقديمي. **Read/write** java.util.Date.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

إرجاع أو ضبط اسم آخر شخص عدل العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

إرجاع أو ضبط اسم آخر شخص عدل العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

إرجاع أو ضبط رقم مراجعة العرض التقديمي. **Read/write** int.

**الإرجاع:**  
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

إرجاع أو ضبط رقم مراجعة العرض التقديمي. **Read/write** int.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

إرجاع أو ضبط حالة محتوى العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

إرجاع أو ضبط حالة محتوى العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

إرجاع أو ضبط نوع محتوى العرض التقديمي. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

إرجاع أو ضبط نوع محتوى العرض التقديمي. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

إرجاع أو ضبط خاصية HyperlinkBase للمستند. **Read/write** String.

**الإرجاع:**  
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

إرجاع أو ضبط خاصية HyperlinkBase للمستند. **Read/write** String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

إرجاع عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. **Read-only** int.

**الإرجاع:**  
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

إرجاع اسم خاصية مخصصة عند الفهرس المحدد.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخاصية المخصصة المطلوب إرجاعها. |

**الإرجاع:**  
java.lang.String - اسم الخاصية المخصصة عند الفهرس المحدد.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

إزالة خاصية مخصصة مرتبطة باسم محدد.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المراد إزالتها. |

**الإرجاع:**  
boolean - إرجاع true إذا تمت إزالة الخاصية، false غير ذلك.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

التحقق من وجود خاصية مخصصة بالاسم المحدد.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة للتحقق منها. |

**الإرجاع:**  
boolean - إرجاع true إذا كانت الخاصية موجودة، false غير ذلك.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

إرجاع أو ضبط الخاصية المخصصة المرتبطة بالاسم المحدد. **Read/write** Object.

--------------------

القيمة يمكن أن تكون **int**, **float**, **String**, **boolean** أو **Date**.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**الإرجاع:**  
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

إرجاع أو ضبط الخاصية المخصصة المرتبطة بالاسم المحدد. **Read/write** Object.

--------------------

القيمة يمكن أن تكون **int**, **float**, **String**, **boolean** أو **Date**.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

يحصل على قيمة Boolean مسماة من الخصائص المخصصة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المطلوب الحصول عليها |
| value | boolean[] | قيمة الخاصية المخصّصة |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

يحصل على قيمة Integer مسماة من الخصائص المخصصة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المطلوب الحصول عليها |
| value | int[] | قيمة الخاصية المخصّصة |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

يحصل على قيمة DateTime مسماة من الخصائص المخصصة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المطلوب الحصول عليها |
| value | java.util.Date[] | قيمة الخاصية المخصّصة |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

يحصل على قيمة String مسماة من الخصائص المخصصة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المطلوب الحصول عليها |
| value | java.lang.String[] | قيمة الخاصية المخصّصة |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

يحصل على قيمة Float مسماة من الخصائص المخصصة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المطلوب الحصول عليها |
| value | float[] | قيمة الخاصية المخصّصة |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

يحصل على قيمة Double مسماة من الخصائص المخصصة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة المطلوب الحصول عليها. |
| value | double[] | قيمة الخاصية المخصّصة |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

يضبط خاصية مخصصة Boolean مسماة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة لتعيينها |
| value | boolean | قيمة الخاصية المخصّصة |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

يضبط خاصية مخصصة Integer مسماة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة لتعيينها |
| value | int | قيمة الخاصية المخصّصة |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

يضبط خاصية مخصصة DateTime مسماة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة لتعيينها |
| value | java.util.Date | قيمة الخاصية المخصّصة |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

يضبط خاصية مخصصة String مسماة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة لتعيينها |
| value | java.lang.String | قيمة الخاصية المخصّصة |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

يضبط خاصية مخصصة Float مسماة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة لتعيينها |
| value | float | قيمة الخاصية المخصّصة |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

يضبط خاصية مخصصة Double مسماة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصّصة لتعيينها |
| value | double | قيمة الخاصية المخصّصة |
### clearCustomProperties() {#clearCustomProperties--}
```
public  



```

إزالة جميع الخصائص المخصصة.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // الحصول على تسميات الحساسية من خصائص المستند المخصصة
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // إضافة التسمية إلى المجموعة
>          // هنا يمكنك إضافة فحص لصحة معلومات التسمية (التسمية متاحة، إلخ)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

مسح وضبط القيم الافتراضية لجميع الخصائص المدمجة.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

يحدد وضع عرض صورة المصغرة للمستند. عيّن هذا العنصر إلى **true** لتمكين تحجيم صورة المصغرة للمستند لتملأ العرض. عيّن إلى **false** لتمكين قص صورة المصغرة لإظهار الأقسام التي تناسب العرض. **Read/write** boolean.

**الإرجاع:**  
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

يحدد وضع عرض صورة المصغرة للمستند. عيّن هذا العنصر إلى **true** لتمكين تحجيم صورة المصغرة للمستند لتملأ العرض. عيّن إلى **false** لتمكين قص صورة المصغرة لإظهار الأقسام التي تناسب العرض. **Read/write** boolean.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

يحدد ما إذا كانت الروابط التشعبية في المستند محدثة. عيّن هذا العنصر إلى **true** للدلالة على أن الروابط محدثة. عيّن إلى **false** للدلالة على أن الروابط قديمة. **Read/write** boolean.

**الإرجاع:**  
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

يحدد ما إذا كانت الروابط التشعبية في المستند محدثة. عيّن هذا العنصر إلى **true** للدلالة على أن الروابط محدثة. عيّن إلى **false** للدلالة على أن الروابط قديمة. **Read/write** boolean.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

يحدد أن رابطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذا المستند بتحديث علاقات الروابط التشعبية بالروابط الجديدة المحددة في هذا الجزء. **Read/write** boolean.

**الإرجاع:**  
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

يحدد أن رابطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذا المستند بتحديث علاقات الروابط التشعبية بالروابط الجديدة المحددة في هذا الجزء. **Read/write** boolean.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

إرجاع إجمالي عدد الشرائح في مستند عرض تقديمي. **Read-only** int.

**الإرجاع:**  
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

إرجاع عدد الشرائح المخفية في مستند عرض تقديمي. **Read-only** int.

**الإرجاع:**  
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

إرجاع عدد الشرائح التي تحتوي على ملاحظات في عرض تقديمي. **Read-only** int.

**الإرجاع:**  
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

إرجاع إجمالي عدد الفقرات الموجودة في المستند إذا كان ذلك قابلًا للتطبيق. **Read-only** int.

**الإرجاع:**  
int
### getWords() {#getWords--}
```
public final int getWords()
```

إرجاع إجمالي عدد الكلمات المتضمنة في المستند. **Read-only** int.

**الإرجاع:**  
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final



```

إرجاع إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. **Read-only** int.

**الإرجاع:**  
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

يحدد عنوان كل جزء من أجزاء المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفاهيمية لأقسام المستند. **Read-only** String[].

**الإرجاع:**  
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

يحدد تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. **Read-only** IHeadingPair[].

**الإرجاع:**  
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

استنساخ الكائن الحالي

**الإرجاع:**  
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

استنساخ الكائن الحالي

**الإرجاع:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone