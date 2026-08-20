---
title: PptOptions
second_title: Aspose.Slides ل Java مرجع API
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق PPT.
type: docs
url: /ar/com.aspose.slides/pptoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

يوفر خيارات تُتحكم في كيفية حفظ العرض التقديمي بتنسيق PPT.
## المنشئات

| Constructor | Description |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## الطرق

| Method | Description |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | يمثل GUID الفئة (CLSID) للكائن المخزن في إدخال الدليل الجذر. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | يمثل GUID الفئة (CLSID) للكائن المخزن في إدخال الدليل الجذر. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


يمثل GUID الفئة (CLSID) للكائن المخزن في إدخال الدليل الجذر. يمكن استخدامها لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتطابق مع 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// تعيين CLSID إلى 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


يمثل GUID الفئة (CLSID) للكائن المخزن في إدخال الدليل الجذر. يمكن استخدامها لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتطابق مع 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// تعيين CLSID إلى 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |