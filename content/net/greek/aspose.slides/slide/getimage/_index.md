---
title: GetImage
second_title: Αναφορά API του Aspose.Sildes για .NET
description: Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.
type: docs
weight: 80
url: /el/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | Single | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | Single | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή επιστροφής

αντικείμενο IImage.

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε μικρογραφίες από παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργεί μια κλάση Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Πρόσβαση στην πρώτη διαφάνεια
    ISlide sld = pres.Slides[0];
    // Δημιουργία εικόνας πλήρους κλίμακας
    IImage bmp = sld.GetImage(1f, 1f);
    // Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε διαφάνειες σε bitmap και να αποθηκεύσετε τις εικόνες σε μορφή PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Μετατρέπει την πρώτη διαφάνεια στην παρουσίαση σε αντικείμενο Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Αποθηκεύει την εικόνα σε μορφή PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε PowerPoint PPT/PPTX σε JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Δημιουργία εικόνας πλήρους κλίμακας
		IImage bmp = sld.GetImage(1f, 1f);
		// Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε PowerPoint PPT/PPTX σε JPG με προσαρμοσμένες διαστάσεις.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Ορισμός διαστάσεων
	int desiredX = 1200;
	int desiredY = 800;
	// Λήψη κλιμακωμένων τιμών X και Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Δημιουργία εικόνας πλήρους κλίμακας
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Επιστρέφει ένα αντικείμενο Thumbnail Image (20 % του πραγματικού μεγέθους).

```csharp
public IImage GetImage()
```

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος.

```csharp
public IImage GetImage(Size imageSize)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | Size | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή επιστροφής

αντικείμενο Image.

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε διαφάνειες σε εικόνες με προσαρμοσμένα μεγέθη χρησιμοποιώντας C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Μετατρέπει την πρώτη διαφάνεια στην παρουσίαση σε Bitmap με το καθορισμένο μέγεθος
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Αποθηκεύει την εικόνα σε μορφή JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Επιστρέφει ένα αντικείμενο Thumbnail tiff image με τα καθορισμένα παραμέτρους.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | ITiffOptions | Επιλογές Tiff. |

### Τιμή επιστροφής

αντικείμενο Image.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| InvalidOperationException | Εμφανίζεται όταν options.SlideLayoutOption είναι NotesCommentsLayoutingOptions και η ιδιότητα NotesPosition παίρνει την τιμή NotesPositions.BottomFull. |

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* διασύνδεση [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Επιστρέφει ένα αντικείμενο Thumbnail Image.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | IRenderingOptions | Επιλογές απόδοσης. |

### Τιμή επιστροφής

αντικείμενο Image.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| InvalidOperationException | Εμφανίζεται όταν notesCommentsLayouting.NotesPosition παίρνει την τιμή NotesPositions.BottomFull |

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* διασύνδεση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | IRenderingOptions | Επιλογές απόδοσης. |
| scaleX | Single | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | Single | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή επιστροφής

αντικείμενα Bitmap.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| InvalidOperationException | Εμφανίζεται όταν notesCommentsLayouting.NotesPosition παίρνει την τιμή NotesPositions.BottomFull |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε διαφάνειες με σημειώσεις και σχόλια σε εικόνες χρησιμοποιώντας C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Δημιουργία των επιλογών απόδοσης
    IRenderingOptions options = new RenderingOptions();
    // Δημιουργία επιλογών διάταξης σημειώσεων και σχολίων
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Ορίζει τη θέση των σημειώσεων στη σελίδα
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Ορίζει τη θέση των σχολίων στη σελίδα
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Ορίζει το πλάτος της περιοχής εξόδου σχολίων
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Ορίζει το χρώμα για την περιοχή σχολίων
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Ορίζει τις επιλογές διάταξης για την απόδοση
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Μετατρέπει την πρώτη διαφάνεια της παρουσίασης σε αντικείμενο IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Αποθηκεύει την εικόνα σε μορφή GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* διασύνδεση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | IRenderingOptions | Επιλογές απόδοσης. |
| imageSize | Size | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή επιστροφής

αντικείμενο Image.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| InvalidOperationException | Εμφανίζεται όταν options.SlideLayoutOption είναι NotesCommentsLayoutingOptions και η ιδιότητα NotesPosition παίρνει την τιμή NotesPositions.BottomFull. |

### Δείτε επίσης

* διασύνδεση [IImage](../../iimage)
* διασύνδεση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* κλάση [Slide](../../slide)
* χώρο ονομάτων [Aspose.Slides](../../slide)
* συναρμολόγηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->