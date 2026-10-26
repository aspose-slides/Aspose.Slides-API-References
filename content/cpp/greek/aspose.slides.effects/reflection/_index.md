---
title: Reflection
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεύει ένα εφέ Reflection.
type: docs
weight: 1067
url: /el/aspose.slides.effects/reflection/
---
## Κλάση Reflection

Αντιπροσωπεύει ένα [Reflection](./) εφέ.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Καθορίζει εάν το συγκεκριμένο [Reflection](./) είναι ίσο με το τρέχον [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) ακτίνα. Ανάγνωση **double**. |
| **float** [get_Direction](./get_direction/)() override | Κατεύθυνση του ανακλαστικού. Ανάγνωση **float**. |
| **double** [get_Distance](./get_distance/)() override | Απόσταση του ανακλαστικού. Ανάγνωση **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας αλφα-gradient) της τιμής αλφα λήξης (ποσοστά). Ανάγνωση **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Διαφάνεια λήξης ανακλαστικού. (ποσοστά). Ανάγνωση **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Καθορίζει την κατεύθυνση μετατόπισης του ανακλαστικού. (γωνία). Ανάγνωση **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονικό [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Μόνο-ανάγνωση [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Στοίχιση ορθογωνίου. Ανάγνωση [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Καθορίζει εάν το ανακλαστικό πρέπει να περιστρέφεται μαζί με το σχήμα εάν το σχήμα περιστρέφεται. Ανάγνωση **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αντιστροφή. (ποσοστά) Ανάγνωση **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Καθορίζει τον κάθετο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αντιστροφή. (ποσοστά) Ανάγνωση **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Καθορίζει τη γωνία οριζόντιας κλίσης. Ανάγνωση **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Καθορίζει τη γωνία κάθετης κλίσης. Ανάγνωση **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Καθορίζει τη θέση εκκίνησης (κατά μήκος της κλίμακας αλφα-gradient) της τιμής αλφα έναρξης (ποσοστά). Ανάγνωση **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Διαφάνεια εκκίνησης ανακλαστικού. (ποσοστά). Ανάγνωση **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Έκδοση. Μόνο-ανάγνωση **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ [Reflection](./) με την κληρονομικότητα εφαρμοσμένη. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα του C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορικά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) ακτίνα. Εγγραφή **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Κατεύθυνση του ανακλαστικού. Εγγραφή **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Απόσταση του ανακλαστικού. Εγγραφή **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας αλφα-gradient) της τιμής αλφα λήξης (ποσοστά). Εγγραφή **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Διαφάνεια λήξης ανακλαστικού. (ποσοστά). Εγγραφή **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Καθορίζει την κατεύθυνση μετατόπισης του ανακλαστικού. (γωνία). Εγγραφή **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Στοίχιση ορθογωνίου. Εγγραφή [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Καθορίζει εάν το ανακλαστικό πρέπει να περιστρέφεται μαζί με το σχήμα εάν το σχήμα περιστρέφεται. Εγγραφή **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αντιστροφή. (ποσοστά) Εγγραφή **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Καθορίζει τον κάθετο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αντιστροφή. (ποσοστά) Εγγραφή **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Καθορίζει τη γωνία οριζόντιας κλίσης. Εγγραφή **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Καθορίζει τη γωνία κάθετης κλίσης. Εγγραφή **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Καθορίζει τη θέση εκκίνησης (κατά μήκος της κλίμακας αλφα-gradient) της τιμής αλφα έναρξης (ποσοστά). Εγγραφή **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Διαφάνεια εκκίνησης ανακλαστικού. (ποσοστά). Εγγραφή **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IReflection](../ireflection/)
* Κλάση [IVisualEffect](../ivisualeffect/)
* Κλάση [IPVIObject](../../aspose.slides/ipviobject/)
* Χώρος ονομάτων [Aspose::Slides::Effects](../)
* Βιβλιοθήκη [Aspose.Slides](../../)