---
title: PresentationFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يسمح بإنشاء عرض تقديمي عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/presentationfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

يسمح بإنشاء عرض تقديمي عبر واجهة COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثيل ثابت لمصنع العرض. |
| [createPresentation()](#createPresentation--) | إنشاء عرض تقديمي جديد. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | إنشاء عرض تقديمي جديد مع خيارات تحميل إضافية |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | إنشاء كائن PresentationInfo جديد من ملف وربط العرض به. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | إنشاء كائن PresentationInfo جديد من تدفق وربط العرض به. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | قراءة عرض تقديمي موجود من مصفوفة |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | قراءة عرض تقديمي موجود من مصفوفة مع خيارات تحميل إضافية |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | قراءة عرض تقديمي موجود من تدفق |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | قراءة عرض تقديمي موجود من تدفق مع خيارات تحميل إضافية |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | قراءة عرض تقديمي موجود من ملف |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | قراءة عرض تقديمي موجود من تدفق مع خيارات تحميل إضافية |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | استخراج النص الخام من الشرائح |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | استخراج النص الخام من الشرائح |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | استخراج النص الخام من الشرائح |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


مثيل ثابت لمصنع العرض. للقراءة فقط [PresentationFactory](../../com.aspose.slides/presentationfactory).

**القيمة المرجعة:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


إنشاء عرض تقديمي جديد.

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - عرض تقديمي جديد
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


إنشاء عرض تقديمي جديد مع خيارات تحميل إضافية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - عرض تقديمي جديد
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


إنشاء كائن PresentationInfo جديد من ملف وربط العرض به.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف العرض. |

**القيمة المرجعة:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - معلومات العرض المرتبطة بالعرض.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


إنشاء كائن PresentationInfo جديد من تدفق وربط العرض به. الحصول على معلومات حول العرض في التدفق المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق العرض. |

**القيمة المرجعة:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - معلومات العرض المرتبطة بالعرض.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


قراءة عرض تقديمي موجود من مصفوفة

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | المصفوفة للقراءة |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


قراءة عرض تقديمي موجود من مصفوفة مع خيارات تحميل إضافية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | المصفوفة للقراءة |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPPresentation readPresentation(InputStream stream)
```


قراءة عرض تقديمي موجود من تدفق

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال للقراءة |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


قراءة عرض تقديمي موجود من تدفق مع خيارات تحميل إضافية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال للقراءة |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


قراءة عرض تقديمي موجود من ملف

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | اسم الملف |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


قراءة عرض تقديمي موجود من ملف مع خيارات تحميل إضافية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | اسم الملف |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


استخراج النص الخام من الشرائح

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال |
| mode | int | وضع الاستخلاص |

**القيمة المرجعة:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - النسخة من PresentationText التي تحتوي على مصفوفة SlideText تمثل نص الشرائح الخام
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


استخراج النص الخام من الشرائح

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال |
| mode | int | وضع الاستخلاص |

**القيمة المرجعة:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - النسخة من PresentationText التي تحتوي على مصفوفة SlideText تمثل نص الشرائح الخام
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


استخراج النص الخام من الشرائح

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال |
| mode | int | وضع الاستخلاص |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - النسخة من PresentationText التي تحتوي على مصفوفة SlideText تمثل نص الشرائح الخام