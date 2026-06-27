---
title: BasePortionFormat
second_title: Αναφορά API Aspose.Sildes για .NET
description: Κοινές ιδιότητες μορφοποίησης τμημάτων κειμένου.
type: docs
weight: 950
url: /el/asprise.slides/baseportionformat/
---
## BasePortionFormat κλάση

Common text portion formatting properties.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την λήψη της βασικής διεπαφής IPresentationComponent. Μόνο ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat κειμένου. Δεν εφαρμόζεται κληρονόμηση. Μόνο ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Επιστρέφει ή ορίζει το ανώγενο ή υπογερό κείμενο. Τιμή από -100% (υπογερό) έως 100% (ανώγενο). **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat κειμένου. Δεν εφαρμόζεται κληρονόμηση. Μόνο ανάγνωση [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **float.NaN** σημαίνει ότι το ύψος δεν είναι ορισμένο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Καθορίζει εάν η γραμματοσειρά είναι πλαγιαστή. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης κειμένου. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονόμηση. Μόνο ανάγνωση [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο θα ενεργοποιηθεί το kerning. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου που είναι ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Λατινικού. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονόμηση. Μόνο ανάγνωση [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Καθορίζει εάν το ύψος κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. **float.NaN** σημαίνει ότι η τιμή δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου παραλείπονται. Όταν οριστεί σε true, επιτρέπεται ο έλεγχος ορθογραφίας. Η προεπιλεγμένη τιμή είναι `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο διαγράμματος κειμένου. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν είναι ορισμένη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/εγγραφή [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονόμηση. Μόνο ανάγνωση [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για την περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονόμηση. Μόνο ανάγνωση [`ILineFormat`](../ilineformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει κωδικό hash. |

### Δείτε επίσης

* κλάση [PVIObject](../pviobject)
* διασύνδεση [IBasePortionFormat](../ibaseportionformat)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->