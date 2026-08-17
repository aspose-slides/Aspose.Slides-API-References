---
title: IOutputSaver
second_title: Aspose.Slides για Java Αναφορά API
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
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Αποθηκεύει το αρχείο εξόδου στη δοσμένη διαδρομή. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Αποθηκεύει το αρχείο εξόδου στη δοσμένη διαδρομή.

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
| path | java.lang.String | Διαδρομή για την αποθήκευση του αρχείου. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Αρχείο εξόδου. |