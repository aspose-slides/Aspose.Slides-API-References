---
title: AddOnlineImagePlaceholder()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να φιλοξενήσει μια online εικόνα.
type: docs
weight: 118
url: /el/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) μέθοδος


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να φιλοξενήσει μια online εικόνα.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | **float** | Το πλάτος του νέου σχήματος placeholder. |
| height | **float** | Το ύψος του νέου σχήματος placeholder. |

### Τιμή επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με έναν Online Image placeholder.

## Παρατηρήσεις



Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα Online Image placeholder στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)