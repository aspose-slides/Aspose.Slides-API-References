---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta un servizio di salvataggio dell'output.
type: docs
url: /it/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Rappresenta un servizio di salvataggio dell'output.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Salva il file di output nel percorso specificato. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Salva il file di output nel percorso specificato.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso in cui salvare il file. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | File di output. |