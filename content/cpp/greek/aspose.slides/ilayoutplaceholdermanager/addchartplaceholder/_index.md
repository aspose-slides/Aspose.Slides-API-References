---
title: AddChartPlaceholder()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να φιλοξενήσει ένα διάγραμμα.
type: docs
weight: 66
url: /el/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) μέθοδος


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να φιλοξενήσει ένα Chart.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | **float** | Το πλάτος του νέου σχήματος placeholder. |
| height | **float** | Το ύψος του νέου σχήματος placeholder. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα placeholder Chart.
## Σχόλια



Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder Chart στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)