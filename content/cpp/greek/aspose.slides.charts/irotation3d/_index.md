---
title: IRotation3D
second_title: Αναφορά API Aspose.Slides για C++
description: Αναπαριστά την περιστροφή 3D ενός διαγράμματος.
type: docs
weight: 1171
url: /el/aspose.slides.charts/irotation3d/
---
## IRotation3D κλάση

Αναπαριστά την περιστροφή 3D ενός διαγράμματος.

```cpp
class IRotation3D : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητών σημείων σε στυλ C# όπου δύο NaN θεωρούνται ίσοι παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ισότιμο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητών σημείων σε στυλ C# όπου δύο NaN θεωρούνται ίσοι παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ισότιμο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Επιστρέφει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Διαβάζει **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Διαβάζει **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Επιστρέφει την τιμή προοπτικής (γωνία πεδίου θέασης) για 3D διαγράμματα (μεταξύ 0 και 100). Αγνοείται εάν η ιδιότητα RightAngleAxes είναι αληθής. Διαβάζει **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Καθορίζει εάν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται προοπτικά. Με άλλα λόγια, καθορίζει εάν οι γωνίες των αξόνων του διαγράμματος είναι ανεξάρτητες από την περιστροφή ή την ανύψωση του διαγράμματος. Διαβάζει **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Επιστρέφει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3D διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.157 rotX (X Rotation) στο ECMA-376 και με την επιλογή "Y Rotation" στο PowerPoint 2007+. Διαβάζει **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Επιστρέφει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3D διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.158 rotY (Y Rotation) στο ECMA-376 και με την επιλογή "X Rotation" στο PowerPoint 2007+. Διαβάζει **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της C# [Object.GetHashCode()](../../system/object/gethashcode/) μεθόδου. Ενεργοποιεί την κατασκευή κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της C# [System.Object.GetType()](../../system/object/gettype/) κλήσης. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του C# τελεστή 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) μεθόδου. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγράφου. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινών αναφορών κατά τη συγκεκριμένη τιμή. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Εγγράφει **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Εγγράφει **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Ορίζει την τιμή προοπτικής (γωνία πεδίου θέασης) για 3D διαγράμματα (μεταξύ 0 και 100). Αγνοείται εάν η ιδιότητα RightAngleAxes είναι αληθής. Εγγράφει **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Καθορίζει εάν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται προοπτικά. Με άλλα λόγια, καθορίζει εάν οι γωνίες των αξόνων του διαγράμματος είναι ανεξάρτητες από την περιστροφή ή την ανύψωση του διαγράμματος. Εγγράφει **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Ορίζει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3D διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.157 rotX (X Rotation) στο ECMA-376 και με την επιλογή "Y Rotation" στο PowerPoint 2007+. Εγγράφει **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Ορίζει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3D διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.158 rotY (Y Rotation) στο ECMA-376 και με την επιλογή "X Rotation" στο PowerPoint 2007+. Εγγράφει **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατό λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)