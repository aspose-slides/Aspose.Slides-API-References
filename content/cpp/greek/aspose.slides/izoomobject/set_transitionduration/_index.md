---
title: set_TransitionDuration()
second_title: Aspose.Slides για το C++ API
description: "Ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Γράψτε float. Προεπιλεγμένη τιμή: 1.0f"
type: docs
weight: 118
url: /el/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) μέθοδος

Ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Γράψτε **float**. Προεπιλεγμένη τιμή: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Παρατηρήσεις

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιήσει τη μετάβαση της διαφάνειας προορισμού και τα χρονικά δεδομένα που σχετίζονται με αυτή τη μετάβαση.

Το παράδειγμα δείχνει την αλλαγή της διάρκειας της μετάβασης μεταξύ Zoom και διαφάνειας:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Δείτε επίσης

* Κλάση [IZoomObject](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)