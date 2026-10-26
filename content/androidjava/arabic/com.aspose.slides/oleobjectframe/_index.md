---
title: OleObjectFrame
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل كائن OLE على شريحة.
type: docs
url: /ar/com.aspose.slides/oleobjectframe/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

يمثل كائن OLE على شريحة.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // يحمِّل ملف PPTX إلى كائن عرض تقديمي
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // يصل إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // يقوم بتحويل الشكل إلى OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // يقوم بقراءة كائن OLE وكتابته إلى القرص
>      if (oleObjectFrame != null) {
>          // يحصل على بيانات الملف المضمّن
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // يحصل على امتداد الملف المضمّن
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // ينشئ مسارًا لحفظ الملف المستخرج
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // يحفظ البيانات المستخرجة
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | إرجاع كائن خصائص تعبئة صورة OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | إرجاع أو تعيين عنوان أيقونة OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | إرجاع أو تعيين عنوان أيقونة OleObject. |
| [getObjectName()](#getObjectName--) | إرجاع أو تعيين اسم كائن. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | إرجاع أو تعيين اسم كائن. |
| [getObjectProgId()](#getObjectProgId--) | إرجاع ProgID لكائن. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | إرجاع ProgID لكائن. |
| [getLinkFileName()](#getLinkFileName--) | إرجاع المسار الكامل لملف مرتبط. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع المسار الكامل لملف مرتبط. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع المسار الكامل لملف مرتبط. |
| [getLinkPathRelative()](#getLinkPathRelative--) | إرجاع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا إرجاع سلسلة فارغة. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | إرجاع اسم ملف كائن OLE المضمن |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | إرجاع مسار كائن OLE المضمن |
| [getEmbeddedData()](#getEmbeddedData--) | إرجاع أو تعيين معلومات حول بيانات OLE المضمنة. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | تعيين معلومات حول بيانات OLE المضمنة. |
| [isObjectIcon()](#isObjectIcon--) | تحديد ما إذا كان كائن مرئيًا كأيقونة. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | تحديد ما إذا كان كائن مرئيًا كأيقونة. |
| [isObjectLink()](#isObjectLink--) | تحديد ما إذا كان كائن مرتبط بملف خارجي. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | تحديد ما إذا تم تحديث الكائن المضمن المرتبط تلقائيًا عند فتح العرض التقديمي أو طباعته. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | تحديد ما إذا تم تحديث الكائن المضمن المرتبط تلقائيًا عند فتح العرض التقديمي أو طباعته. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

إرجاع كائن خصائص تعبئة صورة OleObject. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

إرجاع أو تعيين عنوان أيقونة OleObject. قراءة/كتابة String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon.

**الإرجاع:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

إرجاع أو تعيين عنوان أيقونة OleObject. قراءة/كتابة String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

إرجاع أو تعيين اسم كائن. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

إرجاع أو تعيين اسم كائن. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

إرجاع ProgID لكائن. قراءة فقط String.

**الإرجاع:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

إرجاع ProgID لكائن. قراءة فقط String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

إرجاع المسار الكامل لملف مرتبط. سيتم استخدام اسم ملف قصير. قراءة فقط String.

**الإرجاع:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

إرجاع المسار الكامل لملف مرتبط. سيتم استخدام اسم ملف طويل. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

إرجاع المسار الكامل لملف مرتبط. سيتم استخدام اسم ملف طويل. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

إرجاع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا إرجاع سلسلة فارغة. قراءة فقط String.

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

In the Ppt presentations, some Ole object links may have a relative representation.

**الإرجاع:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

إرجاع اسم ملف كائن OLE المضمن

**الإرجاع:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

إرجاع مسار كائن OLE المضمن

**الإرجاع:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

إرجاع أو تعيين معلومات حول بيانات OLE المضمنة. قراءة/كتابة [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**الإرجاع:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

تعيين معلومات حول بيانات OLE المضمنة.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | البيانات المضمنة [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

هذه الطريقة تغير خصائص الكائن لتعكس البيانات الجديدة وتحدد علم IsObjectLink إلى false، مما يدل على أن كائن OLE مضمّن. |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

تحديد ما إذا كان كائن مرئيًا كأيقونة. قراءة/كتابة boolean .

**الإرجاع:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

تحديد ما إذا كان كائن مرئيًا كأيقونة. قراءة/كتابة boolean .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

تحديد ما إذا كان كائن مرتبط بملف خارجي. قراءة فقط boolean .

**الإرجاع:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

تحديد ما إذا تم تحديث الكائن المضمن المرتبط تلقائيًا عند فتح العرض التقديمي أو طباعته. قراءة/كتابة boolean .

**الإرجاع:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

تحديد ما إذا تم تحديث الكائن المضمن المرتبط تلقائيًا عند فتح العرض التقديمي أو طباعته. قراءة/كتابة boolean .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |