---
title: Output
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من عناصر الإخراج لـ IWebDocument.
type: docs
url: /ar/com.aspose.slides/output/
---
**الوراثة:**
java.lang.Object
```
public final class Output
```

يمثل مجموعة من عناصر الإخراج لـ IWebDocument.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | يضيف عنصر إخراج لكائن السياق. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | يضيف عنصر إخراج للصورة. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | يضيف عنصر إخراج للصورة. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | يضيف عنصر إخراج للفيديو. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | ينشئ ويضيف عنصر ملف إخراج للخط المحدد. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | يضيف عنصر إخراج لمحتوى النص. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | يربط المورد بملف الإخراج. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | يرجع المسار لمورد معين. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

يضيف عنصر إخراج لكائن السياق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الإخراج. |
| templateKey | java.lang.String | المفتاح المستخدم لتحويل كائن السياق قبل الإخراج. |
| contextObject | TContextObject | كائن السياق. |

**القيمة المرجعة:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) كائن لكائن السياق.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

يضيف عنصر إخراج للصورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الإخراج. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للإخراج. |

**القيمة المرجعة:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) كائن للصورة.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

يضيف عنصر إخراج للصورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الإخراج. |
| image | [IImage](../../com.aspose.slides/iimage) | الصورة للإخراج. |

**القيمة المرجعة:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) كائن للصورة.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

يضيف عنصر إخراج للفيديو.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الإخراج. |
| video | [IVideo](../../com.aspose.slides/ivideo) | الفيديو للإخراج. |

**القيمة المرجعة:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) كائن للفيديو.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

ينشئ ويضيف عنصر ملف إخراج للخط المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الملف حيث سيتم حفظ إخراج الخط. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | بيانات الخط التي سيتم كتابتها إلى الإخراج. |
| fontStyle | int | نمط الخط (مثال: Regular, Bold, Italic). |

**القيمة المرجعة:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - An [IOutputFile](../../com.aspose.slides/ioutputfile) instance للخط المُنشأ.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

يضيف عنصر إخراج لمحتوى النص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الإخراج. |
| textContent | java.lang.String | المحتوى للإخراج. |

**القيمة المرجعة:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) كائن لمحتوى النص.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

يربط المورد بملف الإخراج.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | ملف الإخراج. |
| obj | java.lang.Object | كائن المورد. |
### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

يرجع المسار لمورد معين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | كائن المورد. |

**القيمة المرجعة:**
java.lang.String - مسار المورد.