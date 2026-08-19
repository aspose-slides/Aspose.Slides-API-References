---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Představuje službu pro ukládání výstupu.
type: docs
url: /cs/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Představuje službu pro ukládání výstupu.
## Metody

| Metoda | Popis |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Uloží výstupní soubor na zadanou cestu. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

Uloží výstupní soubor na zadanou cestu.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta, kam soubor uložit. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Výstupní soubor. |