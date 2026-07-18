---
title: get_TransitionDuration()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αποκτά τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Διαβάζει float. Προεπιλεγμένη τιμή: 1.0f"
type: docs
weight: 105
url: /el/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() μέθοδος


Αποκτά τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Διαβάζει **float**. Προεπιλεγμένη τιμή: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Σχόλια


Εάν δεν έχει καθοριστεί (TransitionDur = 0), θα χρησιμοποιήσει τη μετάβαση της προορισμού διαφάνειας και τους χρόνους που σχετίζονται με αυτή τη μετάβαση. 

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