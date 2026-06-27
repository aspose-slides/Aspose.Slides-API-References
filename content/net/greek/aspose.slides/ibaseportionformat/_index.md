---
title: IBasePortionFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων κειμένου. Σε αντίθεση με IPortionFormatEffectiveData./iportionformateffectivedata, όλες οι ιδιότητες αυτής της κλάσης είναι επεξεργάσιμες.
type: docs
weight: 5290
url: /el/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat διεπαφή

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public interface IBasePortionFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/γραφή String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο-ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το εκθέτω ή υπογεγραμμένο κείμενο. Τιμή από -100% (υποσημείο) έως 100% (εκθέτω). **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος δεν είναι ορισμένο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο-ανάγνωση [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή τις κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή τις κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο θα ενεργοποιηθεί το kerning. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν τη κατακόρυφη διάταξη κειμένου που είναι ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας επιβεβαίωσης. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/γραφή String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Καθορίζει αν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, επιτρέπεται ο έλεγχος ορθογραφίας. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διαγράμματος κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/γραφή [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλοποίησης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/γραφή [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |

### Παρατηρήσεις

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και την τροποποίηση των ιδιοτήτων μορφοποίησης τμημάτων κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά την ανάγνωση τιμών, έτσι για την πλειονότητα των περιπτώσεων θα λαμβάνετε τιμές που σημαίνουν «ακαθόριστο».

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](../iportionformat/geteffective) η οποία επιστρέφει ένα [`IPortionFormatEffectiveData`](../iportionformateffectivedata) αντίγραφο.

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->