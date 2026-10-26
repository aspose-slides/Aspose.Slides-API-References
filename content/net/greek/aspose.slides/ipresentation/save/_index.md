---
title: Save
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.
type: docs
weight: 380
url: /el/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

```csharp
public void Save(string fname, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Stream εξόδου. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και πρόσθετες επιλογές.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |
| options | ISaveOptions | Πρόσθετες επιλογές μορφής. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και πρόσθετες επιλογές.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Stream εξόδου. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |
| options | ISaveOptions | Πρόσθετες επιλογές μορφής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή εκτός Office 2007-2010 |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | Int32[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος stream ή slides είναι null. |
| ArgumentOutOfRangeException | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | Int32[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |
| options | ISaveOptions | Πρόσθετες επιλογές μορφής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος stream ή slides είναι null. |
| ArgumentOutOfRangeException | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Stream εξόδου. |
| slides | Int32[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος stream ή slides είναι null. |
| ArgumentOutOfRangeException | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Stream εξόδου. |
| slides | Int32[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | SaveFormat | Μορφή των εξαγόμενων δεδομένων. |
| options | ISaveOptions | Πρόσθετες επιλογές μορφής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος stream ή slides είναι null. |
| ArgumentOutOfRangeException | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Δείτε επίσης

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML.

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
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->