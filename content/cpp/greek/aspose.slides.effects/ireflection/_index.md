---
title: IReflection
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεύει ένα εφέ ανάκλασης.
type: docs
weight: 937
url: /el/aspose.slides.effects/ireflection/
---
## IReflection κλάση

Αντιπροσωπεύει ένα εφέ ανάκλασης.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) ακτίνα. Διαβάζει **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Κατεύθυνση ανάκλασης. Διαβάζει **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Απόσταση ανάκλασης. Διαβάζει **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας διαβάθμισης alpha) της τιμής alpha λήξης (ποσοστά). Διαβάζει **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Διαφάνεια λήξης ανάκλασης. (ποσοστά). Διαβάζει **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Καθορίζει την κατεύθυνση μετατόπισης της ανάκλασης. (γωνία). Διαβάζει **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Στοίχιση ορθογωνίου. Διαβάζει [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Καθορίζει αν η ανάκλαση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. Διαβάζει **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανάστροφη. (ποσοστά) Διαβάζει **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Καθορίζει τον κατακόρυφο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανάστροφη. (ποσοστά) Διαβάζει **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Καθορίζει την οριζόντια γωνία παραμόρφωσης. Διαβάζει **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Καθορίζει την κατακόρυφη γωνία παραμόρφωσης. Διαβάζει **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Καθορίζει τη θέση έναρξης (κατά μήκος της κλίμακας διαβάθμισης alpha) της τιμής alpha έναρξης (ποσοστά). Διαβάζει **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Διαφάνεια έναρξης ανάκλασης. (ποσοστά). Διαβάζει **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Αποκτά τα αποτελεσματικά δεδομένα με την εφαρμοσμένη κληρονομικότητα. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην ουσία, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην ουσία, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) ακτίνα. Εγγραφή **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Κατεύθυνση ανάκλασης. Εγγραφή **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Απόσταση ανάκλασης. Εγγραφή **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας διαβάθμισης alpha) της τιμής alpha λήξης (ποσοστά). Εγγραφή **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Διαφάνεια λήξης ανάκλασης. (ποσοστά). Εγγραφή **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Καθορίζει την κατεύθυνση μετατόπισης της ανάκλασης. (γωνία). Εγγραφή **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Στοίχιση ορθογωνίου. Εγγραφή [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Καθορίζει αν η ανάκλαση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. Εγγραφή **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανάστροφη. (ποσοστά) Εγγραφή **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Καθορίζει τον κατακόρυφο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανάστροφη. (ποσοστά) Εγγραφή **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Καθορίζει την οριζόντια γωνία παραμόρφωσης. Εγγραφή **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Καθορίζει την κατακόρυφη γωνία παραμόρφωσης. Εγγραφή **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Καθορίζει τη θέση έναρξης (κατά μήκος της κλίμακας διαβάθμισης alpha) της τιμής alpha έναρξης (ποσοστά). Εγγραφή **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Διαφάνεια έναρξης ανάκλασης. (ποσοστά). Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα του προτύπου ως αδυναμικό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινό μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτικούς ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτικούς ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτικούς ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτικούς ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IImageTransformOperation](../iimagetransformoperation/)
* Κλάση [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Χώρος ονομάτων [Aspose::Slides::Effects](../)
* Βιβλιοθήκη [Aspose.Slides](../../)