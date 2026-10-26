---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: 表示一个输出保存服务。
type: docs
url: /zh/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

表示一个输出保存服务。
## 方法

| 方法 | 描述 |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | 将输出文件保存到指定路径。 |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

将输出文件保存到指定路径。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 要保存文件的路径。 |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 输出文件。 |