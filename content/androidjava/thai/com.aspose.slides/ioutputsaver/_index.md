---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saving service.
type: docs
url: /th/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

แสดงถึงบริการการบันทึกเอาต์พุต.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | บันทึกไฟล์เอาต์พุตไปยังเส้นทางที่ระบุ |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


บันทึกไฟล์เอาต์พุตไปยังเส้นทางที่ระบุ.

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


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางที่ต้องการบันทึกไฟล์ |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | ไฟล์เอาต์พุต |
