---
title: BasePortionFormat
second_title: Aspose.Slides για C++ Αναφορά API
description: Κοινές ιδιότητες διαμόρφωσης τμημάτων κειμένου.
type: docs
weight: 144
url: /el/aspose.slides/baseportionformat/
---
## BasePortionFormat κλάση

Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σήμανση C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Διαβάστε [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Επιστρέφει τις ιδιότητες του κειμένου [EffectFormat](../effectformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Επιστρέφει το κείμενο σε εκθέτη ή υπογεγραμμένο. Τιμή από -100% (υπογεγραμμένο) έως 100% (εκθέτη). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Επιστρέφει τις ιδιότητες του κειμένου [FillFormat](../fillformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Επιστρέφει το ύψος γραμματοσειράς ενός τμήματος. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Επιστρέφει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες [FillFormat](../fillformat/) ή κληρονομεί από τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Διαβάστε [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες [LineFormat](../lineformat/) ή κληρονομεί από τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η γνώση (kerning). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν τη συγκεκριμένη για ανατολικές γλώσσες κατακόρυφη διάταξη κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Επιστρέφει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Διαβάστε [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Επιστρέφει τις πληροφορίες γραμματοσειράς Λατινικής. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Καθορίζει εάν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει τον γονέα [IPresentationComponent](../ipresentationcomponent/). Μόνο ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Επιστρέφει την αύξηση διαστήματος μεταξύ χαρακτήρων. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Επιστρέφει μια τιμή που δείχνει εάν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Επιστρέφει τον τύπο διακριτής γραμμής κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Επιστρέφει τον τύπο κεφαλοποίησης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Επιστρέφει τις ιδιότητες της γραμμής υπογράμμισης [FillFormat](../fillformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Επιστρέφει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Επιστρέφει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων στις υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων στις υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει την αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Ορίζει το Id μιας εναλλακτικής γλώσσας. Γράψτε [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Ορίζει το κείμενο σε εκθέτη ή υπογεγραμμένο. Τιμή από -100% (υπογεγραμμένο) έως 100% (εκθέτη). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Ορίζει το ύψος γραμματοσειράς ενός τμήματος. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες [FillFormat](../fillformat/) ή κληρονομεί τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Γράψτε [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες [LineFormat](../lineformat/) ή κληρονομεί τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Γράψτε [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί το kerning. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν τη συγκεκριμένη για ανατολικές γλώσσες κατακόρυφη διάταξη κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Γράψτε [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες γραμματοσειράς Λατινικής. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Ορίζει την αύξηση διαστήματος μεταξύ χαρακτήρων. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Ορίζει τον τύπο διακριτής γραμμής κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Ορίζει τον τύπο κεφαλοποίησης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Επιστρέφει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δημιουργία C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IBasePortionFormat](../ibaseportionformat/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Library [Aspose.Slides](../../)