---
title: DocumentProperties
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: خواص یک ارائه را نمایش می‌دهد.
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
>  // نمونه‌سازی کلاس Presentation که نمایانگر ارائه است
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // یک مرجع به شیء IDocumentProperties مرتبط با Presentation ایجاد کنید
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
>  // نمونه‌سازی کلاس Presentation که نمایانگر Presentation است
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // یک مرجع به شیء IDocumentProperties مرتبط با Presentation ایجاد کنید
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // تنظیم ویژگی‌های پیش‌فرض
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Save your presentation to a file
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | یک نمونه جدید از کلاس [DocumentProperties](../../com.aspose.slides/documentproperties) را مقداردهی می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | نسخه برنامه را برمی‌گرداند. |
| [getNameOfApplication()](#getNameOfApplication--) | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [getCompany()](#getCompany--) | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. |
| [setCompany(String value)](#setCompany-java.lang.String-) | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. |
| [getManager()](#getManager--) | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. |
| [setManager(String value)](#setManager-java.lang.String-) | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. |
| [getPresentationFormat()](#getPresentationFormat--) | قالب پیش‌نقش‌شده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | قالب پیش‌نقش‌شده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getSharedDoc()](#getSharedDoc--) | تعیین می‌کند که آیا ارائه بین چند نفر به‌اشتراک گذاشته شده است یا نه. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | تعیین می‌کند که آیا ارائه بین چند نفر به‌اشتراک گذاشته شده است یا نه. |
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
| [getKeywords()](#getKeywords--) | کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
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
| [getLastSavedBy()](#getLastSavedBy--) | نام آخرین شخصی که یک ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | نام آخرین شخصی که یک ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getRevisionNumber()](#getRevisionNumber--) | عدد نسخه تجدید ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | عدد نسخه تجدید ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getContentStatus()](#getContentStatus--) | وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getContentType()](#getContentType--) | نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setContentType(String value)](#setContentType-java.lang.String-) | نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkBase()](#getHyperlinkBase--) | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | تعداد ویژگی‌های سفارشی واقعاً موجود در یک مجموعه را برمی‌گرداند. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | نام یک ویژگی سفارشی را در ایندکس مشخص برمی‌گرداند. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | یک ویژگی سفارشی بولی با نام خاص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | یک ویژگی سفارشی عددی با نام خاص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | یک ویژگی سفارشی DateTime با نام خاص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | یک ویژگی سفارشی رشته‌ای با نام خاص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | یک ویژگی سفارشی float با نام خاص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | یک ویژگی سفارشی double با نام خاص را تنظیم می‌کند. |
| [clearCustomProperties()](#clearCustomProperties--) | تمام ویژگی‌های سفارشی را حذف می‌کند. |
| [getSensitivityLabels()](#getSensitivityLabels--) | یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | تمام ویژگی‌های builtIn را پاک کرده و مقادیر پیش‌فرض را تنظیم می‌کند. |
| [getScaleCrop()](#getScaleCrop--) | حالت نمایش بندانگشتی سند را نشان می‌دهد. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | حالت نمایش بندانگشتی سند را نشان می‌دهد. |
| [getLinksUpToDate()](#getLinksUpToDate--) | نشان می‌دهد آیا پیوندهای‌هایپر در سند به‌روز هستند یا نه. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | نشان می‌دهد آیا پیوندهای‌هایپر در سند به‌روز هستند یا نه. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | مشخص می‌کند که یک یا چند پیوندهای‌هایپر در این بخش به‌صورت اختصاصی توسط یک تولیدکننده به‌روزرسانی شده‌اند. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | مشخص می‌کند که یک یا چند پیوندهای‌هایپر در این بخش به‌صورت اختصاصی توسط یک تولیدکننده به‌روزرسانی شده‌اند. |
| [getSlides()](#getSlides--) | تعداد کل اسلایدهای موجود در سند ارائه را برمی‌گرداند. |
| [getHiddenSlides()](#getHiddenSlides--) | تعداد اسلایدهای مخفی در سند ارائه را برمی‌گرداند. |
| [getNotes()](#getNotes--) | تعداد اسلایدهایی که در ارائه حاوی یادداشت هستند را برمی‌گرداند. |
| [getParagraphs()](#getParagraphs--) | تعداد کل پاراگراف‌های موجود در سند (در صورت امکان) را برمی‌گرداند. |
| [getWords()](#getWords--) | تعداد کل واژگان موجود در سند را برمی‌گرداند. |
| [getMultimediaClips()](#getMultimediaClips--) | تعداد کل کلیپ‌های صوتی یا تصویری موجود در سند را برمی‌گرداند. |
| [getTitlesOfParts()](#getTitlesOfParts--) | عنوان هر بخش از سند را مشخص می‌کند. |
| [getHeadingPairs()](#getHeadingPairs--) | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. |
| [deepClone()](#deepClone--) | شیء جاری را کپی می‌کند |
| [cloneT()](#cloneT--) | شیء جاری را کپی می‌کند |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

یک نمونه جدید از کلاس [DocumentProperties](../../com.aspose.slides/documentproperties) را مقداردهی می‌کند.

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

نسخه برنامه را برمی‌گرداند. رشته فقط خواندنی.

**باز می‌گردد:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

نام برنامه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

نام برنامه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

قالب پیش‌نقش‌شده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

قالب پیش‌نقش‌شده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

تعیین می‌کند که آیا ارائه بین چند نفر به‌اشتراک گذاشته شده است یا نه. بولین قابل خواندن/نوشتن.

**باز می‌گردد:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

تعیین می‌کند که آیا ارائه بین چند نفر به‌اشتراک گذاشته شده است یا نه. بولین قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

کل زمان ویرایش یک ارائه. double قابل خواندن/نوشتن.

**باز می‌گردد:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

کل زمان ویرایش یک ارائه. double قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. java.util.Date قابل خواندن/نوشتن.

**باز می‌گردد:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. java.util.Date قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

تاریخ آخرین اصلاح یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط خواندنی در مورد Presentation.DocumentProperties (زیرا در حین ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونه DocumentProperties بازگردانده شده توسط متد [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) تغییر یابد. لطفاً مثال در خلاصهٔ متد [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) را ببینید.

**باز می‌گردد:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

تاریخ آخرین اصلاح یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط خواندنی در مورد Presentation.DocumentProperties (زیرا در حین ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونه DocumentProperties بازگردانده شده توسط متد [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) تغییر یابد. لطفاً مثال در خلاصهٔ متد [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) را ببینید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. java.util.Date قابل خواندن/نوشتن.

**باز می‌گردد:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. java.util.Date قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

نام آخرین شخصی که یک ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

نام آخرین شخصی که یک ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

عدد نسخه تجدید ارائه را برمی‌گرداند یا تنظیم می‌کند. int قابل خواندن/نوشتن.

**باز می‌گردد:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

عدد نسخه تجدید ارائه را برمی‌گرداند یا تنظیم می‌کند. int قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public      (**\* Comments are removed**)
```

وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**باز می‌گردد:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. رشته قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

تعداد ویژگی‌های سفارشی واقعاً موجود در یک مجموعه را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

نام یک ویژگی سفارشی را در ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-محور ویژگی سفارشی مورد نظر |

**باز می‌گردد:**
java.lang.String - نام ویژگی سفارشی در ایندکس مشخص.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای حذف |

**باز می‌گردد:**
boolean - در صورتی که ویژگی حذف شود true برگردانده می‌شود، در غیر این صورت false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای بررسی |

**باز می‌گردد:**
boolean - در صورتی که ویژگی موجود باشد true برگردانده می‌شود، در غیر این صورت false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. Object قابل خواندن/نوشتن.

--------------------

مقدار می‌تواند **int**، **float**، **String**، **boolean** یا **Date** باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String |  |

**باز می‌گردد:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. Object قابل خواندن/نوشتن.

--------------------

مقدار می‌تواند **int**، **float**، **String**، **boolean** یا **Date** باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

یک مقدار بولی نام‌گذاری‌شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | boolean[] | مقدار ویژگی سفارشی |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

یک مقدار عددی نام‌گذاری‌شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | int[] | مقدار ویژگی سفارشی |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

یک مقدار DateTime نام‌گذاری‌شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | java.util.Date[] | مقدار ویژگی سفارشی |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

یک مقدار رشته‌ای نام‌گذاری‌شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | java.lang.String[] | مقدار ویژگی سفارشی |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

یک مقدار float نام‌گذاری‌شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | float[] | مقدار ویژگی سفارشی |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

یک مقدار double نام‌گذاری‌شده را از ویژگی‌های سفارشی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | double[] | مقدار ویژگی سفارشی |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

یک ویژگی سفارشی بولی با نام خاص را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | boolean | مقدار ویژگی سفارشی |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

یک ویژگی سفارشی عددی با نام خاص را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | int | مقدار ویژگی سفارشی |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

یک ویژگی سفارشی DateTime با نام خاص را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | java.util.Date | مقدار ویژگی سفارشی |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

یک ویژگی سفارشی رشته‌ای با نام خاص را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | java.lang.String | مقدار ویژگی سفارشی |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

یک ویژگی سفارشی float با نام خاص را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | float | مقدار ویژگی سفارشی |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

یک ویژگی سفارشی double با نام خاص را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
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
>          // در اینجا می‌توانید بررسی صحت اطلاعات برچسب (در دسترس بودن برچسب و غیره) را اضافه کنید
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گردد:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public  (** ** ** ** ** ** ** ** ** ** **)
```

تمام ویژگی‌های builtIn را پاک کرده و مقادیر پیش‌فرض را تنظیم می‌کند.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

حالت نمایش بندانگشتی سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌بندی بندانگشت به **true** تنظیم کنید. برای فعال‌سازی برش بندانگشتی به **false** تنظیم کنید. بولین قابل خواندن/نوشتن.

**باز می‌گردد:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

حالت نمایش بندانگشتی سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌بندی بندانگشت به **true** تنظیم کنید. برای فعال‌سازی برش بندانگشتی به **false** تنظیم کنید. بولین قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

نشان می‌دهد آیا پیوندهای‌هایپر در سند به‌روز هستند یا نه. برای نشان دادن بروز بودن به **true** تنظیم کنید. برای نشان دادن که پیوندها منقضی شده‌اند به **false** تنظیم کنید. بولین قابل خواندن/نوشتن.

**باز می‌گردد:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

نشان می‌دهد آیا پیوندهای‌هایپر در سند به‌روز هستند یا نه. برای نشان دادن بروز بودن به **true** تنظیم کنید. برای نشان دادن که پیوندها منقضی شده‌اند به **false** تنظیم کنید. بولین قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

مشخص می‌کند که یک یا چند پیوندهای‌هایپر در این بخش به‌صورت اختصاصی توسط یک تولیدکننده به‌روزرسانی شده‌اند. تولیدکنندهٔ بعدی که این سند را باز کند باید روابط پیوندهای‌هایپر را با پیوندهای جدید موجود در این بخش به‌روزرسانی کند. بولین قابل خواندن/نوشتن.

**باز می‌گردد:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

مشخص می‌کند که یک یا چند پیوندهای‌هایپر در این بخش به‌صورت اختصاصی توسط یک تولیدکننده به‌روزرسانی شده‌اند. تولیدکنندهٔ بعدی که این سند را باز کند باید روابط پیوندهای‌هایپر را با پیوندهای جدید موجود در این بخش به‌روزرسانی کند. بولین قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

تعداد کل اسلایدهای موجود در سند ارائه را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

تعداد اسلایدهای مخفی در سند ارائه را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

تعداد اسلایدهایی که در ارائه حاوی یادداشت هستند را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getNotes()
```

تعداد کل پاراگراف‌های موجود در سند (در صورت امکان) را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

تعداد کل واژگان موجود در سند را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

تعداد کل کلیپ‌های صوتی یا تصویری موجود در سند را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

عنوان هر بخش از سند را مشخص می‌کند. این بخش‌ها نمایهٔ مفهومی از بخش‌های سند هستند، نه بخش‌های واقعی سند. String[] فقط خواندنی.

**باز می‌گردد:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. IHeadingPair[] فقط خواندنی.

**باز می‌گردد:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

شیء جاری را کپی می‌کند

**باز می‌گردد:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

شیء جاری را کپی می‌کند

**باز می‌گردد:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone