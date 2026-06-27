---
title: PortionFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων κειμένου. Σε αντίθεση με IPortionFormatEffectiveData./iportionformateffectivedata όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 9470
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
| [PortionFormat](portionformat)() | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [`PortionFormat`](../portionformat). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την πρόσβαση στη βασική διεπαφή IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς πολύπλοκου σεναρίου. Null σημαίνει ότι η γραμματοσειρά είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το υπερ- ή υπο-σκορ το κειμένου. Τιμή από -100% (υποσκορ) έως 100% (υπερσκορ). **float.NaN** σημαίνει ότι η τιμή είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος είναι ακαθόριστο και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Καθορίζει εάν η γραμματοσειρά είναι πλάγια (itallic). Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Διαχειριστής υπερσυνδέσμων. Μόνο για ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο ενεργοποιείται η εξομάλυνση. **float.NaN** σημαίνει ότι η τιμή είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κάθετη διάταξη κειμένου ειδικά για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας διόρθωσης. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περιγράμμιση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Καθορίζει εάν το κείμενο δεν πρέπει να υποβληθεί σε έλεγχο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει το πρόσθετο διάστημα μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι έλεγχοι ορθογραφίας για τα στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλογή είναι `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι ακαθόριστη και θα κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλαιοποίησης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περιγράμμιση της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμογή κληρονομικότητας. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κώδικα κατακερματισμού. |

### Σχόλια

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμημάτων κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη των τιμών, έτσι στη μεγαλύτερη μέρος των περιπτώσεων θα λάβετε τιμές που σημαίνουν «απροσδιόριστο».

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](./geteffective) που επιστρέφει ένα [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να εκχωρήσετε τη λατινική γραμματοσειρά σε ένα τμήμα της Paragraph σε μια παρουσίαση PowerPoint.

```csharp
[C#]
//Δημιουργήστε ένα αντικείμενο παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
//Το Aspose.Slides χρησιμοποιεί αυτά τα ειδικά αναγνωριστικά (παρόμοια με αυτά που χρησιμοποιούνται στο PowerPoint):
// +mn-lt - Γραμματοσειρά σώματος Latin (Μικρή γραμματοσειρά Latin)
// +mj-lt - Γραμματοσειρά κεφαλίδας Latin (Κύρια γραμματοσειρά Latin)
// +mn-ea - Γραμματοσειρά σώματος East Asian (Μικρή γραμματοσειρά East Asian)
// +mj-ea - Γραμματοσειρά σώματος East Asian (Μικρή γραμματοσειρά East Asian)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Δείτε επίσης

* κλάση [BasePortionFormat](../baseportionformat)
* διεπαφή [IPortionFormat](../iportionformat)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->