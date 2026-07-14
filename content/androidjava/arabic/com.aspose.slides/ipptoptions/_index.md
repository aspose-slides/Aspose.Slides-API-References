---
title: IPptOptions
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة PPT.
type: docs
url: /ar/com.aspose.slides/ipptoptions/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة PPT.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | يمثل GUID (CLSID) لفئة الكائن المخزن في إدخال الدليل الجذر. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | يمثل GUID (CLSID) لفئة الكائن المخزن في إدخال الدليل الجذر. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

يمثل GUID (CLSID) لفئة الكائن المخزن في إدخال الدليل الجذر. يمكن استخدامه لتفعيل COM لتطبيق الوثيقة. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتطابق مع 'Microsoft Powerpoint.Slide.8'.

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

**القيمة المرجعة:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

يمثل GUID (CLSID) لفئة الكائن المخزن في إدخال الدليل الجذر. يمكن استخدامه لتفعيل COM لتطبيق الوثيقة. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتطابق مع 'Microsoft Powerpoint.Slide.8'.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |