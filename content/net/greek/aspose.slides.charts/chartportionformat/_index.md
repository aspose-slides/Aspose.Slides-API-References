---
title: ChartPortionFormat
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων διαγράμματος που χρησιμοποιούνται σε διαγράμματα. Σε αντίθεση με IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 1410
url: /el/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat κλάση

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων διαγράμματος που χρησιμοποιούνται στα διαγράμματα. Σε αντίθεση με [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IPresentationComponent. Μόνο ανάγνωση [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το κείμενο επισύψιμου ή υποσυγγράμμισης. Τιμή από -100% (υποσυγγράμμιση) έως 100% (επισύψιμη). **float.NaN** σημαίνει ότι η τιμή δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος δεν είναι καθορισμένο και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης διαθέτει τις δικές του ιδιότητες FillFormat ή τις κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης διαθέτει τις δικές του ιδιότητες LineFormat ή τις κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η διακριτική απόσταση (kerning). **float.NaN** σημαίνει ότι η τιμή δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου που είναι ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας διόρθωσης. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Λατινική. Null σημαίνει ότι η γραμματοσειρά δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Καθορίζει αν το ύψος του κειμένου πρέπει να ομαλοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Καθορίζει αν το κείμενο δεν πρέπει να υποβληθεί σε διόρθωση. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει το βήμα μεταξύχαρακτήρων. **float.NaN** σημαίνει ότι η τιμή δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, επιτρέπεται ο έλεγχος ορθογραφίας. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν είναι καθορισμένη και πρέπει να κληρονομείται από το Master. Ανάγνωση/εγγραφή [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το συγκεκριμένο αντικείμενο. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει κωδικό κατατεμαχισμού. |

### Παρατηρήσεις

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμημάτων κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη των τιμών, έτσι στην πλειονότητα των περιπτώσεων θα λάβετε τιμές που σημαίνουν "μη καθορισμένο".

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένης της κληρονομίας, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](../../aspose.slides/portionformat/geteffective) η οποία επιστρέφει μια περίπτωση [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Δείτε επίσης

* κλάση [BasePortionFormat](../../aspose.slides/baseportionformat)
* διεπαφή [IChartPortionFormat](../ichartportionformat)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->