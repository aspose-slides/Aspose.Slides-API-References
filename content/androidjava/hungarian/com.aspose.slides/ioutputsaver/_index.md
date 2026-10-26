---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Kimeneti mentési szolgáltatást képvisel.
type: docs
url: /hu/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Kimeneti mentési szolgáltatást képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | A kimeneti fájlt a megadott útvonalra menti. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


A kimeneti fájlt a megadott útvonalra menti.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Az útvonal, ahová a fájlt menteni kell. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Kimeneti fájl. |