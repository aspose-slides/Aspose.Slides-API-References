---
title: PortionFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με IPortionFormatEffectiveData./iportionformateffectivedata όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 9490
url: /el/aspose.slides/portionformat/
---
## PortionFormat κλάση

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης κειμένου τμημάτων. Σε αντίθεση με [`IPortionFormatEffectiveData`](../iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PortionFormat](portionformat)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`PortionFormat`](../portionformat). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την λήψη της βασικής διεπαφής IPresentationComponent. Μόνο-ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετης γραφής. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομιά. Μόνο-ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το υπερεκτεταμένο ή υποκείμενο κείμενο. Τιμή από -100% (υπόγραμμο) έως 100% (υπερκείμενο). **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομιά. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος δεν είναι ορισμένο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομιά. Μόνο-ανάγνωση [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Διαχειριστής υπερσυνδέσμων. Μόνο-ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πλοκή του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί η διαστήση γραμμάτων (kerning). **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας έλεγχου. Χρησιμοποιείται για ορθογραφικό και γραμματικό έλεγχο. Ανάγνωση/εγγραφή String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περιθώριο κειμένου. Δεν εφαρμόζεται κληρονομιά. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Καθορίζει εάν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει την αύξηση κενού μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλνονται. Όταν είναι true, επιτρέπεται ο έλεγχος. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διακριτής γραμμής (strikethrough) ενός κειμένου. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλοποίησης κειμένου. Δεν εφαρμόζεται κληρονομιά. Ανάγνωση/εγγραφή [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομιά. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Επιστέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περιγράμματα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομιά. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμοσμένη κληρονομιά. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει κωδικό κατακερματισμού. |

### Σχόλια

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομιά κατά τη λήψη τιμών, επομένως στις περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν "μη ορισμένο".

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](./geteffective) που επιστρέφει ένα στιγμιότυπο [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Παραδείγματα

Τα παρακάτω παραδείγματα δείχνουν πώς να αντιστοιχίσετε τη γραμματοσειρά Latin σε ένα τμήμα Paragraph μιας παρουσίασης PowerPoint.

```csharp
[C#]
//Δημιουργεί ένα αντικείμενο παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Το Aspose.Slides χρησιμοποιεί αυτούς τους ειδικούς αναγνωριστές (παρόμοιους με αυτούς που χρησιμοποιούνται στο PowerPoint):
// +mn-lt - Γραμματοσειρά σώματος Λατινική (Μικρή Λατινική Γραμματοσειρά)
// +mj-lt - Γραμματοσειρά επικεφαλίδας Λατινική (Κύρια Λατινική Γραμματοσειρά)
// +mn-ea - Γραμματοσειρά σώματος Ανατολική Ασία (Μικρή Ανατολική Ασιατική Γραμματοσειρά)
// +mj-ea - Γραμματοσειρά σώματος Ανατολική Ασία (Μικρή Ανατολική Ασιατική Γραμματοσειρά)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Δείτε επίσης

* κλάση [BasePortionFormat](../baseportionformat)
* διεπαφή [IPortionFormat](../iportionformat)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συστοιχία [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->