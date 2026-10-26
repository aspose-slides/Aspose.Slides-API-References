---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Представляет сервис сохранения вывода.
type: docs
url: /ru/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Представляет сервис сохранения вывода.
## Методы

| Метод | Описание |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Сохраняет выходной файл по указанному пути. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Сохраняет выходной файл по указанному пути.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, по которому сохраняется файл. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Выходной файл. |