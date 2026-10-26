---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Represents an output saving service.
type: docs
url: /nl/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Vertegenwoordigt een service voor het opslaan van output.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Slaat het uitvoerbestand op naar het opgegeven pad. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

Slaat het uitvoerbestand op naar het opgegeven pad.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Pad om het bestand op te slaan. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Uitvoerbestand. |