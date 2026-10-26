---
title: Save
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.
type: docs
weight: 390
url: /el/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.

```csharp
public void Save(string fname, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή εξόδου. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με πρόσθετες επιλογές.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή εξόδου. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |
| options | ISaveOptions | Επιπλέον επιλογές μορφής. |

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή διαφορετική από Office 2007-2010 |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν τη σήμανση XAML.

```csharp
public void Save(IXamlOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | IXamlOptions | Οι επιλογές μορφής XAML. |

### Παραδείγματα

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Δείτε επίσης

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή, διατηρώντας τον αριθμό σελίδας.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | Int32[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος stream ή slides είναι null. |
| ArgumentOutOfRangeException | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδων. |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενη μορφή SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή, διατηρώντας τον αριθμό σελίδας.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | Int32[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |
| options | ISaveOptions | Επιπλέον επιλογές μορφής. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή, διατηρώντας τον αριθμό σελίδας.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή εξόδου. |
| slides | Int32[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή, διατηρώντας τον αριθμό σελίδας.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή εξόδου. |
| slides | Int32[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των δεδομένων που εξάγονται. |
| options | ISaveOptions | Επιπλέον επιλογές μορφής. |

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος stream ή slides είναι null. |
| ArgumentOutOfRangeException | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδων. |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενη μορφή SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PNG με προσαρμοσμένες διαστάσεις.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PNG με προσαρμοσμένο μέγεθος.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->