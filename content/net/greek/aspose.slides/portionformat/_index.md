---
title: PortionFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων κειμένου. Σε αντίθεση με IPortionFormatEffectiveData./iportionformateffectivedata όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 9510
url: /el/aspose.slides/portionformat/
---
## PortionFormat κλάση

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων κειμένου. Σε αντίθεση με [`IPortionFormatEffectiveData`](../iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PortionFormat](portionformat)() | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [`PortionFormat`](../portionformat). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την απόκτηση της βασικής διασύνδεσης IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Το null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Το null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το κείμενο εκθέτη ή κάτω δείκτη. Τιμή από -100% (κάτω δείκτης) έως 100% (εκθέτης). **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος δεν είναι ορισμένο και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Διαχειριστής υπερσυνδέσμων. Μόνο για ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοπική επισήμανση ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η kerning. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας απόδειξης. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Λατινικά. Το null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περιγράμματα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Καθορίζει αν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει το βήμα διαστημάτων μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου παραλείπονται. Όταν οριστεί σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς συμβόλων. Το null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλαιοποίησης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περιγράμματα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με εφαρμογή κληρονομικότητας. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κώδικα κατακερματισμού. |

### Σχόλια

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμημάτων κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη των τιμών, έτσι σε περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν "απροσδιόριστο".

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](./geteffective) η οποία επιστρέφει μια περίπτωση [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Παραδείγματα

Το παρακάτω παράδειγμα σας δείχνει πώς να αντιστοιχίσετε τη γραμματοσειρά Λατινικά σε ένα τμήμα Paragraph μιας παρουσίασης PowerPoint.

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
// Το Aspose.Slides χρησιμοποιεί αυτούς τους ειδικούς αναγνωριστικούς (παρόμοιους με αυτούς που χρησιμοποιούνται στο PowerPoint):
// +mn-lt - Γραμματοσειρά σώματος Λατινική (Μικρή Λατινική Γραμματοσειρά)
// +mj-lt - Γραμματοσειρά τίτλου Λατινική (Μεγάλη Λατινική Γραμματοσειρά)
// +mn-ea - Γραμματοσειρά σώματος Ανατολική Ασία (Μικρή Ανατολική Ασιατική Γραμματοσειρά)
// +mj-ea - Γραμματοσειρά σώματος Ανατολική Ασία (Μικρή Ανατολική Ασιατική Γραμματοσειρά)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Δείτε επίσης

* κλάση [BasePortionFormat](../baseportionformat)
* διασύνδεση [IPortionFormat](../iportionformat)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->