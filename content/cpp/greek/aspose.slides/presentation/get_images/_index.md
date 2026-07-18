---
title: get_Images()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο για ανάγνωση IImageCollection.
type: docs
weight: 209
url: /el/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() μέθοδος

Returns the collection of all images in the presentation. Read-only [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Παρατηρήσεις

The following examples shows how to add image as BLOB in PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// δημιουργεί μια νέα παρουσίαση στην οποία θα προστεθεί η εικόνα.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Ας προσθέσουμε την εικόνα στην παρουσίαση - επιλέγουμε τη συμπεριφορά KeepLocked επειδή
// ΔΕΝ σκοπεύουμε να έχουμε πρόσβαση στο αρχείο "largeImage.png" file.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Αποθηκεύει την παρουσίαση. Ενώ μια μεγάλη παρουσίαση εξάγεται, η κατανάλωση μνήμης
// παραμένει χαμηλή κατά τη διάρκεια του κύκλου ζωής του αντικειμένου pres.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 The following examples add a hyperlink to an image in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Προσθέτει εικόνα στην παρουσίαση
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Δημιουργεί πλαίσιο εικόνας στη διαφάνεια 1 βάσει της προηγουμένως προστιθέμενης εικόνας
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImageCollection](../../iimagecollection/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)