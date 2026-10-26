---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /el/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Αντιπροσωπεύει τον διαχειριστή αποθήκευσης εικόνας markdown του \#ImageSavingDelegate.ImageSavingDelegate συμβάντος.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Καλείται για κάθε εικόνα που δεν είναι SVG (bitmap ή metafile) κατά την εξαγωγή Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Καλείται για κάθε εικόνα που δεν είναι SVG (bitmap ή metafile) κατά την εξαγωγή Markdown. Επιστρέψτε true για να χρησιμοποιήσετε το καθορισμένο σύνδεσμο ή false για να εφαρμόσετε την προεπιλεγμένη λογική αποθήκευσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Η εικόνα που εξάγεται (bitmap ή metafile). |
| format | int | Η μορφή της εικόνας. |
| link | java.lang.String[] | Ο σύνδεσμος Markdown για χρήση όταν επιστρέφεται true. |

**Επιστρέφει:**
boolean