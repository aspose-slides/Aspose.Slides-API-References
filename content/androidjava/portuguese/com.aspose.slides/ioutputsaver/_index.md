---
title: IOutputSaver
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um serviço de salvamento de saída.
type: docs
url: /pt/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Representa um serviço de salvamento de saída.
## Métodos

| Método | Descrição |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Saves the output file to the given path. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

Salva o arquivo de saída no caminho especificado.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Caminho onde o arquivo será salvo. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Arquivo de saída. |