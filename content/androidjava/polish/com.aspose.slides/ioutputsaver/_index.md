---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saving service.
type: docs
url: /pl/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Reprezentuje usługę zapisywania wyjścia.
## Metody

| Metoda | Opis |
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka, w której zostanie zapisany plik. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Plik wyjściowy. |