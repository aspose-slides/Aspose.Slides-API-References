---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides για την Αναφορά API Java
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /el/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Αντιπροσωπεύει τον χειριστή αποθήκευσης markdown SVG εικόνας του \#SvgImageSavingDelegate.SvgImageSavingDelegate event.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Καλείται για κάθε SVG εικόνα κατά την εξαγωγή Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Καλείται για κάθε SVG εικόνα κατά την εξαγωγή Markdown. Επιστρέψτε true για να χρησιμοποιήσετε το καθορισμένο σύνδεσμο, ή false για να εφαρμόσετε την προεπιλεγμένη λογική αποθήκευσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Η SVG εικόνα που εξάγεται. |
| link | java.lang.String[] | Ο σύνδεσμος Markdown που χρησιμοποιείται όταν επιστρέφεται true. |

**Επιστρέφει:**
boolean