---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: نمایندهٔ ویژگی‌های یک ارائه.
type: docs
url: /fa/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

نمایندهٔ ویژگی‌های یک ارائه.
## متدها

| Method | Description |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | نسخهٔ برنامه را برمی‌گرداند. |
| [getNameOfApplication()](#getNameOfApplication--) | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [getCompany()](#getCompany--) | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. |
| [setCompany(String value)](#setCompany-java.lang.String-) | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. |
| [getManager()](#getManager--) | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. |
| [setManager(String value)](#setManager-java.lang.String-) | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. |
| [getPresentationFormat()](#getPresentationFormat--) | قالب مورد نظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | قالب مورد نظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getSharedDoc()](#getSharedDoc--) | تعیین می‌کند که آیا ارائه بین چند نفر به اشتراک گذاشته شده است یا خیر. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | تعیین می‌کند که آیا ارائه بین چند نفر به اشتراک گذاشته شده است یا خیر. |
| [getApplicationTemplate()](#getApplicationTemplate--) | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. |
| [getTotalEditingTime()](#getTotalEditingTime--) | زمان کل ویرایش یک ارائه. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | زمان کل ویرایش یک ارائه. |
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
| [getLastSavedTime()](#getLastSavedTime--) | تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. |
| [getLastPrinted()](#getLastPrinted--) | تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. |
| [getLastSavedBy()](#getLastSavedBy--) | نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getRevisionNumber()](#getRevisionNumber--) | شماره بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | شماره بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getContentStatus()](#getContentStatus--) | وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getContentType()](#getContentType--) | نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setContentType(String value)](#setContentType-java.lang.String-) | نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkBase()](#getHyperlinkBase--) | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. |
| [getScaleCrop()](#getScaleCrop--) | حالت نمایش تصویر بندانگشت سند را نشان می‌دهد. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | حالت نمایش تصویر بندانگشت سند را نشان می‌دهد. |
| [getLinksUpToDate()](#getLinksUpToDate--) | نشان می‌دهد که آیا پیوندهای فراخوانی در سند به‌روز هستند یا خیر. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | نشان می‌دهد که آیا پیوندهای فراخوانی در سند به‌روز هستند یا خیر. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | مشخص می‌کند که یک یا چند پیوند فراخوانی در این بخش به‌صورت انحصاری توسط تولید کننده به‌روز شده‌اند. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | مشخص می‌کند که یک یا چند پیوند فراخوانی در این بخش به‌صورت انحصاری توسط تولید کننده به‌روز شده‌اند. |
| [getSlides()](#getSlides--) | تعداد کل اسلایدهای سند ارائه را مشخص می‌کند. |
| [getHiddenSlides()](#getHiddenSlides--) | تعداد اسلایدهای مخفی در سند ارائه را مشخص می‌کند. |
| [getNotes()](#getNotes--) | تعداد اسلایدهایی که در ارائه حاوی یادداشت هستند را مشخص می‌کند. |
| [getParagraphs()](#getParagraphs--) | تعداد کل پاراگراف‌های موجود در سند (در صورت قابل اعمال) را مشخص می‌کند. |
| [getWords()](#getWords--) | تعداد کل کلمات موجود در سند را مشخص می‌کند. |
| [getMultimediaClips()](#getMultimediaClips--) | تعداد کل کلیپ‌های صوتی یا ویدیویی موجود در سند را مشخص می‌کند. |
| [getTitlesOfParts()](#getTitlesOfParts--) | عنوان هر بخش سند را مشخص می‌کند. |
| [getHeadingPairs()](#getHeadingPairs--) | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | تعداد ویژگی‌های سفارشی موجود در مجموعه را برمی‌گرداند. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | نام ویژگی سفارشی در ایندکس مشخص را برمی‌گرداند. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. |
| [clearCustomProperties()](#clearCustomProperties--) | تمام ویژگی‌های سفارشی را حذف می‌کند. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | تمام ویژگی‌های پیش‌ساخته را پاک می‌کند و مقادیر پیش‌فرض را تنظیم می‌کند. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | مقدار بولی با نام مشخص را از ویژگی‌های سفارشی می‌گیرد. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | مقدار صحیح با نام مشخص را از ویژگی‌های سفارشی می‌گیرد. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | مقدار DateTime با نام مشخص را از ویژگی‌های سفارشی می‌گیرد. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | مقدار رشته‌ای با نام مشخص را از ویژگی‌های سفارشی می‌گیرد. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | مقدار شناور با نام مشخص را از ویژگی‌های سفارشی می‌گیرد. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | مقدار دوگانه با نام مشخص را از ویژگی‌های سفارشی می‌گیرد. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | یک ویژگی سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | یک ویژگی سفارشی صحیح با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | یک ویژگی سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | یک ویژگی سفارشی رشته‌ای با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | یک ویژگی سفارشی شناور با نام مشخص را تنظیم می‌کند. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | یک ویژگی سفارشی دوگانه با نام مشخص را تنظیم می‌کند. |
| [getSensitivityLabels()](#getSensitivityLabels--) | آرایه‌ای از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند می‌گیرد (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

نسخهٔ برنامه را برمی‌گرداند. فقط خواندنی String.

--------------------

محتویات این عنصر باید به فرم XX.YYYY باشد که X و Y مقادیر عددی هستند؛ در غیر اینصورت سند به‌عنوان غیر‌سازگار در نظر گرفته می‌شود. Aspose.Slides نسخهٔ خود را به فرم XX.YY.ZZ نشان می‌دهد که: XX - نسخهٔ اصلی YY - نسخهٔ جزئی ZZ - نسخهٔ اصلاحی. به‌عنوان مثال مقدار 23.0105 به‌معنی Aspose.Slides نسخهٔ 23.1.5 است.

**Returns:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

نام برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

نام برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

قالب مورد نظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

قالب مورد نظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

تعیین می‌کند که آیا ارائه بین چند نفر به اشتراک گذاشته شده است یا خیر. قابل خواندن/نوشتن boolean.

**Returns:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

تعیین می‌کند که آیا ارائه بین چند نفر به اشتراک گذاشته شده است یا خیر. قابل خواندن/نوشتن boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

زمان کل ویرایش یک ارائه. قابل خواندن/نوشتن double.

**Returns:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

زمان کل ویرایش یک ارائه. قابل خواندن/نوشتن double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

نویسنده یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. قابل خواندن/نوشتن java.util.Date.

**Returns:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. قابل خواندن/نوشتن java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط خواندنی در حالت Presentation.DocumentProperties (به‌دلیل به‌روزرسانی داخلی هنگام ذخیره‌سازی شیء IPresentation). می‌تواند از طریق نمونه DocumentProperties که توسط روش [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) برگردانده می‌شود تغییر یابد. لطفاً مثال در خلاصهٔ روش [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) را ببینید.

**Returns:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط خواندنی در حالت Presentation.DocumentProperties (به‌دلیل به‌روزرسانی داخلی هنگام ذخیره‌سازی شیء IPresentation). می‌تواند از طریق نمونه DocumentProperties که توسط روش [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) برگردانده می‌شود تغییر یابد. لطفاً مثال در خلاصهٔ روش [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) را ببینید.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. قابل خواندن/نوشتن java.util.Date.

**Returns:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. قابل خواندن/نوشتن java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

شماره بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**Returns:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

شماره بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

حالت نمایش تصویر بندانگشت سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌بندی تصویر بندانگشت به **true** تنظیم کنید. برای فعال‌سازی برش تصویر بندانگشت به **false** تنظیم کنید. قابل خواندن/نوشتن boolean.

**Returns:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

حالت نمایش تصویر بندانگشت سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌بندی تصویر بندانگشت به **true** تنظیم کنید. برای فعال‌سازی برش تصویر بندانگشت به **false** تنظیم کنید. قابل خواندن/نوشتن boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

نشان می‌دهد که آیا پیوندهای فراخوانی در سند به‌روز هستند یا خیر. برای نشان دادن به‌روزرسانی پیوندها به **true** تنظیم کنید. برای نشان دادن که پیوندها قدیمی‌اند به **false** تنظیم کنید. قابل خواندن/نوشتن boolean.

**Returns:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

نشان می‌دهد که آیا پیوندهای فراخوانی در سند به‌روز هستند یا خیر. برای نشان دادن به‌روزرسانی پیوندها به **true** تنظیم کنید. برای نشان دادن که پیوندها قدیمی‌اند به **false** تنظیم کنید. قابل خواندن/نوشتن boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

مشخص می‌کند که یک یا چند پیوند فراخوانی در این بخش به‌صورت انحصاری توسط یک تولید کننده به‌روز شده‌اند. تولید کنندهٔ بعدی که این سند را باز می‌کند روابط پیوندها را با پیوندهای جدید به‌روزرسانی می‌کند. قابل خواندن/نوشتن boolean.

**Returns:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

مشخص می‌کند که یک یا چند پیوند فراخوانی در این بخش به‌صورت انحصاری توسط یک تولید کننده به‌روز شده‌اند. تولید کنندهٔ بعدی که این سند را باز می‌کند روابط پیوندها را با پیوندهای جدید به‌روزرسانی می‌کند. قابل خواندن/نوشتن boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

تعداد کل اسلایدهای سند ارائه را مشخص می‌کند. فقط خواندنی int.

**Returns:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

تعداد اسلایدهای مخفی در سند ارائه را مشخص می‌کند. فقط خواندنی int.

**Returns:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

تعداد اسلایدهایی که در ارائه حاوی یادداشت هستند را مشخص می‌کند. فقط خواندنی int.

**Returns:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

تعداد کل پاراگراف‌های موجود در سند (در صورت قابل اعمال) را مشخص می‌کند. فقط خواندنی int.

**Returns:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

تعداد کل کلمات موجود در سند را مشخص می‌کند. فقط خواندنی int.

**Returns:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

تعداد کل کلیپ‌های صوتی یا ویدیویی موجود در سند را مشخص می‌کند. فقط خواندنی int.

**Returns:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

عنوان هر بخش سند را مشخص می‌کند. این بخش‌ها بخش‌های واقعی سند نیستند بلکه نمایشی مفهومی از بخش‌های سند هستند. فقط خواندنی String[].

**Returns:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. فقط خواندنی IHeadingPair[].

**Returns:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

تعداد ویژگی‌های سفارشی موجود در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**Returns:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

نام ویژگی سفارشی در ایندکس مشخص را برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | شمارهٔ صفر مبنا ایندکس یک ویژگی سفارشی برای دریافت. |

**Returns:**
java.lang.String - نام ویژگی سفارشی در ایندکس مشخص.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای حذف. |

**Returns:**
boolean - اگر ویژگی حذف شد true برمی‌گرداند، در غیر اینصورت false.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای بررسی. |

**Returns:**
boolean - اگر ویژگی وجود داشته باشد true برمی‌گرداند، در غیر اینصورت false.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Object.

--------------------

مقدار می‌تواند **int**, **float**, **double**, **String**, **boolean** یا **Date** باشد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Object.

--------------------

مقدار می‌تواند **int**, **float**, **double**, **String**, **boolean** یا **Date** باشد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

تمام ویژگی‌های سفارشی را حذف می‌کند.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

تمام ویژگی‌های پیش‌ساخته را پاک می‌کند و مقادیر پیش‌فرض را تنظیم می‌کند.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

یک مقدار بولی با نام مشخص را از ویژگی‌های سفارشی می‌گیرد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | boolean[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

یک مقدار صحیح با نام مشخص را از ویژگی‌های سفارشی می‌گیرد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | int[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

یک مقدار DateTime با نام مشخص را از ویژگی‌های سفارشی می‌گیرد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | java.util.Date[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

یک مقدار رشته‌ای با نام مشخص را از ویژگی‌های سفارشی می‌گیرد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | java.lang.String[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

یک مقدار شناور با نام مشخص را از ویژگی‌های سفارشی می‌گیرد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت |
| value | float[] | مقدار ویژگی سفارشی |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

یک مقدار دوگانه با نام مشخص را از ویژگی‌های سفارشی می‌گیرد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای دریافت. |
| value | double[] | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

یک ویژگی سفارشی بولی با نام مشخص را تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | boolean | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

یک ویژگی سفارشی صحیح با نام مشخص را تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | int | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

یک ویژگی سفارشی DateTime با نام مشخص را تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | java.util.Date | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

یک ویژگی سفارشی رشته‌ای با نام مشخص را تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | java.lang.String | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

یک ویژگی سفارشی شناور با نام مشخص را تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | float | مقدار ویژگی سفارشی |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

یک ویژگی سفارشی دوگانه با نام مشخص را تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی سفارشی برای تنظیم |
| value | double | مقدار ویژگی سفارشی |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

آرایه‌ای از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند می‌گیرد (Microsoft Information Protection SDK Metadata).

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

**Returns:**
com.aspose.slides.ISensitivityLabel[]