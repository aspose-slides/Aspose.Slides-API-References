---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes για .NET API Αναφορά
description: Βασική διασύνδεση για αμετάβλητα αντικείμενα που περιέχουν ιδιότητες μορφοποίησης αποτελεσματικών τμημάτων κειμένου.
type: docs
weight: 5300
url: /el/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData διασύνδεση

Βασική διασύνδεση για αμετάβλητα αντικείμενα που περιέχουν ιδιότητες μορφοποίησης αποτελεσματικών τμημάτων κειμένου.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Μόνο για ανάγνωση String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετου σεναρίου. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Μόνο για ανάγνωση [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Επιστρέφει το υπερ- ή υπο-σκριπτικό κείμενο. Τιμή από -100% (υποσκριπτικό) έως 100% (υπερσκριπτικό). Μόνο για ανάγνωση Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Μόνο για ανάγνωση Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε σημεία. Μόνο για ανάγνωση Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Μόνο για ανάγνωση Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Επιστρέφει τον τύπο υπογράμμισης του κειμένου. Μόνο για ανάγνωση [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Μόνο για ανάγνωση Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Μόνο για ανάγνωση Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο θα ενεργοποιηθεί το kerning. Μόνο για ανάγνωση Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κάθετη διάταξη κειμένου ειδική για ανατολικές γλώσσες. Μόνο για ανάγνωση Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Επιστρέφει το Id μιας γλώσσας. Μόνο για ανάγνωση String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς Λατινικού. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περίγραμμα κειμένου. Μόνο για ανάγνωση [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Καθορίζει εάν το ύψος του κειμένου πρέπει να ομαλοποιηθεί. Μόνο για ανάγνωση Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Μόνο για ανάγνωση Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. Μόνο για ανάγνωση Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Επιστρέφει την αύξηση διαστολής μεταξύ χαρακτήρων, σε σημεία. Μόνο για ανάγνωση Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Επιστρέφει τον τύπο διαγράμμισης κειμένου. Μόνο για ανάγνωση [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Επιστρέφει τον τύπο κεφαλαιοποίησης κειμένου. Μόνο για ανάγνωση [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Μόνο για ανάγνωση [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Μόνο για ανάγνωση [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->