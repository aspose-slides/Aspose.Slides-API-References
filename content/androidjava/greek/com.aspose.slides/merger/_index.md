---
title: Merger
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει μια ομάδα μεθόδων για τη συγχώνευση παρουσιάσεων PowerPoint του ίδιου μορφότυπου σε ένα αρχείο.
type: docs
url: /el/com.aspose.slides/merger/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Merger
```

Αντιπροσωπεύει μια ομάδα μεθόδων για τη συγχώνευση παρουσιάσεων PowerPoint του ίδιου μορφότυπου σε ένα αρχείο.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Συγχωνεύει πολλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ένας πίνακας με τα ονόματα των αρχείων παρουσίασης εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου του τελικού συγχωνευμένου αρχείου παρουσίασης. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Συγχωνεύει πολλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ένας πίνακας με τα ονόματα των αρχείων παρουσίασης εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου του τελικού συγχωνευμένου αρχείου παρουσίασης. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Οι πρόσθετες επιλογές που ορίζουν πώς θα αποθηκευτεί η συγχωνευμένη παρουσίαση. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Συγχωνεύει πολλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ένας πίνακας με τα ονόματα των αρχείων παρουσίασης εισόδου. |
| outputStream | java.io.OutputStream | Η ροή εξόδου. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Συγχωνεύει πολλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ένας πίνακας με τα ονόματα των αρχείων παρουσίασης εισόδου. |
| outputStream | java.io.OutputStream | Η ροή εξόδου. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Οι πρόσθετες επιλογές που ορίζουν πώς θα αποθηκευτεί η συγχωνευμένη παρουσίαση. |