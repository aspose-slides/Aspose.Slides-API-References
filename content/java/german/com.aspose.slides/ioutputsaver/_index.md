---
title: IOutputSaver
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Ausgabespeicherdienst dar.
type: docs
url: /de/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Stellt einen Ausgabespeicherdienst dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Speichert die Ausgabedatei im angegebenen Pfad. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Speichert die Ausgabedatei im angegebenen Pfad.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Pfad, in dem die Datei gespeichert werden soll. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Ausgabedatei. |