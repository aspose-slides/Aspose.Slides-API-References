---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل خصائص عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

يمثل خصائص عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | يعيد إصدار التطبيق. |
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
| [getTotalEditingTime()](#getTotalEditingTime--) | إجمالي وقت التحرير للعرض التقديمي. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | إجمالي وقت التحرير للعرض التقديمي. |
| [getTitle()](#getTitle--) | يعيد أو يضبط عنوان العرض التقديمي. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يعيد أو يضبط عنوان العرض التقديمي. |
| [getSubject()](#getSubject--) | يعيد أو يضبط موضوع العرض التقديمي. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يعيد أو يضبط موضوع العرض التقديمي. |
| [getAuthor()](#getAuthor--) | يعيد أو يضبط مؤلف العرض التقديمي. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | يعيد أو يضبط مؤلف العرض التقديمي. |
| [getKeywords()](#getKeywords--) | يعيد أو يضبط الكلمات المفتاحية للعرض التقديمي. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | يعيد أو يضبط الكلمات المفتاحية للعرض التقديمي. |
| [getComments()](#getComments--) | يعيد أو يضبط التعليقات للعرض التقديمي. |
| [setComments(String value)](#setComments-java.lang.String-) | يعيد أو يضبط التعليقات للعرض التقديمي. |
| [getCategory()](#getCategory--) | يعيد أو يضبط الفئة للعرض التقديمي. |
| [setCategory(String value)](#setCategory-java.lang.String-) | يعيد أو يضبط الفئة للعرض التقديمي. |
| [getCreatedTime()](#getCreatedTime--) | يعيد تاريخ إنشاء العرض التقديمي. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | يعيد تاريخ إنشاء العرض التقديمي. |
| [getLastSavedTime()](#getLastSavedTime--) | يعيد تاريخ تعديل العرض التقديمي الأخير. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | يعيد تاريخ تعديل العرض التقديمي الأخير. |
| [getLastPrinted()](#getLastPrinted--) | يعيد تاريخ طباعة العرض التقديمي آخر مرة. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | يعيد تاريخ طباعة العرض التقديمي آخر مرة. |
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
| [getScaleCrop()](#getScaleCrop--) | يحدد وضع عرض صورة المصغرة للوثيقة. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | يحدد وضع عرض صورة المصغرة للوثيقة. |
| [getLinksUpToDate()](#getLinksUpToDate--) | يحدد ما إذا كانت الروابط التشعبية في الوثيقة محدثة. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | يحدد ما إذا كانت الروابط التشعبية في الوثيقة محدثة. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | يحدد أن أحد أو أكثر من الروابط التشعبية في هذا الجزء تم تحديثها حصريًا في هذا الجزء بواسطة منتج. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | يحدد أن أحد أو أكثر من الروابط التشعبية في هذا الجزء تم تحديثها حصريًا في هذا الجزء بواسطة منتج. |
| [getSlides()](#getSlides--) | يحدد إجمالي عدد الشرائح في وثيقة العرض التقديمي. |
| [getHiddenSlides()](#getHiddenSlides--) | يحدد عدد الشرائح المخفية في وثيقة العرض التقديمي. |
| [getNotes()](#getNotes--) | يحدد عدد الشرائح التي تحتوي على ملاحظات. |
| [getParagraphs()](#getParagraphs--) | يحدد إجمالي عدد الفقرات الموجودة في الوثيقة إن وجد. |
| [getWords()](#getWords--) | يحدد إجمالي عدد الكلمات الموجودة في الوثيقة. |
| [getMultimediaClips()](#getMultimediaClips--) | يحدد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في الوثيقة. |
| [getTitlesOfParts()](#getTitlesOfParts--) | يحدد عنوان كل جزء من أجزاء الوثيقة. |
| [getHeadingPairs()](#getHeadingPairs--) | يحدد تجميع أجزاء الوثيقة وعدد الأجزاء في كل مجموعة. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | يعيد عدد الخصائص المخصصة الموجودة فعليًا في مجموعة. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | يرجع اسم خاصية مخصصة عند الفهرس المحدد. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | يزيل خاصية مخصصة مرتبطة بالاسم المحدد. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | يعيد أو يضبط الخاصية المخصصة المرتبطة بالاسم المحدد. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يعيد أو يضبط الخاصية المخصصة المرتبطة بالاسم المحدد. |
| [clearCustomProperties()](#clearCustomProperties--) | يزيل جميع الخصائص المخصصة. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | يمسح ويُعين القيم الافتراضية لجميع الخصائص المدمجة. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | يحصل على قيمة منطقية مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | يحصل على قيمة عددية صحيحة مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | يحصل على قيمة تاريخية مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | يحصل على قيمة نصية مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | يحصل على قيمة عائمة مسماة من الخصائص المخصصة. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | يحصل على قيمة مزدوجة مسماة من الخصائص المخصصة. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | يضبط خاصية منطقية مخصصة مسماة. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | يضبط خاصية عددية صحيحة مخصصة مسماة. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | يضبط خاصية تاريخية مخصصة مسماة. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | يضبط خاصية نصية مخصصة مسماة. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | يضبط خاصية عائمة مخصصة مسماة. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | يضبط خاصية مزدوجة مخصصة مسماة. |
| [getSensitivityLabels()](#getSensitivityLabels--) | يحصل على مصفوفة من تسميات الحساسية من الخصائص المخصصة للوثيقة (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

يعيد إصدار التطبيق. للقراءة فقط String.

--------------------

محتوى هذا العنصر يجب أن يكون على الشكل XX.YYYY، حيث تمثل X و Y قيمًا رقمية؛ وإلا سيُ considered غير متطابق. Aspose.Slides يمثل إصداره بالشكل XX.YY.ZZ، حيث: XX - الإصدار الرئيسي YY - الإصدار الفرعي ZZ - إصدار التصحيح على سبيل المثال، القيمة 23.0105 تعني نسخة Aspose.Slides 23.1.5.

**الإرجاع:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

يعيد أو يضبط اسم التطبيق. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

يعيد أو يضبط اسم التطبيق. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

يعيد أو يضبط خاصية الشركة. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

يعيد أو يضبط خاصية الشركة. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

يعيد أو يضبط خاصية المدير. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

يعيد أو يضبط خاصية المدير. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

يعيد أو يضبط الصيغة المقصودة للعرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

يعيد أو يضبط الصيغة المقصودة للعرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

يعيد أو يضبط القالب لتطبيق. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

يعيد أو يضبط القالب لتطبيق. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

إجمالي وقت التحرير للعرض التقديمي. قابل للقراءة والكتابة double.

**الإرجاع:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

إجمالي وقت التحرير للعرض التقديمي. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

يعيد أو يضبط عنوان العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

يعيد أو يضبط عنوان العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

يعيد أو يضبط موضوع العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

يعيد أو يضبط موضوع العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

يعيد أو يضبط مؤلف العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

يعيد أو يضبط مؤلف العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

يعيد أو يضبط الكلمات المفتاحية للعرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

يعيد أو يضبط الكلمات المفتاحية للعرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

يعيد أو يضبط التعليقات للعرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

يعيد أو يضبط التعليقات للعرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

يعيد أو يضبط الفئة للعرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

يعيد أو يضبط الفئة للعرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

يعيد تاريخ إنشاء العرض التقديمي. القيم تُعطى بتوقيت UTC. قابل للقراءة والكتابة java.util.Date.

**الإرجاع:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

يعيد تاريخ إنشاء العرض التقديمي. القيم تُعطى بتوقيت UTC. قابل للقراءة والكتابة java.util.Date.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

يعيد تاريخ آخر تعديل للعرض التقديمي. القيم تُعطى بتوقيت UTC.P للقراءة فقط في حالة Presentation.DocumentProperties (لأنه يتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties المعاد بواسطة الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) يرجى مراجعة المثال في طريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**الإرجاع:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

يعيد تاريخ آخر تعديل للعرض التقديمي. القيم تُعطى بتوقيت UTC.P للقراءة فقط في حالة Presentation.DocumentProperties (لأنه يتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties المعاد بواسطة الطريقة [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) يرجى مراجعة المثال في طريقة [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

يعيد تاريخ آخر طباعة للعرض التقديمي. قابل للقراءة والكتابة java.util.Date.

**الإرجاع:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

يعيد تاريخ آخر طباعة للعرض التقديمي. قابل للقراءة والكتابة java.util.Date.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

يعيد أو يضبط اسم آخر شخص عدل العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

يعيد أو يضبط اسم آخر شخص عدل العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

يعيد أو يضبط رقم مراجعة العرض التقديمي. قابل للقراءة والكتابة int.

**الإرجاع:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

يعيد أو يضبط رقم مراجعة العرض التقديمي. قابل للقراءة والكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

يعيد أو يضبط حالة محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

يعيد أو يضبط حالة محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

يعيد أو يضبط نوع محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

يعيد أو يضبط نوع محتوى العرض التقديمي. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

يعيد أو يضبط خاصية HyperlinkBase للوثيقة. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

يعيد أو يضبط خاصية HyperlinkBase للوثيقة. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

يحدد وضع عرض صورة المصغرة للوثيقة. ضع هذا العنصر **true** لتمكين تعديل حجم صورة المصغرة لتناسب العرض. ضع هذا العنصر **false** لتمكين قص صورة المصغرة لإظهار الأقسام التي تناسب العرض فقط. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

يحدد وضع عرض صورة المصغرة للوثيقة. ضع هذا العنصر **true** لتمكين تعديل حجم صورة المصغرة لتناسب العرض. ضع هذا العنصر **false** لتمكين قص صورة المصغرة لإظهار الأقسام التي تناسب العرض فقط. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

يحدد ما إذا كانت الروابط التشعبية في الوثيقة محدثة. ضع هذا العنصر **true** للإشارة إلى أن الروابط محدثة. ضع هذا العنصر **false** للإشارة إلى أن الروابط قديمة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

يحدد ما إذا كانت الروابط التشعبية في الوثيقة محدثة. ضع هذا العنصر **true** للإشارة إلى أن الروابط محدثة. ضع هذا العنصر **false** للإشارة إلى أن الروابط قديمة. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

يحدد أن أحد أو أكثر من الروابط التشعبية في هذا الجزء تم تحديثها حصريًا في هذا الجزء بواسطة منتج. سيُحدِّث المنتج التالي الذي يفتح هذه الوثيقة علاقات الروابط بالتحديثات الجديدة المحددة في هذا الجزء. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

يحدد أن أحد أو أكثر من الروابط التشعبية في هذا الجزء تم تحديثها حصريًا في هذا الجزء بواسطة منتج. سيُحدِّث المنتج التالي الذي يفتح هذه الوثيقة علاقات الروابط بالتحديثات الجديدة المحددة في هذا الجزء. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

يحدد إجمالي عدد الشرائح في وثيقة العرض التقديمي. للقراءة فقط int.

**الإرجاع:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

يحدد عدد الشرائح المخفية في وثيقة العرض التقديمي. للقراءة فقط int.

**الإرجاع:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

يحدد عدد الشرائح التي تحتوي على ملاحظات. للقراءة فقط int.

**الإرجاع:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

يحدد إجمالي عدد الفقرات الموجودة في الوثيقة إن وجد. للقراءة فقط int.

**الإرجاع:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

يحدد إجمالي عدد الكلمات الموجودة في الوثيقة. للقراءة فقط int.

**الإرجاع:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

يحدد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في الوثيقة. للقراءة فقط int.

**الإرجاع:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

يحدد عنوان كل جزء من أجزاء الوثيقة. هذه الأجزاء ليست أجزاء فعلية من الوثيقة بل تمثيلات مفهومية لأقسام الوثيقة. للقراءة فقط String[].

**الإرجاع:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

يحدد تجميع أجزاء الوثيقة وعدد الأجزاء في كل مجموعة. للقراءة فقط IHeadingPair[].

**الإرجاع:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

يعيد عدد الخصائص المخصصة الموجودة فعليًا في مجموعة. للقراءة فقط int.

**الإرجاع:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

يرجع اسم خاصية مخصصة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخاصية المخصصة المراد الحصول عليها. |

**الإرجاع:**
java.lang.String - اسم الخاصية المخصصة عند الفهرس المحدد.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

يزيل خاصية مخصصة مرتبطة بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد إزالتها. |

**الإرجاع:**
boolean - إرجاع true إذا تمت إزالة الخاصية، false إذا لم يحدث ذلك.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

يتحقق من وجود خاصية مخصصة بالاسم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة للتحقق منها. |

**الإرجاع:**
boolean - إرجاع true إذا كانت الخاصية موجودة، false إذا لم تكن.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

يعيد أو يضبط الخاصية المخصصة المرتبطة بالاسم المحدد. قابل للقراءة والكتابة Object.

--------------------

القيمة يمكن أن تكون **int**, **float**, **double**, **String**, **boolean** أو **Date**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**الإرجاع:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

يعيد أو يضبط الخاصية المخصصة المرتبطة بالاسم المحدد. قابل للقراءة والكتابة Object.

--------------------

القيمة يمكن أن تكون **int**, **float**, **double**, **String**, **boolean** أو **Date**.

**المعاملات:**
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

يمسح ويُعين القيم الافتراضية لجميع الخصائص المدمجة.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

يحصل على قيمة منطقية مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المطلوب الحصول عليها |
| value | boolean[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

يحصل على قيمة عددية صحيحة مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المطلوب الحصول عليها |
| value | int[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

يحصل على قيمة تاريخية مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المطلوب الحصول عليها |
| value | java.util.Date[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

يحصل على قيمة نصية مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المطلوب الحصول عليها |
| value | java.lang.String[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

يحصل على قيمة عائمة مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المطلوب الحصول عليها |
| value | float[] | قيمة الخاصية المخصصة |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

يحصل على قيمة مزدوجة مسماة من الخصائص المخصصة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المطلوب الحصول عليها. |
| value | double[] | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

يضبط خاصية منطقية مخصصة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد ضبطها |
| value | boolean | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

يضبط خاصية عددية صحيحة مخصصة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد ضبطها |
| value | int | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

يضبط خاصية تاريخية مخصصة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد ضبطها |
| value | java.util.Date | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

يضبط خاصية نصية مخصصة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد ضبطها |
| value | java.lang.String | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

يضبط خاصية عائمة مخصصة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد ضبطها |
| value | float | قيمة الخاصية المخصصة |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

يضبط خاصية مزدوجة مخصصة مسماة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المخصصة المراد ضبطها |
| value | double | قيمة الخاصية المخصصة |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

يحصل على مصفوفة من تسميات الحساسية من الخصائص المخصصة للوثيقة (Microsoft Information Protection SDK Metadata).

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