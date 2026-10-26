---
title: IOutputSaver
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un service d'enregistrement de sortie.
type: docs
url: /fr/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Représente un service d'enregistrement de sortie.
## Méthodes

| Méthode | Description |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Enregistre le fichier de sortie à l'emplacement indiqué. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Enregistre le fichier de sortie à l'emplacement indiqué.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin où enregistrer le fichier. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Fichier de sortie. |