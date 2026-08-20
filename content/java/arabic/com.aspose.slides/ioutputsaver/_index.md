---
title: IOutputSaver
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل خدمة حفظ الإخراج.
type: docs
url: /ar/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

يمثل خدمة حفظ الإخراج.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | يحفظ ملف الإخراج في المسار المحدد. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


يحفظ ملف الإخراج في المسار المحدد.

--------------------

> ```
> Saving into the FileStream implementation example:
>  
>  public void save(String path, IOutputFile outputFile)
>  {
>      FileOutputStream stream = new FileOutputStream(path);
>      try {
>          outputFile.write(stream);
>      } catch (IOException e) {
>      } finally {
>          if (stream != null) stream.close();
>      }
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | المسار لحفظ الملف فيه. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | ملف الإخراج. |