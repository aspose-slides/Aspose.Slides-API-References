---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saving service.
type: docs
url: /ko/com.aspose.slides/ioutputsaver/
---
```
public interface IOutputSaver
```

출력 저장 서비스를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | 지정된 경로에 출력 파일을 저장합니다. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

지정된 경로에 출력 파일을 저장합니다.

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


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 파일을 저장할 경로. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 출력 파일. |