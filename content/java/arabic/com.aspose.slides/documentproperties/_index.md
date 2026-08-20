---
title: DocumentProperties
second_title: مرجع API ل Aspose.Slides للـ Java
description: يمثل خصائص العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/documentproperties/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

يمثل خصائص عرض تقديمي.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // إنشاء كائن من فئة Presentation التي تمثل العرض التقديمي
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // إنشاء مرجع إلى كائن IDocumentProperties المرتبط بالعرض التقديمي
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
>  // إنشاء كائن من فئة Presentation التي تمثل العرض التقديمي
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // إنشاء مرجع إلى كائن IDocumentProperties المرتبط بالعرض التقديمي
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // تعيين الخصائص المدمجة
>      documentProperties.setAuthor("Aspose.Slides for Java");
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
| [DocumentProperties()](#DocumentProperties--) | يقوم بتهيئة نسخة جديدة من الفئة [DocumentProperties](../../com.aspose.slides/documentproperties). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | يعيد نسخة التطبيق. |
| [getNameOfApplication()](#getNameOfApplication--) | يعيد أو يضبط اسم التطبيق. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | يعيد أو يضبط اسم التطبيق. |
| [getCompany()](#getCompany--) | يعيد أو يضبط خاصية الشركة. |
| [setCompany(String value)](#setCompany-java.lang.String-) | يعيد أو يضبط خاصية الشركة. |
| [getManager()](#getManager--) | يعيد أو يضبط خاصية المدير. |
| [setManager(String value)](#setManager-java.lang.String-) | يعيد أو يضبط خاصية المدير. |
| [getPresentationFormat()](#getPresentationFormat--) | يعيد أو يضبط الصيغة المقصودة للعرض التقديمي. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | يعيد أو يضبط الصيغة المقصودة للعرض التقديمي. |
| [getSharedDoc()](#getSharedDoc--) | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. |
| [getApplicationTemplate()](#getApplicationTemplate--) | يعيد أو يضبط القالب لتطبيق. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | يعيد أو يضبط القالب لتطبيق. |
| [getTotalEditingTime()](#getTotalEditingTime--) | إجمالي وقت تعديل العرض التقديمي. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | إجمالي وقت تعديل العرض التقديمي. |
| [getTitle()](#getTitle--) | يعيد أو يضبط عنوان العرض التقديمي. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يعيد أو يضبط عنوان العرض التقديمي. |
| [getSubject()](#getSubject--) | يعيد أو يضبط موضوع العرض التقديمي. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يعيد أو يضبط موضوع العرض التقديمي. |
| [getAuthor()](#getAuthor--) | يعيد أو يضبط مؤلف العرض التقديمي. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | يعيد أو يضبط مؤلف العرض التقديمي. |
| [getKeywords()](#getKeywords--) | يعيد أو يضبط الكلمات المفتاحية للعرض التقديمي. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | يعيد أو يضبط الكلمات المفتاحية للعرض التقديمي. |
| [getComments()](#getComments--) | يعيد أو يضبط التعليقات على العرض التقديمي. |
| [setComments(String value)](#setComments-java.lang.String-) | يعيد أو يضبط التعليقات على العرض التقديمي. |
| [getCategory()](#getCategory--) | يعيد أو يضبط فئة العرض التقديمي. |
| [setCategory(String value)](#setCategory-java.lang.String-) | يعيد أو يضبط فئة العرض التقديمي. |
| [getCreatedTime()](#getCreatedTime--) | يعيد تاريخ إنشاء العرض التقديمي. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | يعيد تاريخ إنشاء العرض التقديمي. |
| [getLastSavedTime()](#getLastSavedTime--) | يعيد تاريخ آخر تعديل للعرض التقديمي. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | يعيد تاريخ آخر تعديل للعرض التقديمي. |
| [getLastPrinted()](#getLastPrinted--) | يعيد تاريخ آخر طباعة للعرض التقديمي. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | يعيد تاريخ آخر طباعة للعرض التقديمي. |
| [getLastSavedBy()](#getLastSavedBy--) | يعيد أو يضبط اسم آخر شخص عدل العرض التقديمي. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | يعيد أو يضبط اسم آخر شخص عدل العرض التقديمي. |
| [getRevisionNumber()](#getRevisionNumber--) | يعيد أو يضبط رقم مراجعة العرض التقديمي. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | يعيد أو يضبط رقم مراجعة العرض التقديمي. |
| [getContentStatus()](#getContentStatus--) | يعيد أو يضبط حالة محتوى العرض التقديمي. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | يعيد أو يضبط حالة محتوى العرض التقديمي. |
| [getContentType()](#getContentType--) | يعيد أو يضبط نوع محتوى العرض التقديمي. |
| [setContentType(String value)](#setContentType-java.lang.String-) | يعيد أو يضبط نوع محتوى العرض التقديمي. |
| [getHyperlinkBase()](#getHyperlinkBase--) | يعيد أو يضبط خاصية HyperlinkBase للوثيقة. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | يعيد أو يضبط خاصية HyperlinkBase للوثيقة. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | يعيد عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | يرجع اسم خاصية مخصصة عند الفهرس المحدد. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | يزيل خاصية مخصصة مرتبطة بالاسم المحدد. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | يعيد أو يضبط الخاصية المخصصة المرتبطة بالاسم المحدد. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يعيد أو يضبط الخاصية المخصصة المرتبطة بالاسم المحدد. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | يضبط خاصية مخصصة منطقية مسماة. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | يضبط خاصية مخصصة عددية مسماة. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | يضبط خاصية مخصصة تاريخية مسماة. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | يضبط خاصية مخصصة سلسلة مسماة. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | يضبط خاصية مخصصة عائمة مسماة. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | يضبط خاصية مخصصة مزدوجة مسماة. |
| [clearCustomProperties()](#clearCustomProperties--) | يزيل جميع الخصائص المخصصة. |
| [getSensitivityLabels()](#getSensitivityLabels--) | يحصل على مصفوفة من تسميات الحساسية من الخصائص المخصصة للمستند (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | يمسح ويضبط القيم الافتراضية لجميع builtIn الخصائص. |
| [getScaleCrop()](#getScaleCrop--) | يشير إلى وضع عرض صورة مصغرة للمستند. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | يشير إلى وضع عرض صورة مصغرة للمستند. |
| [getLinksUpToDate()](#getLinksUpToDate--) | يشير إلى ما إذا كانت الروابط التشعبية في المستند محدثة. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | يشير إلى ما إذا كانت الروابط التشعبية في المستند محدثة. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | يحدد أن رابطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة المنتج. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | يحدد أن رابطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة المنتج. |
| [getSlides()](#getSlides--) | يعيد العدد الإجمالي للشرائح في مستند عرض تقديمي. |
| [getHiddenSlides()](#getHiddenSlides--) | يعيد عدد الشرائح المخفية في مستند عرض تقديمي. |
| [getNotes()](#getNotes--) | يعيد عدد الشرائح التي تحتوي على ملاحظات في العرض التقديمي. |
| [getParagraphs()](#getParagraphs--) | يعيد العدد الإجمالي للفقرات الموجودة في المستند إذا كان ذلك ممكنًا. |
| [getWords()](#getWords--) | يعيد العدد الإجمالي للكلمات الموجودة في المستند. |
| [getMultimediaClips()](#getMultimediaClips--) | يعيد العدد الإجمالي لمقاطع الصوت أو الفيديو الموجودة في المستند. |
| [getTitlesOfParts()](#getTitlesOfParts--) | يحدد عنوان كل جزء من المستند. |
| [getHeadingPairs()](#getHeadingPairs--) | يشير إلى تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. |
| [deepClone()](#deepClone--) | ينسخ الكائن الحالي |
| [cloneT()](#cloneT--) | ينسخ الكائن الحالي |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

يقوم بتهيئة نسخة جديدة من الفئة [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

يعيد نسخة التطبيق. String للقراءة فقط.

**الإرجاع:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

يعيد أو يضبط اسم التطبيق. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

يعيد أو يضبط اسم التطبيق. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

يعيد أو يضبط خاصية الشركة. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

يعيد أو يضبط خاصية الشركة. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

يعيد أو yضبط خاصية المدير. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

يعيد أو yضبط خاصية المدير. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

يعيد أو yضبط الصيغة المقصودة للعرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

يعيد أو yضبط الصيغة المقصودة للعرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. boolean للقراءة والكتابة.

**الإرجاع:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. boolean للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

يعيد أو yضبط قالب التطبيق. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

يعيد أو yضبط قالب التطبيق. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

إجمالي وقت تعديل العرض التقديمي. double للقراءة والكتابة.

**الإرجاع:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

إجمالي وقت تعديل العرض التقديمي. double للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

يعيد أو yضبط عنوان العرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

يعيد أو yضبط عنوان العرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

يعيد أو yضبط موضوع العرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

يعيد أو yضبط موضوع العرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

يعيد أو yضبط مؤلف العرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

يعيد أو yضبط مؤلف العرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

يعيد أو yضبط الكلمات المفتاحية للعرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

يعيد أو yضبط الكلمات المفتاحية للعرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

يعيد أو yضبط التعليقات على العرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

يعيد أو yضبط التعليقات على العرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

يعيد أو yضبط فئة العرض التقديمي. String للقراءة والكتابة.

**الإرجاع:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

يعيد أو yضبط فئة العرض التقديمي. String للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
تُرجِع تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قابل للقراءة والكتابة java.util.Date.

**الإرجاع:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


تُرجِع تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قابل للقراءة والكتابة java.util.Date.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


تُرجِع تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. للقراءة فقط في حالة Presentation.DocumentProperties (لأنه سيتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر كائن DocumentProperties المسترجع بواسطة الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) يرجى مراجعة المثال في ملخص الطريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**الإرجاع:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


تُرجِع تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. للقراءة فقط في حالة Presentation.DocumentProperties (لأنه سيتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر كائن DocumentProperties المسترجع بواسطة الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) يرجى مراجعة المثال في ملخص الطريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


تُرجِع تاريخ آخر مرة تم فيها طباعة العرض التقديمي. قابل للقراءة والكتابة java.util.Date.

**الإرجاع:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


تُرجِع تاريخ آخر مرة تم فيها طباعة العرض التقديمي. قابل للقراءة والكتابة java.util.Date.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


تُرجِع أو تعيين اسم آخر شخص عَدل العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


تُرجِع أو تعيين اسم آخر شخص عَدل العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


تُرجِع أو تعيين رقم إصدارة العرض التقديمي. قابل للقراءة والكتابة int.

**الإرجاع:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


تُرجِع أو تعيين رقم إصدارة العرض التقديمي. قابل للقراءة والكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


تُرجِع أو تعيين حالة محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


تُرجِع أو تعيين حالة محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


تُرجِع أو تعيين نوع محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


تُرجِع أو تعيين نوع محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


تُرجِع أو تعيين خاصية HyperlinkBase للوثيقة. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


تُرجِع أو تعيين خاصية HyperlinkBase للوثيقة. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


تُرجِع عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. للقراءة فقط int.

**الإرجاع:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


إرجاع اسم خاصية مخصصة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخاصية المخصصة المراد الحصول عليها. |

**الإرجاع:**
java.lang.String - اسم الخاصية المخصصة في الفهرس المحدد.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


إزالة خاصية مخصصة مرتبطة بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد إزالتها. |

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
| name | java.lang.String | اسم الخاصية المخصصة للتحقق منها. |

**الإرجاع:**
boolean - إرجاع true إذا كانت الخاصية موجودة، false غير ذلك.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


تُرجِع أو تعيين الخاصية المخصصة المرتبطة بالاسم المحدد. قابل للقراءة والكتابة Object.

--------------------

يمكن أن تكون القيمة **int**, **float**, **String**, **boolean** أو **Date**.

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


تُرجِع أو تعيين الخاصية المخصصة المرتبطة بالاسم المحدد. قابل للقراءة والكتابة Object.

--------------------

يمكن أن تكون القيمة **int**, **float**, **String**, **boolean** أو **Date**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


الحصول على قيمة منطقية مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها |
| value | boolean[] | قيمة الخاصية المخصصة |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


الحصول على قيمة عددية صحيحة مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها |
| value | int[] | قيمة الخاصية المخصصة |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


الحصول على قيمة DateTime مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها |
| value | java.util.Date[] | قيمة الخاصية المخصصة |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


الحصول على قيمة نصية مسماة من الخصائص المخصصة.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها |
| value | java.lang.String[] | قيمة الخاصية المخصصة |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


الحصول على قيمة عائمة مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها |
| value | float[] | قيمة الخاصية المخصصة |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


الحصول على قيمة مزدوجة مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها |
| value | double[] | قيمة الخاصية المخصصة |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


تعيين خاصية مخصصة منطقية مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد تعيينها |
| value | boolean | قيمة الخاصية المخصصة |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


تعيين خاصية مخصصة عددية صحيحة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد تعيينها |
| value | int | قيمة الخاصية المخصصة |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


تعيين خاصية مخصصة من نوع DateTime مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد تعيينها |
| value | java.util.Date | قيمة الخاصية المخصصة |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


تعيين خاصية مخصصة نصية مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد تعيينها |
| value | java.lang.String | قيمة الخاصية المخصصة |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


تعيين خاصية مخصصة عائمة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد تعيينها |
| value | float | قيمة الخاصية المخصصة |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


تعيين خاصية مخصصة مزدوجة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد تعيينها |
| value | double | قيمة الخاصية المخصصة |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


إزالة جميع الخصائص المخصصة.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


الحصول على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // الحصول على ملصقات الحساسية من خصائص المستند المخصصة
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // إضافة الملصق إلى المجموعة
>          // يمكنك هنا إضافة فحص لصحة معلومات الملصق (الملصق متاح، إلخ)
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


إزالة وتعيين القيم الافتراضية لجميع الخصائص المدمجة.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```


يشير إلى وضع عرض صورة المصغرات للوثيقة. ضع هذا العنصر على **true** لتفعيل تكبير صورة المصغرات لتناسب العرض. ضع هذا العنصر على **false** لتفعيل قص صورة المصغرات لعرض الأقسام التي تناسب العرض فقط. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


يشير إلى وضع عرض صورة المصغرات للوثيقة. ضع هذا العنصر على **true** لتفعيل تكبير صورة المصغرات لتناسب العرض. ضع هذا العنصر على **false** لتفعيل قص صورة المصغرات لعرض الأقسام التي تناسب العرض فقط. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


يشير إلى ما إذا كانت الروابط التشعبية في المستند محدثة. ضع هذا العنصر على **true** للدلالة على أن الروابط محدثة. ضع هذا العنصر على **false** للدلالة على أن الروابط غير محدثة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read/write boolean.

**Returns:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Returns the total number of slides in a presentation document. Read-only int.

**Returns:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Returns the number of hidden slides in a presentation document. Read-only int.

**Returns:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Returns the number of slides in a presentation containing notes. Read-only int.

**Returns:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Returns the total number of paragraphs found in a document if applicable. Read-only int.

**Returns:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Returns the total number of words contained in a document. Read-only int.

**Returns:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Returns the total number of sound or video clips that are present in the document. Read-only int.

**Returns:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Specifies the title of each document part. These parts are not document parts but conceptual representations of document sections. Read-only String[].

**Returns:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Indicates the grouping of document parts and the number of parts in each group. Read-only IHeadingPair[].

**Returns:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clones current object

**Returns:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Clones current object

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone