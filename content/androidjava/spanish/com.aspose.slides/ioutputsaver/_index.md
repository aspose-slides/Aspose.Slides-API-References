---
title: IOutputSaver
second_title: Aspose.Slides para Android mediante la referencia de API de Java
description: Representa un servicio de guardado de salida.
type: docs
url: /es/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Representa un servicio de guardado de salida.
## Métodos

| Método | Descripción |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Guarda el archivo de salida en la ruta especificada. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

Guarda el archivo de salida en la ruta especificada.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta donde guardar el archivo. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Archivo de salida. |