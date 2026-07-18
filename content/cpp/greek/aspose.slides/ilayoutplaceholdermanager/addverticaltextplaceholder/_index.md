---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατά το περιεχόμενο κειμένου σε κάθετη κατεύθυνση.
type: docs
weight: 40
url: /el/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) μέθοδος


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατά περιεχόμενο κειμένου σε κάθετη κατεύθυνση.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | **float** | Το πλάτος του νέου σχήματος placeholder. |
| height | **float** | Το ύψος του νέου σχήματος placeholder. |

### Return Value

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα placeholder κειμένου (Κάθετα).

## Remarks



Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder κειμένου (Κάθετα) στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ILayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)