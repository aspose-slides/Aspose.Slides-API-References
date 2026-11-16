---
title: ChartPortionFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων διαγράμματος που χρησιμοποιούνται σε διαγράμματα. Σε αντίθεση με IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 1440
url: /el/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat κλάση

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων διαγραμμάτων που χρησιμοποιούνται σε διαγράμματα. Σε αντίθεση με [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή θέτει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/Εγγραφή String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την λήψη της βασικής διεπαφής IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή θέτει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή θέτει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Επιστρέφει ή θέτει το κείμενο ανώτερης ή κατώτερης δείκτη. Τιμή από -100% (κατώτερη) έως 100% (ανώτερη). **float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Επιστρέφει ή θέτει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος είναι απροσδιόριστο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Επιστρέφει ή θέτει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή θέτει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η ρύθμιση kerning. **float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Καθορίζει εάν οι αριθμοί θα αγνοούν τη συγκεκριμένη για την Ανατολική γλώσσα διάταξη του κάθετου κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Επιστρέφει ή θέτει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/Εγγραφή String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Επιστρέφει ή θέτει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Καθορίζει εάν το ύψος του κειμένου πρέπει να ομαλοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Επιστρέφει ή θέτει την αύξηση του διακριτού διαστήματος μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Λαμβάνει ή θέτει μια τιμή που υποδεικνύει εάν είναι ενεργοποιημένος ο έλεγχος ορθογραφίας για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή θέτει τον τύπο διακριτής γραμμής κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Επιστρέφει ή θέτει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Επιστρέφει ή θέτει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κωδικό κατακερματισμού. |

### Παρατηρήσεις

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη τιμών, έτσι στην πλειονότητα των περιπτώσεων θα λαμβάνετε τιμές που σημαίνουν «απροσδιόριστο».

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομισμένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](../../aspose.slides/portionformat/geteffective) που επιστρέφει ένα παράδειγμα [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Δείτε επίσης

* κλάση [BasePortionFormat](../../aspose.slides/baseportionformat)
* διασύνδεση [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->