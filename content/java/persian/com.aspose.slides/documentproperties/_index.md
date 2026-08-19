---
title: DocumentProperties
second_title: مرجع API Aspose.Slides برای Java
description: ویژگی‌های یک ارائه را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/documentproperties/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable  
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

خواص یک ارائه را نمایش می‌دهد.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // نمونه‌سازی کلاس Presentation که نشان‌دهندهٔ ارائه است
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // ایجاد یک ارجاع به شیء IDocumentProperties مرتبط با Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // نمایش ویژگی‌های پیش‌فرض
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
>  // نمونه‌سازی کلاس Presentation که نشان‌دهندهٔ Presentation است
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // ایجاد یک ارجاع به شیء IDocumentProperties مرتبط با Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // تنظیم ویژگی‌های پیش‌فرض
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // ذخیرهٔ ارائه شما در یک فایل
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | یک نمونهٔ جدید از کلاس [DocumentProperties](../../com.aspose.slides/documentproperties) را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | نسخهٔ برنامه را برمی‌گرداند. |
| [getNameOfApplication()](#getNameOfApplication--) | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [getCompany()](#getCompany--) | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. |
| [setCompany(String value)](#setCompany-java.lang.String-) | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. |
| [getManager()](#getManager--) | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. |
| [setManager(String value)](#setManager-java.lang.String-) | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. |
| [getPresentationFormat()](#getPresentationFormat--) | قالب موردنظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | قالب موردنظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getSharedDoc()](#getSharedDoc--) | تعیین می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | تعیین می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. |
| [getApplicationTemplate()](#getApplicationTemplate--) | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [getTotalEditingTime()](#getTotalEditingTime--) | کل زمان ویرایش یک ارائه. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | کل زمان ویرایش یک ارائه. |
| [getTitle()](#getTitle--) | عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setTitle(String value)](#setTitle-java.lang.String-) | عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getSubject()](#getSubject--) | موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setSubject(String value)](#setSubject-java.lang.String-) | موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getAuthor()](#getAuthor--) | نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getKeywords()](#getKeywords--) | کلمات کلیدی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | کلمات کلیدی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getComments()](#getComments--) | نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setComments(String value)](#setComments-java.lang.String-) | نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getCategory()](#getCategory--) | دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setCategory(String value)](#setCategory-java.lang.String-) | دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getCreatedTime()](#getCreatedTime--) | تاریخ ایجاد یک ارائه را برمی‌گرداند. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | تاریخ ایجاد یک ارائه را برمی‌گرداند. |
| [getLastSavedTime()](#getLastSavedTime--) | تاریخ آخرین اصلاح یک ارائه را برمی‌گرداند. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | تاریخ آخرین اصلاح یک ارائه را برمی‌گرداند. |
| [getLastPrinted()](#getLastPrinted--) | تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. |
| [getLastSavedBy()](#getLastSavedBy--) | نام آخرین شخصی که ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | نام آخرین شخصی که ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getRevisionNumber()](#getRevisionNumber--) | شماره بازبینی ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | شماره بازبینی ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getContentStatus()](#getContentStatus--) | وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getContentType()](#getContentType--) | نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setContentType(String value)](#setContentType-java.lang.String-) | نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkBase()](#getHyperlinkBase--) | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | تعداد ویژگی‌های سفارشی موجود در یک مجموعه را برمی‌گرداند. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | نام یک ویژگی سفارشی را در شاخص مشخص شده برمی‌گرداند. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | یک ویژگی سفارشی مرتبط با نام مشخص شده را حذف می‌کند. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | وجود یک ویژگی سفارشی با نام مشخص شده را بررسی می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی سفارشی مرتبط با نام مشخص شده را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | ویژگی سفارشی مرتبط با نام مشخص شده را برمی‌گرداند یا تنظیم می‌کند. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | یک ویژگی سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | یک ویژگی سفارشی عدد صحیح با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | یک ویژگی سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | یک ویژگی سفارشی رشته‌ای با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | یک ویژگی سفارشی شناور با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | یک ویژگی سفارشی دوگانه با نام مشخص را تنظیم می‌کند. |
| [clearCustomProperties()](#clearCustomProperties--) | تمام ویژگی‌های سفارشی را حذف می‌کند. |
| [getSensitivityLabels()](#getSensitivityLabels--) | یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | تمام ویژگی‌های پیش‌ساخته را پاک‌سازی و مقادیر پیش‌فرض را تنظیم می‌کند. |
| [getScaleCrop()](#getScaleCrop--) | حالت نمایش تصویر بندانگشتی سند را نشان می‌دهد. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | حالت نمایش تصویر بندانگشتی سند را نشان می‌دهد. |
| [getLinksUpToDate()](#getLinksUpToDate--) | نشان می‌دهد آیا پیوندهای موجود در سند به‌روز هستند یا نه. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | نشان می‌دهد آیا پیوندهای موجود در سند به‌روز هستند یا نه. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | مشخص می‌کند که یک یا چند پیوند در این بخش به‌صورت اختصاصی توسط تولیدکننده به‌روز شده‌اند. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | مشخص می‌کند که یک یا چند پیوند در این بخش به‌صورت اختصاصی توسط تولیدکننده به‌روز شده‌اند. |
| [getSlides()](#getSlides--) | تعداد کل اسلایدهای یک سند ارائه را برمی‌گرداند. |
| [getHiddenSlides()](#getHiddenSlides--) | تعداد اسلایدهای پنهان در یک سند ارائه را برمی‌گرداند. |
| [getNotes()](#getNotes--) | تعداد اسلایدهای حاوی یادداشت در یک ارائه را برمی‌گرداند. |
| [getParagraphs()](#getParagraphs--) | تعداد کل پاراگراف‌های موجود در سند را (در صورت وجود) برمی‌گرداند. |
| [getWords()](#getWords--) | تعداد کل کلمات موجود در سند را برمی‌گرداند. |
| [getMultimediaClips()](#getMultimediaClips--) | تعداد کل کلیپ‌های صوتی یا ویدیویی موجود در سند را برمی‌گرداند. |
| [getTitlesOfParts()](#getTitlesOfParts--) | عنوان هر بخش سند را مشخص می‌کند. |
| [getHeadingPairs()](#getHeadingPairs--) | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. |
| [deepClone()](#deepClone--) | شی جاری را کلون می‌کند. |
| [cloneT()](#cloneT--) | شی جاری را کلون می‌کند. |

### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

یک نمونهٔ جدید از کلاس [DocumentProperties](../../com.aspose.slides/documentproperties) را مقداردهی اولیه می‌کند.

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

نسخهٔ برنامه را برمی‌گرداند. String فقط‌خواندنی.

**بازگشت:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

نام برنامه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

نام برنامه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

قالب موردنظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

قالب موردنظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

تعیین می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. boolean قابل خواندن و نوشتن.

**بازگشت:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

تعیین می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. boolean قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

کل زمان ویرایش یک ارائه. double قابل خواندن و نوشتن.

**بازگشت:**  
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

کل زمان ویرایش یک ارائه. double قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

کلمات کلیدی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

کلمات کلیدی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**بازگشت:**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. String قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر در زمان UTC هستند. قابل خواندن/نوشتن java.util.Date.

**بازگرداندن:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر در زمان UTC هستند. قابل خواندن/نوشتن java.util.Date.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر در زمان UTC هستند. فقط-خواندنی در مورد Presentation.DocumentProperties (زیرا در فرآیند ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روزرسانی می‌شود). می‌تواند از طریق نمونه DocumentProperties بازگردانده‌شده توسط روش [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) تغییر یابد. لطفاً مثال در خلاصه روش [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) را ببینید.

**بازگرداندن:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر در زمان UTC هستند. فقط-خواندنی در مورد Presentation.DocumentProperties (زیرا در فرآیند ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روزرسانی می‌شود). می‌تواند از طریق نمونه DocumentProperties بازگردانده‌شده توسط روش [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) تغییر یابد. لطفاً مثال در خلاصه روش [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) را ببینید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. قابل خواندن/نوشتن java.util.Date.

**بازگرداندن:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. قابل خواندن/نوشتن java.util.Date.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگرداندن:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

شماره بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازگرداندن:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

شماره بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگرداندن:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگرداندن:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

خصوصیت HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگرداندن:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

خصوصیت HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

تعداد ویژگی‌های سفارشی واقعاً موجود در یک مجموعه را برمی‌گرداند. فقط-خواندنی int.

**بازگرداندن:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

نام یک ویژگی سفارشی را در ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس صفر-محور یک ویژگی سفارشی برای دریافت. |

**بازگرداندن:**
java.lang.String - نام ویژگی سفارشی در ایندکس مشخص.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای حذف. |

**بازگرداندن:**
boolean - اگر ویژگی حذف شد true برمی‌گردد، در غیر این صورت false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای بررسی. |

**بازگرداندن:**
boolean - اگر ویژگی وجود داشته باشد true برمی‌گردد، در غیر این صورت false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Object.

--------------------

مقدار می‌تواند **int**، **float**، **String**، **boolean** یا **Date** باشد.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**بازگرداندن:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Object.

--------------------

مقدار می‌تواند **int**، **float**، **String**، **boolean** یا **Date** باشد.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

یک مقدار بولی نام‌برده شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | boolean[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

یک مقدار عددی نام‌برده شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | int[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

یک مقدار DateTime نام‌برده شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | java.util.Date[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

یک مقدار رشته‌ای نام‌برده شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | java.lang.String[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

یک مقدار شناور (float) نام‌برده شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | float[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

یک مقدار دوچندان (double) نام‌برده شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت. |
| value | double[] | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

یک ویژگی سفارشی بولی نام‌برده را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | boolean | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

یک ویژگی سفارشی عددی نام‌برده را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | int | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

یک ویژگی سفارشی DateTime نام‌برده را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | java.util.Date | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

یک ویژگی سفارشی رشته‌ای نام‌برده را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | java.lang.String | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

یک ویژگی سفارشی شناور (float) نام‌برده را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | float | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

یک ویژگی سفارشی دوچندان (double) نام‌برده را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | double | مقدار ویژگی سفارشی |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

تمام ویژگی‌های سفارشی را حذف می‌کند.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // دریافت برچسب‌های حساسیت از ویژگی‌های سفارشی سند
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // افزودن برچسب به مجموعه
>          // در اینجا می‌توانید یک بررسی برای اعتبار اطلاعات برچسب اضافه کنید (برچسب موجود است و غیره)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

تمام ویژگی‌های داخلی را پاک‌سازی و مقادیر پیش‌فرض برای آن‌ها تنظیم می‌کند.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

حالت نمایش تصویر بندانگشتی سند را نشان می‌دهد. این عنصر را به **true** تنظیم کنید تا مقیاس‌گذاری تصویر بندانگشتی به نمایشگر فعال شود. این عنصر را به **false** تنظیم کنید تا برش تصویر بندانگشتی به‌طوری که فقط بخش‌های متناسب با نمایشگر نشان داده شوند، فعال شود. قابل خواندن/نوشتن boolean.

**بازگرداندن:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

حالت نمایش تصویر بندانگشتی سند را نشان می‌دهد. این عنصر را به **true** تنظیم کنید تا مقیاس‌گذاری تصویر بندانگشتی به نمایشگر فعال شود. این عنصر را به **false** تنظیم کنید تا برش تصویر بندانگشتی به‌طوری که فقط بخش‌های متناسب با نمایشگر نشان داده شوند، فعال شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

نشان می‌دهد که پیوندهای فراگیر در یک سند به‌روز هستند یا خیر. این عنصر را به **true** تنظیم کنید تا نشان دهد پیوندها به‌روز شده‌اند. این عنصر را به **false** تنظیم کنید تا نشان دهد پیوندها تاریخ گذشته‌اند. قابل خواندن/نوشتن boolean.

**بازگرداندن:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. قابل خواندن/نوشتن boolean.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

مشخص می‌کند که یک یا چند پیوند فراخورده در این بخش منحصراً توسط یک تولیدکننده به‌روزرسانی شده‌اند. تولیدکننده بعدی که این سند را باز می‌کند باید روابط پیوندهای فراخورده را با پیوندهای جدید مشخص‌شده در این بخش به‌روزرسانی کند. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

مشخص می‌کند که یک یا چند پیوند فراخورده در این بخش منحصراً توسط یک تولیدکننده به‌روزرسانی شده‌اند. تولیدکننده بعدی که این سند را باز می‌کند باید روابط پیوندهای فراخورده را با پیوندهای جدید مشخص‌شده در این بخش به‌روزرسانی کند. قابل خواندن/نوشتن boolean.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

تعداد کل اسلایدهای موجود در یک سند ارائه را برمی‌گرداند. قابل خواندن فقط int.

**بازگشت:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

تعداد اسلایدهای پنهان موجود در یک سند ارائه را برمی‌گرداند. قابل خواندن فقط int.

**بازگشت:**
int

### getNotes() {#getNotes--}
```
public final int getNotes()
```

تعداد اسلایدهایی که در یک ارائه شامل یادداشت هستند را برمی‌گرداند. قابل خواندن فقط int.

**بازگشت:**
int

### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

در صورت امکان، کل تعداد پاراگراف‌های یافت‌شده در یک سند را برمی‌گرداند. قابل خواندن فقط int.

**بازگشت:**
int

### getWords() {#getWords--}
```
public final int getWords()
```

کل تعداد کلمات موجود در یک سند را برمی‌گرداند. قابل خواندن فقط int.

**بازگشت:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

کل تعداد کلیپ‌های صوتی یا ویدئویی موجود در سند را برمی‌گرداند. قابل خواندن فقط int.

**بازگشت:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

عنوان هر بخش از سند را مشخص می‌کند. این بخش‌ها بخش‌های سند نیستند بلکه نمایش‌های مفهومی از بخش‌های سند هستند. قابل خواندن فقط String[].

**بازگشت:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. قابل خواندن فقط IHeadingPair[].

**بازگشت:**
com.aspose.slides.IHeadingPair[]

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

شیء فعلی را کلون می‌کند

**بازگشت:**
java.lang.Object - Clone

### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

شیء فعلی را کلون می‌کند

**بازگشت:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone