---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει μια υπηρεσία αποθήκευσης εξόδου.
type: docs
url: /el/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Αντιπροσωπεύει μια υπηρεσία αποθήκευσης εξόδου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Saves the output file to the given path. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

Αποθηκεύει το αρχείο εξόδου στη δοθείσα διαδρομή.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή για αποθήκευση του αρχείου. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Αρχείο εξόδου. |