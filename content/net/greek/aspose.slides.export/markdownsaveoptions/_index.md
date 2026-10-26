---
title: MarkdownSaveOptions
second_title: Aspose.Sildes για την αναφορά API .NET
description: Αντιπροσωπεύει τις επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.
type: docs
weight: 4250
url: /el/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions κλάση

Αντιπροσωπεύει τις επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BasePath](../../aspose.slides.export/markdownsaveoptions/basepath) { get; set; } | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. Η προεπιλογή είναι ο τρέχων κατάλογος της εφαρμογής. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται στην περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String. |
| [ExportType](../../aspose.slides.export/markdownsaveoptions/exporttype) { get; set; } | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι `TextOnly`. |
| [Flavor](../../aspose.slides.export/markdownsaveoptions/flavor) { get; set; } | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι `Multi-markdown`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ του gradient. Ανάγνωση/εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [HandleRepeatedSpaces](../../aspose.slides.export/markdownsaveoptions/handlerepeatedspaces) { get; set; } |  |
| [ImagesSaveFolderName](../../aspose.slides.export/markdownsaveoptions/imagessavefoldername) { get; set; } | Καθορίζει το όνομα φακέλου για την αποθήκευση των εικόνων. Η προεπιλογή είναι `Images`. |
| [NewLineType](../../aspose.slides.export/markdownsaveoptions/newlinetype) { get; set; } | Καθορίζει αν το δημιουργημένο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). Η προεπιλογή είναι `Unix`. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο callback για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RemoveEmptyLines](../../aspose.slides.export/markdownsaveoptions/removeemptylines) { get; set; } | Αν οριστεί σε `true`, αφαιρεί κενές ή μόνο με κενά γραμμές από το τελικό έξοδο Markdown. Η προεπιλογή είναι `false`. |
| [ShowComments](../../aspose.slides.export/markdownsaveoptions/showcomments) { get; set; } | Καθορίζει αν το δημιουργημένο έγγραφο θα εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι `false`. |
| [ShowHiddenSlides](../../aspose.slides.export/markdownsaveoptions/showhiddenslides) { get; set; } | Καθορίζει αν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυμμένες διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [ShowSlideNumber](../../aspose.slides.export/markdownsaveoptions/showslidenumber) { get; set; } | Καθορίζει αν το δημιουργημένο έγγραφο θα εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει αν θα παραληφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlideNumberFormat](../../aspose.slides.export/markdownsaveoptions/slidenumberformat) { get; set; } | Ανακτά ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το σύμβολο κράτησης θέσης \"{0}\", το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: \"# Slide {0}\" θα παράγει \"# Slide 1\", \"# Slide 2\", κ.λπ. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Ανακτά ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Παραδείγματα

Example:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions
    {
        ShowHiddenSlides = true,
        ShowSlideNumber = true,
        Flavor = Flavor.Github,
        ExportType = MarkdownExportType.Sequential,
        NewLineType = NewLineType.Windows
    };
    
    pres.Save("doc.md", new[] { 1, 2, 3, 4, 5, 6, 7, 8, 9 }, SaveFormat.Md, markdownSaveOptions);
}
```

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* σύγκροτημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->