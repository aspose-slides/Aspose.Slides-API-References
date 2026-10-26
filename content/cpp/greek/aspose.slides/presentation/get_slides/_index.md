---
title: get_Slides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει έναν κατάλογο με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση ISlideCollection.
type: docs
weight: 53
url: /el/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() μέθοδος

Επιστρέφει έναν κατάλογο με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Παρατηρήσεις

```cpp
// Δημιουργήστε την κλάση Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε το χρώμα φόντου των διαφανειών του PowerPoint [Presentation](../). 
```cpp
// Δημιουργήστε την κλάση Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Ορίστε το φόντο με εικόνα
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Ορίστε την εικόνα
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Προσθέστε την εικόνα στη συλλογή εικόνων της παρουσίασης
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Αποθηκεύστε την παρουσίαση στο δίσκο
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε την εικόνα φόντου των διαφανειών του PowerPoint [Presentation](../). 
```cpp
// Δημιουργήστε την κλάση Presentation για να φορτώσετε το πηγαίο αρχείο παρουσίασης
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Εφαρμόστε μετάβαση τύπου circle στη διαφάνεια 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Εφαρμόστε μετάβαση τύπου comb στη διαφάνεια 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Αποθηκεύστε την παρουσίαση στο δίσκο
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε μετάβαση διαφάνειας [Presentation](../). 
```cpp
// Δημιουργήστε την κλάση Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Εφαρμόστε μετάβαση τύπου circle στη διαφάνεια 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Ορίστε τον χρόνο μετάβασης στα 3 δευτερόλεπτα
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Εφαρμόστε μετάβαση τύπου comb στη διαφάνεια 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Ορίστε τον χρόνο μετάβασης στα 5 δευτερόλεπτα
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Εφαρμόστε μετάβαση τύπου zoom στη διαφάνεια 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Ορίστε τον χρόνο μετάβασης στα 7 δευτερόλεπτα
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Αποθηκεύστε την παρουσίαση στο δίσκο
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε προχωρημένη μετάβαση διαφάνειας. 

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlideCollection](../../islidecollection/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)