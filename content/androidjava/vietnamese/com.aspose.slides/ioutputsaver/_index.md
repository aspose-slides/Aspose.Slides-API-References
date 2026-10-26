---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saving service.
type: docs
url: /vi/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Biểu thị một dịch vụ lưu đầu ra.
## Phương thức

| Method | Description |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Lưu tệp đầu ra vào đường dẫn đã cho. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Lưu tệp đầu ra vào đường dẫn đã cho.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn để lưu tệp. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Tệp đầu ra. |