---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Representerar en tjänst för att spara utdata.
type: docs
url: /sv/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Representerar en tjänst för att spara utdata.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Sparar utdatafilen till den angivna sökvägen. |

### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

Sparar utdatafilen till den angivna sökvägen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg att spara filen till. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Utdatfil. |