---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Represents properties of a presentation.
type: docs
url: /ar/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

يمثل خصائص عرض تقديمي.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | يعيد نسخة التطبيق. |
| [getNameOfApplication()](#getNameOfApplication--) | يعيد أو يضبط اسم التطبيق. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | يعيد أو يضبط اسم التطبيق. |
| [getCompany()](#getCompany--) | يعيد أو يضبط خاصية الشركة. |
| [setCompany(String value)](#setCompany-java.lang.String-) | يعيد أو يضبط خاصية الشركة. |
| [getManager()](#getManager--) | يعيد أو يضبط خاصية المدير. |
| [setManager(String value)](#setManager-java.lang.String-) | يعيد أو يضبط خاصية المدير. |
| [getPresentationFormat()](#getPresentationFormat--) | يعيد أو يضبط التنسيق المقصود للعرض التقديمي. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | يعيد أو يضبط التنسيق المقصود للعرض التقديمي. |
| [getSharedDoc()](#getSharedDoc--) | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. |
| [getApplicationTemplate()](#getApplicationTemplate--) | يعيد أو يضبط قالب التطبيق. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | يعيد أو يضبط قالب التطبيق. |
| [getTotalEditingTime()](#getTotalEditingTime--) | إجمالي وقت تحرير العرض التقديمي. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | إجمالي وقت تحرير العرض التقديمي. |
| [getTitle()](#getTitle--) | يعيد أو يضبط عنوان العرض التقديمي. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يعيد أو يضبط عنوان العرض التقديمي. |
| [getSubject()](#getSubject--) | يعيد أو يضبط موضوع العرض التقديمي. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يعيد أو يضبط موضوع العرض التقديمي. |
| [getAuthor()](#getAuthor--) | يعيد أو يضبط مؤلف العرض التقديمي. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | يعيد أو يضبط مؤلف العرض التقديمي. |
| [getKeywords()](#getKeywords--) | يعيد أو يضبط كلمات مفتاح العرض التقديمي. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | يعيد أو يضبط كلمات مفتاح العرض التقديمي. |
| [getComments()](#getComments--) | يعيد أو يضبط تعليقات العرض التقديمي. |
| [setComments(String value)](#setComments-java.lang.String-) | يعيد أو يضبط تعليقات العرض التقديمي. |
| [getCategory()](#getCategory--) | يعيد أو يضبط فئة العرض التقديمي. |
| [setCategory(String value)](#setCategory-java.lang.String-) | يعيد أو يضبط فئة العرض التقديمي. |
| [getCreatedTime()](#getCreatedTime--) | يعيد تاريخ إنشاء العرض التقديمي. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | يعيد تاريخ إنشاء العرض التقديمي. |
| [getLastSavedTime()](#getLastSavedTime--) | يعيد تاريخ آخر تعديل للعرض التقديمي. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | يعيد تاريخ آخر تعديل للعرض التقديمي. |
| [getLastPrinted()](#getLastPrinted--) | يعيد تاريخ آخر طباعة للعرض التقديمي. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | يعيد تاريخ آخر طباعة للعرض التقديمي. |
| [getLastSavedBy()](#getLastSavedBy--) | يعيد أو يضبط اسم آخر شخص عدّل العرض التقديمي. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | يعيد أو يضبط اسم آخر شخص عدّل العرض التقديمي. |
| [getRevisionNumber()](#getRevisionNumber--) | يعيد أو يضبط رقم مراجعة العرض التقديمي. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | يعيد أو يضبط رقم مراجعة العرض التقديمي. |
| [getContentStatus()](#getContentStatus--) | يعيد أو يضبط حالة محتوى العرض التقديمي. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | يعيد أو يضبط حالة محتوى العرض التقديمي. |
| [getContentType()](#getContentType--) | يعيد أو يضبط نوع محتوى العرض التقديمي. |
| [setContentType(String value)](#setContentType-java.lang.String-) | يعيد أو يضبط نوع محتوى العرض التقديمي. |
| [getHyperlinkBase()](#getHyperlinkBase--) | يعيد أو يضبط خاصية HyperlinkBase للمستند. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | يعيد أو يضبط خاصية HyperlinkBase للمستند. |
| [getScaleCrop()](#getScaleCrop--) | يشير إلى وضع عرض صورة المصغرة للمستند. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | يشير إلى وضع عرض صورة المصغرة للمستند. |
| [getLinksUpToDate()](#getLinksUpToDate--) | يشير إلى ما إذا كانت الروابط التشعبية في المستند محدثة. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | يشير إلى ما إذا كانت الروابط التشعبية في المستند محدثة. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | يحدد أن ارتباطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة المنتج. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | يحدد أن ارتباطًا تشعبيًا واحدًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة المنتج. |
| [getSlides()](#getSlides--) | يحدد العدد الإجمالي للشرائح في مستند العرض التقديمي. |
| [getHiddenSlides()](#getHiddenSlides--) | يحدد عدد الشرائح المخفية في مستند العرض التقديمي. |
| [getNotes()](#getNotes--) | يحدد عدد الشرائح في العرض التقديمي التي تحتوي على ملاحظات. |
| [getParagraphs()](#getParagraphs--) | يحدد العدد الإجمالي للفقرات الموجودة في المستند إذا كان ذلك مناسبًا. |
| [getWords()](#getWords--) | يحدد العدد الإجمالي للكلمات الموجودة في المستند. |
| [getMultimediaClips()](#getMultimediaClips--) | يحدد العدد الإجمالي لمقاطع الصوت أو الفيديو الموجودة في المستند. |
| [getTitlesOfParts()](#getTitlesOfParts--) | يحدد عنوان كل جزء من المستند. |
| [getHeadingPairs()](#getHeadingPairs--) | يشير إلى تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | يعيد عدد الخصائص المخصصة الموجودة فعليًا في مجموعة. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | يعيد اسم خاصية مخصصة في الفهرس المحدد. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | إزالة خاصية مخصصة مرتبطة باسم محدد. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | التحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | يعيد أو يضبط الخاصية المخصصة المرتبطة باسم محدد. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يعيد أو يضبط الخاصية المخصصة المرتبطة باسم محدد. |
| [clearCustomProperties()](#clearCustomProperties--) | يزيل جميع الخصائص المخصصة. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | يسترجع قيمة منطقية مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | يسترجع قيمة عددية صحيحة مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | يسترجع قيمة تاريخية مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | يسترجع قيمة نصية مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | يسترجع قيمة عائمة مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | يسترجع قيمة مزدوجة مسماة من الخصائص المخصصة. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | يضبط خاصية مخصصة منطقية مسماة. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | يضبط خاصية مخصصة عددية صحيحة مسماة. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | يضبط خاصية مخصصة تاريخية مسماة. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | يضبط خاصية مخصصة نصية مسماة. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | يضبط خاصية مخصصة عائمة مسماة. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | يضبط خاصية مخصصة مزدوجة مسماة. |
| [getSensitivityLabels()](#getSensitivityLabels--) | يحصل على مصفوفة من تصنيفات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

يعيد نسخة التطبيق. للقراءة فقط String.

--------------------

يجب أن يكون محتوى هذا العنصر على الصيغة XX.YYYY حيث تمثل X و Y قيمًا رقمية؛ وإلا سيُعتبر المستند غير متطابق. تمثل Aspose.Slides إصداره على الصيغة XX.YY.ZZ حيث: XX - الإصدار الرئيسي YY - الإصدار الفرعي ZZ - إصدار التصحيح. على سبيل المثال، القيمة 23.0105 تعني إصدار Aspose.Slides 23.1.5.

**الإرجاع:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

يعيد أو يضبط اسم التطبيق. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

يعيد أو يضبط اسم التطبيق. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

يعيد أو يضبط خاصية الشركة. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

يعيد أو يضبط خاصية الشركة. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

يعيد أو يضبط خاصية المدير. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

يعيد أو يضبط خاصية المدير. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

يعيد أو يضبط التنسيق المقصود للعرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

يعيد أو يضبط التنسيق المقصود للعرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. للقراءة والكتابة boolean.

**الإرجاع:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. للقراءة والكتابة boolean.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

يعيد أو يضبط قالب التطبيق. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

يعيد أو يضبط قالب التطبيق. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

إجمالي وقت تحرير العرض التقديمي. للقراءة والكتابة double.

**الإرجاع:**  
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

إجمالي وقت تحرير العرض التقديمي. للقراءة والكتابة double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

يعيد أو يضبط عنوان العرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

يعيد أو يضبط عنوان العرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

يعيد أو يضبط موضوع العرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

يعيد أو يضبط موضوع العرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

يعيد أو يضبط مؤلف العرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

يعيد أو يضبط مؤلف العرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

يعيد أو يضبط كلمات مفتاح العرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

يعيد أو يضبط كلمات مفتاح العرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

يعيد أو يضبط تعليقات العرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

يعيد أو يضبط تعليقات العرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

يعيد أو يضبط فئة العرض التقديمي. للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

يعيد أو يضبط فئة العرض التقديمي. للقراءة والكتابة String.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
| القيمة | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

يُعيد تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قراءة/كتابة java.util.Date.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

يُعيد تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قراءة/كتابة java.util.Date.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

يُعيد تاريخ تعديل العرض التقديمي آخر مرة. القيم بتوقيت UTC. قراءة فقط في حالة Presentation.DocumentProperties (لأنه سيُحدث داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties الذي تُرجعه الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). الرجاء الاطلاع على المثال في ملخص الطريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Returns:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

يُعيد تاريخ تعديل العرض التقديمي آخر مرة. القيم بتوقيت UTC. قراءة فقط في حالة Presentation.DocumentProperties (لأنه سيُحدث داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties الذي تُرجعه الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). الرجاء الاطلاع على المثال في ملخص الطريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

يُعيد تاريخ طباعة العرض التقديمي آخر مرة. قراءة/كتابة java.util.Date.

**Returns:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

يُعيد تاريخ طباعة العرض التقديمي آخر مرة. قراءة/كتابة java.util.Date.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

يُعيد أو يضبط اسم آخر شخص عدَّل العرض التقديمي. قراءة/كتابة String.

**Returns:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

يُعيد أو يضبط اسم آخر شخص عدَّل العرض التقديمي. قراءة/كتابة String.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

يُعيد أو يضبط رقم نسخة العرض التقديمي. قراءة/كتابة int.

**Returns:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

يُعيد أو يضبط رقم نسخة العرض التقديمي. قراءة/كتابة int.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

يُعيد أو يضبط حالة محتوى العرض التقديمي. قراءة/كتابة String.

**Returns:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

يُعيد أو يضبط حالة محتوى العرض التقديمي. قراءة/كتابة String.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

يُعيد أو يضبط نوع محتوى العرض التقديمي. قراءة/كتابة String.

**Returns:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

يُعيد أو يضبط نوع محتوى العرض التقديمي. قراءة/كتابة String.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

يُعيد أو يضبط خاصية وثيقة HyperlinkBase. قراءة/كتابة String.

**Returns:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

يُعيد أو يضبط خاصية وثيقة HyperlinkBase. قراءة/كتابة String.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

يشير إلى وضع عرض صورة مصغرة للوثيقة. اضبط هذا العنصر إلى **true** لتمكين تحجيم الصورة المصغرة للوثيقة إلى العرض. اضبطه إلى **false** لتمكين اقتصاص الصورة المصغرة لإظهار الأقسام التي تناسب العرض فقط. قراءة/كتابة boolean.

**Returns:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

يشير إلى وضع عرض صورة مصغرة للوثيقة. اضبط هذا العنصر إلى **true** لتمكين تحجيم الصورة المصغرة للوثيقة إلى العرض. اضبطه إلى **false** لتمكين اقتصاص الصورة المصغرة لإظهار الأقسام التي تناسب العرض فقط. قراءة/كتابة boolean.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

يشير إلى ما إذا كانت الروابط التشعبية في الوثيقة محدثة. اضبط هذا العنصر إلى **true** للدلالة على أن الروابط محدثة. اضبطه إلى **false** للدلالة على أن الروابط قديمة. قراءة/كتابة boolean.

**Returns:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

يشير إلى ما إذا كانت الروابط التشعبية في الوثيقة محدثة. اضبط هذا العنصر إلى **true** للدلالة على أن الروابط محدثة. اضبطه إلى **false** للدلالة على أن الروابط قديمة. قراءة/كتابة boolean.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

يحدد أن واحدة أو أكثر من الروابط التشعبية في هذا الجزء تم تحديثها حصرًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذه الوثيقة بتحديث علاقات الروابط التشعبية بالروابط الجديدة المحددة في هذا الجزء. قراءة/كتابة boolean.

**Returns:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

يحدد أن واحدة أو أكثر من الروابط التشعبية في هذا الجزء تم تحديثها حصرًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذه الوثيقة بتحديث علاقات الروابط التشعبية بالروابط الجديدة المحددة في هذا الجزء. قراءة/كتابة boolean.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

يحدد العدد الإجمالي للشرائح في وثيقة العرض التقديمي. قراءة فقط int.

**Returns:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

يحدد عدد الشرائح المخفية في وثيقة العرض التقديمي. قراءة فقط int.

**Returns:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

يحدد عدد الشرائح التي تحتوي على ملاحظات في العرض التقديمي. قراءة فقط int.

**Returns:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

يحدد العدد الإجمالي للفقرات الموجودة في الوثيقة إذا كان ذلك قابلًا للتطبيق. قراءة فقط int.

**Returns:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

يحدد العدد الإجمالي للكلمات المتضمنة في الوثيقة. قراءة فقط int.

**Returns:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

يحدد العدد الإجمالي للمقاطع الصوتية أو الفيديوية الموجودة في الوثيقة. قراءة فقط int.

**Returns:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

يحدد عنوان كل جزء من أجزاء الوثيقة. هذه الأجزاء ليست أجزاء وثيقة بل تمثيلات مفهومية لأقسام الوثيقة. قراءة فقط String[].

**Returns:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

يشير إلى تجميع أجزاء الوثيقة وعدد الأجزاء في كل مجموعة. قراءة فقط IHeadingPair[].

**Returns:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

يُعيد عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. قراءة فقط int.

**Returns:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

إرجاع اسم الخاصية المخصصة عند الفهرس المحدد.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخاصية المخصصة المطلوب الحصول عليها. |

**Returns:**
java.lang.String - اسم الخاصية المخصصة عند الفهرس المحدد.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

إزالة خاصية مخصصة مرتبطة بالاسم المحدد.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب إزالتها. |

**Returns:**
boolean - إرجاع true إذا تمت إزالة الخاصية، false otherwise.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

التحقق من وجود خاصية مخصصة بالاسم المحدد.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب التحقق منها. |

**Returns:**
boolean - إرجاع true إذا كانت الخاصية موجودة، false otherwise.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

إرجاع أو ضبط الخاصية المخصصة المرتبطة باسم محدد. قراءة/كتابة Object.

--------------------

القيمة يمكن أن تكون **int**, **float**, **double**, **String**, **boolean** أو **Date**.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

إرجاع أو ضبط الخاصية المخصصة المرتبطة باسم محدد. قراءة/كتابة Object.

--------------------

القيمة يمكن أن تكون **int**, **float**, **double**, **String**, **boolean** أو **Date**.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

يزيل جميع الخصائص المخصصة.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

يحصل على قيمة منطقية مسماة من الخصائص المخصصة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب الحصول عليها |
| value | boolean[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

يحصل على قيمة عددية صحيحة مسماة من الخصائص المخصصة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب الحصول عليها |
| value | int[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

يحصل على قيمة DateTime مسماة من الخصائص المخصصة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب الحصول عليها |
| value | java.util.Date[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

يحصل على قيمة نصية مسماة من الخصائص المخصصة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب الحصول عليها |
| value | java.lang.String[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

يحصل على قيمة فاصلة عائمة مسماة من الخصائص المخصصة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب الحصول عليها |
| value | float[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

يحصل على قيمة مزدوجة مسماة من الخصائص المخصصة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة التي يجب الحصول عليها |
| value | double[] | قيمة الخاصية المخصصة |
| الاسم | java.lang.String | اسم الخاصية المخصصة المراد الحصول عليها. |
| القيمة | double[] | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

يقوم بتعيين خاصية مخصصة من نوع boolean بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة لتعيينها |
| value | boolean | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

يقوم بتعيين خاصية مخصصة من نوع int بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة لتعيينها |
| value | int | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

يقوم بتعيين خاصية مخصصة من نوع DateTime بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة لتعيينها |
| value | java.util.Date | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

يقوم بتعيين خاصية مخصصة من نوع string بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة لتعيينها |
| value | java.lang.String | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

يقوم بتعيين خاصية مخصصة من نوع float بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة لتعيينها |
| value | float | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

يقوم بتعيين خاصية مخصصة من نوع double بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة لتعيينها |
| value | double | قيمة الخاصية المخصصة |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

يقوم بجلب مصفوفة من تصنيفات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
com.aspose.slides.ISensitivityLabel[]