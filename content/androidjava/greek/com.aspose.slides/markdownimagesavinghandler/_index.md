---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει το διαχειριστή αποθήκευσης εικόνας markdown της εκδήλωσης ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /el/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Αντιπροσωπεύει το διαχειριστή αποθήκευσης εικόνας markdown της εκδήλωσης #ImageSavingDelegate.ImageSavingDelegate event.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Καλείται για κάθε μη SVG εικόνα (bitmap ή metafile) κατά την εξαγωγή Markdown. Επιστρέψτε true για να χρησιμοποιήσετε το καθορισμένο σύνδεσμο, ή false για να εφαρμόσετε την προεπιλεγμένη λογική αποθήκευσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Η εικόνα που εξάγεται (bitmap ή metafile). |
| format | int | Η μορφή εικόνας. |
| link | java.lang.String[] | Ο σύνδεσμος Markdown που θα χρησιμοποιηθεί όταν επιστρέφεται true. |

**Τιμή Επιστροφής:**
boolean