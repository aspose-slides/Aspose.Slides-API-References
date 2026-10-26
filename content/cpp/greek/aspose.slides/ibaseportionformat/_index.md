---
title: IBasePortionFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Αντίθετα με το IPortionFormatEffectiveData, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 1457
url: /el/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat κλάση


This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Διαβάστε [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Επιστρέφει τις ιδιότητες κειμένου [EffectFormat](../effectformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Επιστρέφει το εκθέτη ή το υπογεγραμμένο κείμενο. Τιμή από -100% (υπογεγραμμένο) έως 100% (εκθέτη). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Επιστρέφει τις ιδιότητες κειμένου [FillFormat](../fillformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Επιστρέφει το ύψος γραμματοσειράς ενός τμήματος. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Επιστρέφει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Επιστρέφει το χρώμα που χρησιμοποιείται για τον φωτισμό κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες [FillFormat](../fillformat/) ή τις κληρονομεί από τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Διαβάστε [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες [LineFormat](../lineformat/) ή τις κληρονομεί από τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί το kerning. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την ανατολική, ειδική για τη γλώσσα, κάθετη διάταξη κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Επιστρέφει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Διαβάστε [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Επιστρέφει τις πληροφορίες γραμματοσειράς Λατινικών. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Επιστρέφει το προσαυξητικό διάστημα μεταξύ χαρακτήρων. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Λαμβάνει μια τιμή που υποδεικνύει αν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλνονται. Όταν οριστεί σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Επιστρέφει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Διαβάστε [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Επιστρέφει τον τύπο κεφαλαίων κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Επιστρέφει τις ιδιότητες γραμμής υπογράμμισης [FillFormat](../fillformat/). Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Επιστρέφει τις ιδιότητες [LineFormat](../lineformat/) που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογίας με τη μέθοδο C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία με την κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία με τον τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία με τη μέθοδο C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Ορίζει το Id μιας εναλλακτικής γλώσσας. Γράψτε [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Ορίζει το εκθέτη ή το υπογεγραμμένο κείμενο. Τιμή από -100% (υπογεγραμμένο) έως 100% (εκθέτη). **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Ορίζει το ύψος γραμματοσειράς ενός τμήματος. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες [FillFormat](../fillformat/) ή τις κληρονομεί από τις ιδιότητες [FillFormat](../fillformat/) του κειμένου. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες [LineFormat](../lineformat/) ή τις κληρονομεί από τις ιδιότητες [LineFormat](../lineformat/) του κειμένου. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί το kerning. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την ανατολική, ειδική για τη γλώσσα, κάθετη διάταξη κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Γράψτε [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ορίζει τις πληροφορίες γραμματοσειράς Λατινικών. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Ορίζει το προσαυξητικό διάστημα μεταξύ χαρακτήρων. **std::numeric_limits<float>::quiet_NaN()** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει αν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλνονται. Όταν οριστεί σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Γράψτε [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Ορίζει τον τύπο κεφαλαίων κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογίας με τη μέθοδο C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις


This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [IPortionFormat::GetEffective](../iportionformat/geteffective/) method which returns a [IPortionFormatEffectiveData](../iportionformateffectivedata/) instance.

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)