---
title: FontsManager
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.
type: docs
weight: 989
url: /el/aspose.slides/fontsmanager/
---
## FontsManager κλάση

Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.

```cpp
class FontsManager : public Aspose::Slides::IFontsManager
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [AddEmbeddedFont](./addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Προσθέτει την ενσωματωμένη γραμματοσειρά |
| void [AddEmbeddedFont](./addembeddedfont/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Προσθέτει την ενσωματωμένη γραμματοσειρά |
| virtual void [AddEmbeddedFont](../ifontsmanager/addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | Προσθέτει την ενσωματωμένη γραμματοσειρά. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/)\> [get_FontFallBackRule](./get_fontfallbackrule/)(**int32_t**) override | Επιστρέφει τον κανόνα στο συγκεκριμένο δείκτη για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Μόνο για ανάγνωση [Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\> [get_FontFallBackRulesCollection](./get_fontfallbackrulescollection/)() override | Αναπαριστά τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Ανάγνωση [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\> [get_FontSubstRule](./get_fontsubstrule/)(**int32_t**) override | Επιστρέφει τον κανόνα αντικατάστασης γραμματοσειράς στο συγκεκριμένο δείκτη που θα χρησιμοποιηθεί κατά την απόδοση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\> [get_FontSubstRuleList](./get_fontsubstrulelist/)() override | Αντικαταστάσεις γραμματοσειρών για χρήση κατά την απόδοση. Ανάγνωση [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetEmbeddedFonts](./getembeddedfonts/)() override | Επιστρέφει τις γραμματοσειρές που έχουν ενσωματωθεί στην παρουσίαση |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](./getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::FontStyleType](../fontstyletype/)) override | Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα συγκεκριμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](../ifontsmanager/getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [FontStyleType](../fontstyletype/)) | Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα συγκεκριμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [Aspose::Slides::EmbeddingLevel](../embeddinglevel/) [GetFontEmbeddingLevel](./getfontembeddinglevel/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/)) override | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δοσμένο πίνακα byte και το όνομα της γραμματοσειράς. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetFonts](./getfonts/)() override | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)() override | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)([System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των συγκεκριμένων διαφανειών. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποτύπων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποτύπων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Σύγκριση αναφοράς αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [RemoveEmbeddedFont](./removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Αφαιρέι την ενσωματωμένη γραμματοσειρά |
| virtual void [RemoveEmbeddedFont](../ifontsmanager/removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Αφαιρέι την ενσωματωμένη γραμματοσειρά |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Αντικαθιστόζει τη γραμματοσειρά στην παρουσίαση |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\>) override | Αντικαθιστόζει τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [FontSubstRule](../fontsubstrule/) |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Αντικαθιστόζει τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή [FontSubstRule](../fontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Αντικαθιστόζει τη γραμματοσειρά στην παρουσίαση |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\>) | Αντικαθιστόζει τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [IFontSubstRule](../ifontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Αντικαθιστόζει τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή [IFontSubstRule](../ifontsubstrule/) |
| void [set_FontFallBackRulesCollection](./set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) override | Αναπαριστά τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Εγγραφή [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual void [set_FontFallBackRulesCollection](../ifontsmanager/set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) | Αναπαριστά τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Εγγραφή [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| void [set_FontSubstRuleList](./set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Αντικαταστάσεις γραμματοσειρών για χρήση κατά την απόδοση. Εγγραφή [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [set_FontSubstRuleList](../ifontsmanager/set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Αντικαταστάσεις γραμματοσειρών για χρήση κατά την απόδοση. Εγγραφή [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ενσωματωμένες γραμματοσειρές στο PowerPoint [Presentation](../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Αποθήκευση της παρουσίασης
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IFontsManager](../ifontsmanager/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)