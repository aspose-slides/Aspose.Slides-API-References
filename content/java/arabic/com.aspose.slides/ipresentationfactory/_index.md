---
title: IPresentationFactory
second_title: Aspose.Slides لـ Java مرجع API
description: يسمح بإنشاء عرض تقديمي عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

يسمح بإنشاء عرض تقديمي عبر واجهة COM

## Methods

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | ينشئ عرض تقديمي جديد. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | ينشئ عرض تقديمي جديد مع خيارات تحميل إضافية |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | يحصل على معلومات حول العرض التقديمي في الملف المحدد. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | يحصل على معلومات حول العرض التقديمي في الدفق المحدد. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | يقرأ عرض تقديمي موجود من مصفوفة |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | يقرأ عرض تقديمي موجود من مصفوفة مع خيارات تحميل إضافية |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | يقرأ عرض تقديمي موجود من دفق |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | يقرأ عرض تقديمي موجود من دفق مع خيارات تحميل إضافية |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | يقرأ عرض تقديمي موجود من ملف |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | يقرأ عرض تقديمي موجود من دفق مع خيارات تحميل إضافية |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | يسترجع النص الخام من الشرائح |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | يسترجع النص الخام من الشرائح |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | يسترجع النص الخام من الشرائح |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

ينشئ عرض تقديمي جديد.

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض الجديد
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

ينشئ عرض تقديمي جديد مع خيارات تحميل إضافية

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض الجديد
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

يحصل على معلومات حول العرض التقديمي في الملف المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | ملف العرض التقديمي. |

**القيمة المرجعة:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - معلومات العرض التقديمي
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

يحصل على معلومات حول العرض التقديمي في الدفق المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | دفق العرض التقديمي. |

**القيمة المرجعة:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - معلومات العرض التقديمي.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

يقرأ عرض تقديمي موجود من مصفوفة

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | المصفوفة للقراءة |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

يقرأ عرض تقديمي موجود من مصفوفة مع خيارات تحميل إضافية

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | المصفوفة للقراءة |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

يقرأ عرض تقديمي موجود من دفق

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | دفق الإدخال للقراءة |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

يقرأ عرض تقديمي موجود من دفق مع خيارات تحميل إضافية

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | دفق الإدخال للقراءة |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

يقرأ عرض تقديمي موجود من ملف

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | اسم الملف |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

يقرأ عرض تقديمي موجود من دفق مع خيارات تحميل إضافية

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | اسم الملف |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation) - العرض المقروء
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

يسترجع النص الخام من الشرائح

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال |
| mode | int | وضع الاستخلاص |

**القيمة المرجعة:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - المثيل PresentationText الذي يحتوي على مصفوفة SlideText تمثّل النص الخام للشرائح
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

يسترجع النص الخام من الشرائح

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | دفق الإدخال |
| mode | int | وضع الاستخلاص |

**القيمة المرجعة:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - المثيل PresentationText الذي يحتوي على مصفوفة SlideText تمثّل النص الخام للشرائح
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

يسترجع النص الخام من الشرائح

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | دفق الإدخال |
| mode | int | وضع الاستخلاص |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | خيارات التحميل |

**القيمة المرجعة:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - المثيل PresentationText الذي يحتوي على مصفوفة SlideText تمثّل النص الخام للشرائح