---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saving service.
type: docs
url: /fa/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

نمایندهٔ سرویس ذخیره‌سازی خروجی است.
## متدها

| متد | توضیح |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | فایل خروجی را در مسیر داده شده ذخیره می‌کند. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


فایل خروجی را در مسیر داده شده ذخیره می‌کند.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر برای ذخیره‌سازی فایل. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | فایل خروجی. |