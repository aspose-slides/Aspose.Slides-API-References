---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Represents an output saving service.
type: docs
url: /id/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Mewakili layanan penyimpanan output.
## Metode

| Method | Description |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Menyimpan file output ke jalur yang diberikan. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Menyimpan file output ke jalur yang diberikan.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur untuk menyimpan file. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | File output. |