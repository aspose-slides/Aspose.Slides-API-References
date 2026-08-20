---
title: IOleObjectFrame
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل كائن OLE على شريحة.
type: docs
url: /ar/com.aspose.slides/ioleobjectframe/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

يمثل كائن OLE على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | يعيد كائن خصائص تعبئة صورة OleObject. |
| [getObjectName()](#getObjectName--) | يعيد أو يضبط اسم كائن. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | يعيد أو يضبط اسم كائن. |
| [getEmbeddedData()](#getEmbeddedData--) | يحصل على معلومات حول بيانات OLE المدمجة. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | يضبط معلومات حول بيانات OLE المدمجة. |
| [getObjectProgId()](#getObjectProgId--) | يعيد ProgID لكائن. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | يعيد ProgID لكائن. |
| [getLinkFileName()](#getLinkFileName--) | يعيد المسار الكامل لملف مرتبط. |
| [getLinkPathLong()](#getLinkPathLong--) | يعيد المسار الكامل لملف مرتبط. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | يعيد المسار الكامل لملف مرتبط. |
| [getLinkPathRelative()](#getLinkPathRelative--) | يعيد المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا يعيد سلسلة فارغة. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | يعيد اسم ملف كائن OLE المدمج |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | يعيد مسار كائن OLE المدمج |
| [isObjectIcon()](#isObjectIcon--) | يحدد ما إذا كان الكائن مرئيًا كأيقونة. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | يحدد ما إذا كان الكائن مرئيًا كأيقونة. |
| [isObjectLink()](#isObjectLink--) | يحدد ما إذا كان الكائن مرتبطًا بملف خارجي. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | يحدد ما إذا كان الكائن المدمج المرتبط يُحدَّث تلقائيًا عند فتح أو طباعة العرض التقديمي. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | يحدد ما إذا كان الكائن المدمج المرتبط يُحدَّث تلقائيًا عند فتح أو طباعة العرض التقديمي. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | يعيد أو يضبط العنوان لأيقونة OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | يعيد أو يضبط العنوان لأيقونة OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

يعيد كائن خصائص تعبئة صورة OleObject. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**القيمة المرجعة:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

يعيد أو يضبط اسم كائن. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

يعيد أو يضبط اسم كائن. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

يحصل على معلومات حول بيانات OLE المدمجة. قراءة فقط [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**القيمة المرجعة:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

يضبط معلومات حول بيانات OLE المدمجة.

--------------------
> ```
> يوضح المثال التالي كيفية تغيير بيانات OLE المدمجة
>  ونوعها لكائن [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) موجود 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | بيانات مدمجة [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------
تغيّر هذه الطريقة خصائص الكائن لتنعكس البيانات الجديدة وتضبط علامة IsObjectLink إلى false، مما يدل على أن كائن OLE مدمج. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

يعيد ProgID لكائن. قراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

يعيد ProgID لكائن. قراءة فقط String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

يعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم ملف قصير. قراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

يعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم ملف طويل. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

يعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم ملف طويل. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

يعيد المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا يعيد سلسلة فارغة. قراءة فقط String.

--------------------
> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------
في عروض Ppt التقديمية، قد تكون بعض روابط كائنات Ole ذات تمثيل نسبي.

**القيمة المرجعة:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

يعيد اسم ملف كائن OLE المدمج

**القيمة المرجعة:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

يعيد مسار كائن OLE المدمج

**القيمة المرجعة:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

يحدد ما إذا كان الكائن مرئيًا كأيقونة. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

يحدد ما إذا كان الكائن مرئيًا كأيقونة. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

يحدد ما إذا كان الكائن مرتبطًا بملف خارجي. قراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

يحدد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح أو طباعة العرض التقديمي. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

يحدد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح أو طباعة العرض التقديمي. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

يعيد أو يضبط العنوان لأيقونة OleObject. قراءة/كتابة String.

--------------------
عند يكون IsObjectIcon == false يتم تجاهل هذه القيمة. يمكن قطع السلسلة وفقًا لحجم أيقونة OLE.

**القيمة المرجعة:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

يعيد أو يضبط العنوان لأيقونة OleObject. قراءة/كتابة String.

--------------------
عند يكون IsObjectIcon == false يتم تجاهل هذه القيمة. يمكن قطع السلسلة وفقًا لحجم أيقونة OLE.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |