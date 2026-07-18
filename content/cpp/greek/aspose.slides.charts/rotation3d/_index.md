---
title: Rotation3D
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά την 3Δ περιστροφή ενός διαγράμματος.
type: docs
weight: 1327
url: /el/aspose.slides.charts/rotation3d/
---
## Rotation3D κλάση

Αναπαριστά την 3Δ περιστροφή ενός διαγράμματος.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Επιστρέφει το βάθος ενός 3Δ διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Ανάγνωση **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Καθορίζει το ύψος ενός 3-Δ διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Ανάγνωση **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Επιστρέφει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3Δ διαγράμματα (μεταξύ 0 και 240). Αγνοείται εάν η τιμή ιδιότητας RightAngleAxes είναι true. Ανάγνωση **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Καθορίζει αν οι άξονες του διαγράμματος είναι ορθογώνιοι, αντί να σχεδιάζονται με προοπτική. Με άλλα λόγια, καθορίζει αν οι γωνίες των αξόνων του διαγράμματος είναι ανεξάρτητες από την περιστροφή ή την ανύψωση του διαγράμματος. Ανάγνωση **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Επιστρέφει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3Δ διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.157 rotX (X Rotation) στο ECMA-376 και με την επιλογή "Y Rotation" στο PowerPoint 2007+. Ανάγνωση **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Επιστρέφει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3Δ διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.158 rotY (Y Rotation) στο ECMA-376 και με την επιλογή "X Rotation" στο PowerPoint 2007+. Ανάγνωση **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την εντολή lock() της C#. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλάσεων-παραγώγων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλάσεων-παραγώγων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Ορίζει το βάθος ενός 3Δ διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Εγγραφή **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Καθορίζει το ύψος ενός 3-Δ διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Εγγραφή **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3Δ διαγράμματα (μεταξύ 0 και 240). Αγνοείται εάν η τιμή ιδιότητας RightAngleAxes είναι true. Εγγραφή **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Καθορίζει αν οι άξονες του διαγράμματος είναι ορθογώνιοι, αντί να σχεδιάζονται με προοπτική. Με άλλα λόγια, καθορίζει αν οι γωνίες των αξόνων του διαγράμματος είναι ανεξάρτητες από την περιστροφή ή την ανύψωση του διαγράμματος. Εγγραφή **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Ορίζει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3Δ διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.157 rotX (X Rotation) στο ECMA-376 και με την επιλογή "Y Rotation" στο PowerPoint 2007+. Εγγραφή **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Ορίζει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3Δ διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.158 rotY (Y Rotation) στο ECMA-376 και με την επιλογή "X Rotation" στο PowerPoint 2007+. Εγγραφή **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή lock() της C# για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IRotation3D](../irotation3d/)
* Κλάση [IDOMObject](../../aspose.slides/idomobject/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)