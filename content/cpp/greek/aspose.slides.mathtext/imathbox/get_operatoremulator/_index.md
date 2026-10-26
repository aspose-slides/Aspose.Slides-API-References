---
title: get_OperatorEmulator()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Operator Emulator. Όταν είναι true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας μοναδικός τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να χρησιμεύσει ως σημείο για αλλαγή γραμμής και μπορεί να ευθυγραμμιστεί με άλλους τελεστές. Operator Emulators χρησιμοποιούνται συχνά όταν ένα ή περισσότερα γλύφια συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '=='. Προεπιλεγμένη τιμή: false"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() μέθοδος

Operator Emulator. Όταν είναι true, το κουτί και το περιεχόμενό του συμπεριφέρονται ως ένας μόνο τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να χρησιμεύσει ως σημείο για αλλαγή γραμμής και μπορεί να ευθυγραμμιστεί με άλλους τελεστές. Operator Emulators χρησιμοποιούνται συχνά όταν ένα ή περισσότερα γλύφια συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '=='. Προεπιλεγμένη τιμή: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Σχόλια

Παράδειγμα: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Δείτε επίσης

* Κλάση [IMathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)