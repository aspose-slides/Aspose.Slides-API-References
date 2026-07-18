---
title: get_OperatorEmulator()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Operator Emulator. Όταν true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος λειτουργός και κληρονομούν τις ιδιότητες ενός λειτουργού. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να χρησιμεύσει ως σημείο για διακοπή γραμμής και μπορεί να ευθυγραμμιστεί με άλλους λειτουργούς. Operator Emulators χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να δημιουργήσουν έναν λειτουργό, όπως το '=='. Προεπιλεγμένη τιμή: false"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() μέθοδος


Operator Emulator. Όταν true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος λειτουργός και κληρονομούν τις ιδιότητες ενός λειτουργού. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να χρησιμεύσει ως σημείο διακοπής γραμμής και μπορεί να ευθυγραμμιστεί με άλλους λειτουργούς. Operator Emulators χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να σχηματίσουν έναν λειτουργό, όπως το '=='. Προεπιλεγμένη τιμή: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Δείτε επίσης

* Κλάση [MathBox](../)
* Ονομαχώρος [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)