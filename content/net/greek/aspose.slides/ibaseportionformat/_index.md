---
title: IBasePortionFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με IPortionFormatEffectiveData./iportionformateffectivedata, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 5310
url: /el/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat διεπαφή

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με [`IPortionFormatEffectiveData`](../iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```csharp
public interface IBasePortionFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/Εγγραφή String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το κείμενο υπερ- ή υποδείκτη. Τιμή από -100% (υποδείκτης) έως 100% (υπερδείκτης). **float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Καθορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο ενεργοποιείται η ανταπόκριση. **float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδικής γλώσσας Ανατολικής Ασίας. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/Εγγραφή String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Λατινικών. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περιγράμματα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Καθορίζει αν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Καθορίζει αν το κείμενο δεν θα ελεγχθεί ορθογραφικά. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει το βήμα διαστήματος μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν η ορθογραφική διόρθωση είναι ενεργή για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για τα στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, η ορθογραφική διόρθωση επιτρέπεται. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |

### Παρατηρήσεις

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη τιμών, έτσι στην πλειονότητα των περιπτώσεων θα λάβετε τιμές που σημαίνουν «αορίστους». Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](../iportionformat/geteffective) η οποία επιστρέφει μια [`IPortionFormatEffectiveData`](../iportionformateffectivedata) παρουσία.

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->