---
title: Equals()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν οι δύο εμφανίσεις IBaseSlide είναι ίσες. Η τιμή επιστροφής υπολογίζεται με βάση τη δομή της διαφάνειας και το στατικό περιεχόμενο. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η animation και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις τιμές μοναδικών ταυτοποιητών, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Placeholder Ημερομηνίας.
type: docs
weight: 183
url: /el/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) method

Καθορίζει εάν οι δύο [IBaseSlide](../) εμφανίσεις είναι ίσες. Η τιμή επιστροφής υπολογίζεται με βάση τη δομή της διαφάνειας και το στατικό περιεχόμενο. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, οι animation και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις τιμές μοναδικών ταυτοποιητών, π.χ. SlideId, και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας στο Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | Το [IBaseSlide](../) για σύγκριση με το τρέχον [IBaseSlide](../). |

### Τιμή Επιστροφής

**true** αν η συγκεκριμένη [IBaseSlide](../) είναι ίση με το τρέχον [IBaseSlide](../)· διαφορετικά, **false**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)