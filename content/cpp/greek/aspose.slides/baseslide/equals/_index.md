---
title: Equals()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν τα δύο στιγμιότυπα IBaseSlide είναι ίσα. Η επιστρεφόμενη τιμή υπολογίζεται με βάση τη δομή της διαφάνειας και το στατικό περιεχόμενο. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστών, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στην Date Placeholder.
type: docs
weight: 170
url: /el/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) μέθοδος

Καθορίζει εάν τα δύο [IBaseSlide](../../ibaseslide/) στιγμιότυπα είναι ίσα. Η επιστρεφόμενη τιμή υπολογίζεται με βάση τη δομή της διαφάνειας και το στατικό περιεχόμενο. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστικών, π.χ. SlideId και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | Το [IBaseSlide](../../ibaseslide/) για σύγκριση με την τρέχουσα [IBaseSlide](../../ibaseslide/). |

### Return Value

**true** εάν το καθορισμένο [IBaseSlide](../../ibaseslide/) είναι ίσο με την τρέχουσα [IBaseSlide](../../ibaseslide/)· διαφορετικά, **false**.

## Remarks

Το παρακάτω παράδειγμα δείχνει πώς να συγκρίνετε δύο διαφάνειες.
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## See Also

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IBaseSlide](../../ibaseslide/)
* Κλάση [BaseSlide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)