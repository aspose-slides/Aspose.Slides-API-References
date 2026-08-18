---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje usługę zapisywania wyjścia.
type: docs
url: /pl/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Reprezentuje usługę zapisywania wyjścia.
## Metody

| Method | Description |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Zapisuje plik wyjściowy w podanej ścieżce. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Zapisuje plik wyjściowy w podanej ścieżce.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Ścieżka, w której zapisać plik. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Plik wyjściowy. |