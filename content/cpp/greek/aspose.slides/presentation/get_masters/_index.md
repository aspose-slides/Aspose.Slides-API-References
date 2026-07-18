---
title: get_Masters()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια λίστα με όλες τις κύριες διαφάνειες που έχουν οριστεί στην παρουσίαση. Μόνο για ανάγνωση IMasterSlideCollection.
type: docs
weight: 118
url: /el/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() μέθοδος


Επιστρέφει μια λίστα με όλες τις κύριες διαφάνειες που έχουν οριστεί στην παρουσίαση. Μόνο για ανάγνωση [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Σχόλια


Τα παρακάτω παραδείγματα δείχνουν πώς να προσθέσετε [Images](../../images/) στο Master [Slides](../../) του PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 Τα παρακάτω παραδείγματα δείχνουν πώς να αλλάξετε το χρώμα φόντου της κύριας διαφάνειας του PowerPoint [Presentation](../). 
```cpp
// Δημιουργήστε μια αντικειμενοποίηση της κλάσης Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>();

// Ορίστε το χρώμα φόντου του Master ISlide σε Πράσινο δάσους
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Αποθηκεύστε την παρουσίαση στο δίσκο
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 Τα παρακάτω παραδείγματα δείχνουν πώς να προσθέσετε διάταξη διαφάνειας στο PowerPoint [Presentation](../). 
```cpp
// Δημιουργία της κλάσης Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Προσπάθεια αναζήτησης ανά τύπο διαφάνειας διάταξης
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Η περίπτωση όταν μια παρουσίαση δεν περιέχει ορισμένους τύπους διατάξεων.
    // Το αρχείο παρουσίασης περιέχει μόνο τύπους διατάξεων Blank και Custom.
    // Ωστόσο, οι διαφάνειες διάταξης με τύπους Custom έχουν διαφορετικά ονόματα διαφάνειας,
    // όπως "Title", "Title and Content", κλπ. Και είναι δυνατόν να χρησιμοποιηθούν αυτά
    // ονόματα για την επιλογή διαφάνειας διάταξης.
    // Επίσης είναι δυνατόν να χρησιμοποιηθεί το σύνολο των τύπων placeholder σχήματος. Για παράδειγμα,
    // Η διαφάνεια Title πρέπει να έχει μόνο τύπο placeholder Title, κλπ.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// Προσθήκη κενής διαφάνειας με την προστιθέμενη διαφάνεια διάταξης
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Αποθήκευση παρουσίασης
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)