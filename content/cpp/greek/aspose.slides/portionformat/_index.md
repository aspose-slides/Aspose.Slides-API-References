---
title: PortionFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με IPortionFormatEffectiveData, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 4811
url: /el/aspose.slides/portionformat/
---
## PortionFormat κλάση


Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με [IPortionFormatEffectiveData](../iportionformateffectivedata/), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με το καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Επιστρέφει το αναγνωριστικό σελιδοδείκτη. Διαβάστε [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Επιστρέφει τις ιδιότητες κειμένου [EffectFormat](../effectformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Επιστρέφει το ανώματο ή το κάτω δείκτη κειμένου. Τιμή από -100% (κάτω δείκτης) έως 100% (ανώματο). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Επιστρέφει τις ιδιότητες κειμένου [FillFormat](../fillformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Επιστρέφει το ύψος γραμματοσειράς ενός τμήματος. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι το ύψος δεν είναι ορισμένο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Επιστρέφει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Διαχειριστής υπερσυνδέσμων. Μόνο ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για υπέρπωση ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες [FillFormat](../fillformat/) ή κληρονομεί από τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Διαβάστε [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες [LineFormat](../lineformat/) ή κληρονομεί από τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί το kerning. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδικού για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Επιστρέφει το Id μιας γλώσσας διόρθωσης. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Διαβάστε [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Επιστρέφει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονικό [IPresentationComponent](../ipresentationcomponent/). Μόνο ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Καθορίζει αν το κείμενο δεν πρέπει να διορθωθεί. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Καθορίζει αν το smart tag πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Επιστρέφει το αυξήσιμο διαστήματος μεταξύ χαρακτήρων. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Λαμβάνει μια τιμή που υποδεικνύει αν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Επιστρέφει τον τύπο διαγράμματος κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Επιστρέφει τον τύπο κεφαλοποιήσεων κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Επιστρέφει τις ιδιότητες γραμμής υπογράμμισης [FillFormat](../fillformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με εφαρμοσμένη κληρονομικότητα. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| [PortionFormat](./portionformat/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Ορίζει το Id μιας εναλλακτικής γλώσσας. Εγγραφή [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Ορίζει το αναγνωριστικό σελιδοδείκτη. Εγγραφή [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Ορίζει το ανώματο ή το κάτω δείκτη κειμένου. Τιμή από -100% (κάτω δείκτης) έως 100% (ανώματο). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Ορίζει το ύψος γραμματοσειράς ενός τμήματος. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι το ύψος δεν είναι ορισμένο και πρέπει να κληρονομηθεί από το Master. Εγγραφή **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για υπέρπωση ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες [FillFormat](../fillformat/) ή κληρονομεί από τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες [LineFormat](../lineformat/) ή κληρονομεί από τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδικού για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Ορίζει το Id μιας γλώσσας διόρθωσης. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Εγγραφή [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Καθορίζει αν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Καθορίζει αν το κείμενο δεν πρέπει να διορθωθεί. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Καθορίζει αν το smart tag πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Ορίζει το αυξήσιμο διαστήματος μεταξύ χαρακτήρων. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει αν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, επιτρέπεται ο έλεγχος. Η προεπιλεγμένη τιμή είναι **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Ορίζει τον τύπο διαγράμματος κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Εγγραφή [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Ορίζει τον τύπο κεφαλοποιήσεων κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Εγγραφή [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε υποδοχείς σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη διατύπωση C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Σχόλια

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά την ανάγνωση τιμών, έτσι για την πλειονότητα των περιπτώσεων θα λάβετε τιμές που σημαίνουν "μη ορισμένη".

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [PortionFormat::GetEffective](./geteffective/) που επιστρέφει μια παρουσία [IPortionFormatEffectiveData](../iportionformateffectivedata/).

Τα παρακάτω παραδείγματα δείχνουν πώς να εκχωρήσετε τη γραμματοσειρά Latin σε ένα τμήμα [Paragraph](../paragraph/) του PowerPoint [Presentation](../presentation/).

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Το Aspose.Slides χρησιμοποιεί αυτούς τους ειδικούς ταυτοποιητές (παρόμοιους με αυτούς που χρησιμοποιούνται στο PowerPoint):
// +mn-lt - Γραμματοσειρά σώματος Latin (Μικρή γραμματοσειρά Latin)
// +mj-lt - Γραμματοσειρά κεφαλίδας Latin (Κύρια γραμματοσειρά Latin)
// +mn-ea - Γραμματοσειρά σώματος Ανατολικής Ασίας (Μικρή γραμματοσειρά Ανατολικής Ασίας)
// +mj-ea - Γραμματοσειρά σώματος Ανατολικής Ασίας (Μικρή γραμματοσειρά Ανατολικής Ασίας)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Δείτε επίσης

* Κλάση [BasePortionFormat](../baseportionformat/)
* Κλάση [IPortionFormat](../iportionformat/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)