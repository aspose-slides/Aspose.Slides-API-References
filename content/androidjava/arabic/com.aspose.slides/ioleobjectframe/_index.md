---
title: IOleObjectFrame
second_title: Aspose.Slides للـ Android عبر مرجع Java API
description: يمثل كائن OLE على شريحة.
type: docs
url: /ar/com.aspose.slides/ioleobjectframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

يمثل كائن OLE على شريحة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | إرجاع كائن خصائص تعبئة صورة OleObject. |
| [getObjectName()](#getObjectName--) | إرجاع أو تعيين اسم كائن. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | إرجاع أو تعيين اسم كائن. |
| [getEmbeddedData()](#getEmbeddedData--) | جلب معلومات حول بيانات OLE المدمجة. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | تعيين معلومات حول بيانات OLE المدمجة. |
| [getObjectProgId()](#getObjectProgId--) | إرجاع ProgID لكائن. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | إرجاع ProgID لكائن. |
| [getLinkFileName()](#getLinkFileName--) | إرجاع المسار الكامل لملف مرتبط. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع المسار الكامل لملف مرتبط. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع المسار الكامل لملف مرتبط. |
| [getLinkPathRelative()](#getLinkPathRelative--) | إرجاع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا إرجاع سلسلة فارغة. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | إرجاع اسم ملف كائن OLE المدمج |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | إرجاع مسار كائن OLE المدمج |
| [isObjectIcon()](#isObjectIcon--) | تحديد ما إذا كان الكائن مرئيًا كأيقونة. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | تحديد ما إذا كان الكائن مرئيًا كأيقونة. |
| [isObjectLink()](#isObjectLink--) | تحديد ما إذا كان الكائن مرتبطًا بملف خارجي. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | تحديد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح العرض أو طباعته. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | تحديد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح العرض أو طباعته. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | إرجاع أو تعيين العنوان لأيقونة OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | إرجاع أو تعيين العنوان لأيقونة OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

إرجاع كائن خصائص تعبئة صورة OleObject. للقراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

إرجاع أو تعيين اسم كائن. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

إرجاع أو تعيين اسم كائن. قابل للقراءة والكتابة String.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

جلب معلومات حول بيانات OLE المدمجة. للقراءة فقط [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**الإرجاع:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

تعيين معلومات حول بيانات OLE المدمجة.

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
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


**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | بيانات مدمجة [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

هذه الطريقة تقوم بتغيير خصائص الكائن لتتناسب مع البيانات الجديدة وتضع علامة IsObjectLink إلى false، مما يشير إلى أن كائن OLE مدمج. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

إرجاع ProgID لكائن. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

إرجاع ProgID لكائن. للقراءة فقط String.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

إرجاع المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف القصير. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

إرجاع المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف الطويل. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

إرجاع المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف الطويل. قابل للقراءة والكتابة String.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

إرجاع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا إرجاع سلسلة فارغة. للقراءة فقط String.

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


في عروض PowerPoint، قد تحتوي بعض روابط كائنات Ole على تمثيل نسبي.

**الإرجاع:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

إرجاع اسم ملف كائن OLE المدمج

**الإرجاع:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

إرجاع مسار كائن OLE المدمج

**الإرجاع:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

تحديد ما إذا كان الكائن مرئيًا كأيقونة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

تحديد ما إذا كان الكائن مرئيًا كأيقونة. قابل للقراءة والكتابة boolean.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

تحديد ما إذا كان الكائن مرتبطًا بملف خارجي. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

تحديد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح العرض أو طباعته. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

تحديد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح العرض أو طباعته. قابل للقراءة والكتابة boolean.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

إرجاع أو تعيين العنوان لأيقونة OleObject. قابل للقراءة والكتابة String.

عند تكون IsObjectIcon == false يتم تجاهل هذه القيمة. يمكن اقتطاع السلسلة وفقًا لحجم أيقونة OLE.

**الإرجاع:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

إرجاع أو تعيين العنوان لأيقونة OleObject. قابل للقراءة والكتابة String.

عند تكون IsObjectIcon == false يتم تجاهل هذه القيمة. يمكن اقتطاع السلسلة وفقًا لحجم أيقونة OLE.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |