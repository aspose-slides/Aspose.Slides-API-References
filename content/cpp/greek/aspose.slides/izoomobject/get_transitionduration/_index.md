---
title: get_TransitionDuration()
second_title: Aspose.Slides για το API της C++
description: "Λαμβάνει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Ανάγνωση float. Προεπιλεγμένη τιμή: 1.0f"
type: docs
weight: 105
url: /el/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() method

Λαμβάνει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Ανάγνωση **float**. Προεπιλεγμένη τιμή: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Παρατηρήσεις

Αν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιήσει τη μετάβαση της διαφάνειας-προορισμού και τα χρονικά διαστήματα που σχετίζονται με αυτήν τη μετάβαση. 

Το παράδειγμα δείχνει την αλλαγή της διάρκειας της μετάβασης μεταξύ Zoom και διαφάνειας: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Δείτε επίσης

* Κλάση [IZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)