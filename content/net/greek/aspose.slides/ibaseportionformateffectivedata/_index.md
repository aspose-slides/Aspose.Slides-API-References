---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes για .NET Αναφορά API
description: Βασική διεπαφή για αμετάβλητα αντικείμενα που περιέχουν ιδιότητες μορφοποίησης τμημάτων κειμένου.
type: docs
weight: 5320
url: /el/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData διεπαφή

Βασική διεπαφή για αμετάβλητα αντικείμενα που περιέχουν αποτελεσματικές ιδιότητες μορφοποίησης τμήματος κειμένου.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Μόνο-ανάγνωση String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετου script. Μόνο-ανάγνωση [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Μόνο-ανάγνωση [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Μόνο-ανάγνωση [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Επιστρέφει το υπερ- ή υπο-συνδρομητικό κείμενο. Τιμή από -100% (υποσύνδρομη) έως 100% (υπερσύνδρομη). Μόνο-ανάγνωση Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Μόνο-ανάγνωση [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Καθορίζει αν η γραμματοσειρά είναι έντονη. Μόνο-ανάγνωση Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε σημεία. Μόνο-ανάγνωση Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Καθορίζει αν η γραμματοσειρά είναι πλάγια. Μόνο-ανάγνωση Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Επιστρέφει τον τύπο υπογράμμισης του κειμένου. Μόνο-ανάγνωση [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για τον επισήμανση κειμένου. Μόνο-ανάγνωση Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Μόνο-ανάγνωση Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Μόνο-ανάγνωση Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο θα ενεργοποιηθεί το kerning. Μόνο-ανάγνωση Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν τη διάταξη κατακόρυφου κειμένου ειδική για ανατολική γλώσσα. Μόνο-ανάγνωση Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Επιστρέφει το Id μιας γλώσσας. Μόνο-ανάγνωση String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Επιστρέφει τις πληροφορίες της λατινικής γραμματοσειράς. Μόνο-ανάγνωση [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. Μόνο-ανάγνωση [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Καθορίζει αν το ύψος του κειμένου πρέπει να είναι κανονικοποιημένο. Μόνο-ανάγνωση Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Καθορίζει αν το κείμενο δεν πρέπει να ελέγχεται ορθογραφικά. Μόνο-ανάγνωση Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Καθορίζει αν το έξυπνο ετικέτα πρέπει να καθαριστεί. Μόνο-ανάγνωση Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Επιστρέφει την αύξηση του διαστήματος μεταξύ χαρακτήρων, σε σημεία. Μόνο-ανάγνωση Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Επιστρέφει τον τύπο διαγραφής κειμένου (strikethrough). Μόνο-ανάγνωση [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Μόνο-ανάγνωση [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Επιστρέφει τον τύπο κεφαλαίων κειμένου. Μόνο-ανάγνωση [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Μόνο-ανάγνωση [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της γραμμής υπογράμμισης. Μόνο-ανάγνωση [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->