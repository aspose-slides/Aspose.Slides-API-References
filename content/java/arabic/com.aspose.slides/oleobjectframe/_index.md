---
title: OleObjectFrame
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل كائن OLE على شريحة.
type: docs
url: /ar/com.aspose.slides/oleobjectframe/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

يمثل كائن OLE على شريحة.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // يحمل ملف PPTX إلى كائن العرض التقديمي
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // يصل إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // يحول الشكل إلى OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // يقرأ كائن OLE ويكتبه إلى القرص
>      if (oleObjectFrame != null) {
>          // يحصل على بيانات الملف المضمّن
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // يحصل على امتداد الملف المضمّن
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // ينشئ مسارًا لحفظ الملف المستخرج
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // يحفظ البيانات المستخرجة
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | يرجع كائن خصائص تعبئة الصورة لـ OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | يرجع أو يعيّن العنوان لأيقونة OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | يرجع أو يعيّن العنوان لأيقونة OleObject. |
| [getObjectName()](#getObjectName--) | يرجع أو يعيّن اسم كائن. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | يرجع أو يعيّن اسم كائن. |
| [getObjectProgId()](#getObjectProgId--) | يرجع ProgID لكائن. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | يرجع ProgID لكائن. |
| [getLinkFileName()](#getLinkFileName--) | يرجع المسار الكامل لملف مرتبط. |
| [getLinkPathLong()](#getLinkPathLong--) | يرجع المسار الكامل لملف مرتبط. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | يرجع المسار الكامل لملف مرتبط. |
| [getLinkPathRelative()](#getLinkPathRelative--) | يرجع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا يرجع سلسلة فارغة. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | يرجع اسم ملف كائن OLE المضمن. |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | يرجع مسار كائن OLE المضمن. |
| [getEmbeddedData()](#getEmbeddedData--) | يحصل أو يعيّن معلومات حول بيانات OLE المضمنة. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | يعيّن معلومات حول بيانات OLE المضمنة. |
| [isObjectIcon()](#isObjectIcon--) | يحدد ما إذا كان الكائن مرئيًا كأيقونة. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | يحدد ما إذا كان الكائن مرئيًا كأيقونة. |
| [isObjectLink()](#isObjectLink--) | يحدد ما إذا كان الكائن مرتبطًا بملف خارجي. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | يحدد ما إذا كان الكائن المضمّن المرتبط يحدث تلقائيًا عند فتح أو طباعة العرض التقديمي. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | يحدد ما إذا كان الكائن المضمّن المرتبط يحدث تلقائيًا عند فتح أو طباعة العرض التقديمي. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

يرجع كائن خصائص تعبئة الصورة لـ OleObject. للقراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

يرجع أو يعيّن العنوان لأيقونة OleObject. قراءة/كتابة String.

--------------------

عندما تكون IsObjectIcon == false يتم تجاهل هذه القيمة. يمكن قص السلسلة وفقًا لحجم أيقونة Ole.

**الإرجاع:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

يرجع أو يعيّن العنوان لأيقونة OleObject. قراءة/كتابة String.

--------------------

عندما تكون IsObjectIcon == false يتم تجاهل هذه القيمة. يمكن قص السلسلة وفقًا لحجم أيقونة Ole.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

يرجع أو يعيّن اسم كائن. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

يرجع أو يعيّن اسم كائن. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

يرجع ProgID لكائن. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

يرجع ProgID لكائن. للقراءة فقط String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

يرجع المسار الكامل لملف مرتبط. سيُستخدم اسم ملف قصير. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

يرجع المسار الكامل لملف مرتبط. سيُستخدم اسم ملف طويل. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

يرجع المسار الكامل لملف مرتبط. سيُستخدم اسم ملف طويل. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

يرجع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا يرجع سلسلة فارغة. للقراءة فقط String.

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

في عروض Ppt التقديمية، قد يحتوي بعض روابط كائنات Ole على تمثيل نسبي.

**الإرجاع:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

يرجع اسم ملف كائن OLE المضمن

**الإرجاع:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

يرجع مسار كائن OLE المضمن

**الإرجاع:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

يحصل أو يعيّن معلومات حول بيانات OLE المضمنة. قراءة/كتابة [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**الإرجاع:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

يعيّن معلومات حول بيانات OLE المضمنة.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | البيانات المضمّنة [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

هذه الطريقة تغير خصائص الكائن لتعكس البيانات الجديدة وتضبط علامة IsObjectLink إلى false، مما يدل على أن كائن OLE مضمّن.

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

يحدد ما إذا كان الكائن مرئيًا كأيقونة. قراءة/كتابة boolean .

**الإرجاع:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

يحدد ما إذا كان الكائن مرئيًا كأيقونة. قراءة/كتابة boolean .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

يحدد ما إذا كان الكائن مرتبطًا بملف خارجي. للقراءة فقط boolean .

**الإرجاع:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

يحدد ما إذا كان الكائن المضمّن المرتبط يحدث تلقائيًا عند فتح أو طباعة العرض التقديمي. قراءة/كتابة boolean .

**الإرجاع:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

يحدد ما إذا كان الكائن المضمّن المرتبط يحدث تلقائيًا عند فتح أو طباعة العرض التقديمي. قراءة/كتابة boolean .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |