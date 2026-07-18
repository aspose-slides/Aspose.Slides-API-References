---
title: set_TransitionDuration()
second_title: Αναφορά API Aspose.Slides για C++
description: "Ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Γράψτε float. Προεπιλεγμένη τιμή: 1.0f"
type: docs
weight: 118
url: /el/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) μέθοδος

Ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Γράψτε **float**. Προεπιλεγμένη τιμή: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Παρατηρήσεις

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας προορισμού και τα χρονικά σημεία που συνδέονται με αυτή τη μετάβαση.

το παράδειγμα δείχνει την αλλαγή της διάρκειας της μετάβασης μεταξύ Zoom και διαφάνειας:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Δείτε επίσης

* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)