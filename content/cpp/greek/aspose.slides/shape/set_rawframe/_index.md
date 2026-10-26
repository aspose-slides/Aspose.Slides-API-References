---
title: set_RawFrame()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος. Γράψτε IShapeFrame.
type: docs
weight: 53
url: /el/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) μέθοδος

Ορίζει τις ιδιότητες του ακατέργαστου πλαισίου σχήματος. Γράψτε [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Σχόλια

Ο κώδικας που προσπαθεί να εκχωρήσει ακαθόριστο πλαίσιο στο [IShape::set_Frame](../../ishape/set_frame/) δεν έχει νόημα στη γενική περίπτωση (ιδιαίτερα όταν ο γονέας [GroupShape](../../groupshape/) είναι πολλαπλά ενσωματωμένος σε άλλα GroupShape). Για παράδειγμα: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 ή 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Τέτοιος κώδικας μπορεί να οδηγήσει σε ασαφείς καταστάσεις. Συνεπώς έχουν προστεθεί περιορισμοί για τη χρήση ακαθόριστων τιμών για [IShape::set_Frame](../../ishape/set_frame/). Οι τιμές των x, y, width, height, flipH, flipV και rotationAngle πρέπει να ορίζονται (να μην είναι std::numeric_limits<float>::quiet_NaN() ή [NullableBool::NotDefined](../../nullablebool/)). Το παραπάνω παράδειγμα κώδικα τώρα ρίχνει εξαίρεση ArgumentException. Αυτό ισχύει για τις ακόλουθες περιπτώσεις χρήσης: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // δεν μπορεί να είναι ακαθόριστο

SharedPtr<IShapeCollection> shapes = ...;
// οι παράμετροι x, y, width, height δεν μπορούν να είναι std::numeric_limits<float>::quiet_NaN():
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

Ωστόσο, ένα πλαίσιο για τη μέθοδο [IShape::set_RawFrame](../../ishape/set_rawframe/) μπορεί να είναι ακαθόριστο. Αυτό έχει νόημα όταν το σχήμα είναι συνδεδεμένο με placeholder. Τότε οι ακαθόριστες τιμές του πλαισίου σχήματος αντικαθίστανται από το γονικό placeholder σχήμα. Εάν δεν υπάρχει γονικό placeholder σχήμα για αυτό το σχήμα, τότε το σχήμα χρησιμοποιεί προεπιλεγμένες τιμές όταν υπολογίζει το αποτελεσματικό πλαίσιο βάσει του [IShape::get_RawFrame](../../ishape/get_rawframe/). Οι προεπιλεγμένες τιμές είναι 0 και [NullableBool::False](../../nullablebool/) για x, y, width, height, flipH, flipV και rotationAngle. Για παράδειγμα: 
```cpp
SharedPtr<IShape> shape = ...; // το σχήμα είναι συνδεδεμένο με placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // τώρα το σχήμα κληρονομεί τις τιμές x, y, height, flipH, flipV από το placeholder και αντικαθιστά width=100 και rotationAngle=0.
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShapeFrame](../../ishapeframe/)
* Κλάση [Shape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)