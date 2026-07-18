---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides για C++ Αναφορά API
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης τμήματος κειμένου.
type: docs
weight: 3342
url: /el/aspose.slides/iportionformateffectivedata/
---
## IPortionFormatEffectiveData κλάση

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης τμήματος κειμένου.

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Μόνο για ανάγνωση [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Επιστρέφει το αναγνωριστικό σελιδοδείκτη. Μόνο για ανάγνωση [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετης γραφής. Μόνο για ανάγνωση [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Μόνο για ανάγνωση [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | Επιστρέφει τις ιδιότητες κειμένου [EffectFormat](../effectformat/). Μόνο για ανάγνωση [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | Επιστρέφει το κείμενο υπερ- ή υπο- δείκτη. Τιμή από -100% (υπο-δείκτης) έως 100% (υπέρ-δείκτης). Μόνο για ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | Επιστρέφει τις ιδιότητες κειμένου [FillFormat](../fillformat/). Μόνο για ανάγνωση [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | Καθορίζει αν η γραμματοσειρά είναι έντονη. Μόνο για ανάγνωση **bool**. |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε σημείο. Μόνο για ανάγνωση **float**. |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Μόνο για ανάγνωση **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | Επιστρέφει τον τύπο υπογράμμισης του κειμένου. Μόνο για ανάγνωση [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Μόνο για ανάγνωση [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | Επιστρέφει τον υπερσύνδεσμο ορισμένο για κλικ ποντικιού. Μόνο για ανάγνωση [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | Επιστρέφει τον υπερσύνδεσμο ορισμένο για πέρασμα ποντικιού. Μόνο για ανάγνωση [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες [FillFormat](../fillformat/) ή κληρονομεί τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Μόνο για ανάγνωση **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες [LineFormat](../lineformat/) ή κληρονομεί τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Μόνο για ανάγνωση **bool**. |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η kerning. Μόνο για ανάγνωση **float**. |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κάθετη διάταξη κειμένου ειδική για ανατολικές γλώσσες. Μόνο για ανάγνωση **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | Επιστρέφει το Id μιας γλώσσας. Μόνο για ανάγνωση [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | Επιστρέφει τις πληροφορίες γραμματοσειράς Λατίνας. Μόνο για ανάγνωση [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) για περιγράμματα κειμένου. Μόνο για ανάγνωση [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | Καθορίζει αν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Μόνο για ανάγνωση **bool**. |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί. Μόνο για ανάγνωση **bool**. |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Μόνο για ανάγνωση **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | Επιστρέφει την αύξηση του διαστήματος μεταξύ χαρακτήρων, σε σημείο. Μόνο για ανάγνωση **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | Επιστρέφει τον τύπο διαγράμματος κειμένου. Μόνο για ανάγνωση [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Μόνο για ανάγνωση [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | Επιστρέφει τον τύπο κεφαλαιοποίησης κειμένου. Μόνο για ανάγνωση [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | Επιστρέφει τις ιδιότητες γραμμής υπογράμμισης [FillFormat](../fillformat/). Μόνο για ανάγνωση [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) που χρησιμοποιούνται για περίγραμμα γραμμής υπογράμμισης. Μόνο για ανάγνωση [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος του C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικός με τον τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() του C# για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικειμενικό sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος του C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος του C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή typeof([System.Object](../../system/object/)) του C#. |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() του C# για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Αυτή η διασύνδεση χρησιμοποιείται μαζί με τη διασύνδεση [IPortionFormat](../iportionformat/) για την επιστροφή αποτελεσματικών τιμών μορφοποίησης με εφαρμοσμένη κληρονομικότητα.

## Δείτε επίσης

* Κλάση [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)