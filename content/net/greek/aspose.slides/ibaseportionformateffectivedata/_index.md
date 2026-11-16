---
title: IBasePortionFormatEffectiveData
second_title: Αναφορά API Aspose.Sildes για .NET
description: Βασική διεπαφή για αμετάβλητα αντικείμενα που περιέχουν αποτελεσματικές ιδιότητες μορφοποίησης τμημάτων κειμένου.
type: docs
weight: 5340
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
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Μόνο για ανάγνωση String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς σύνθετου script. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Μόνο για ανάγνωση [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Επιστρέφει το κείμενο ανώτερου ή κατώτερου εκθέτη. Τιμή από -100% (κατώτερος εκθέτης) έως 100% (ανώτερος εκθέτης). Μόνο για ανάγνωση Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Καθορίζει εάν η γραμματοσειρά είναι έντονη. Μόνο για ανάγνωση Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε πόντους. Μόνο για ανάγνωση Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Μόνο για ανάγνωση Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Επιστρέφει τον τύπο υπογράμμισης του κειμένου. Μόνο για ανάγνωση [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Μόνο για ανάγνωση Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή τις κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή τις κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Μόνο για ανάγνωση Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί το kerning. Μόνο για ανάγνωση Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την ανατολική γλώσσα-συγκεκριμένη κάθετη διάταξη κειμένου. Μόνο για ανάγνωση Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Επιστρέφει το Id μιας γλώσσας. Μόνο για ανάγνωση String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Επιστρέφει τις πληροφορίες γραμματοσειράς Λατινικής. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat για περίγραμμα κειμένου. Μόνο για ανάγνωση [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Καθορίζει εάν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Μόνο για ανάγνωση Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί. Μόνο για ανάγνωση Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. Μόνο για ανάγνωση Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Επιστρέφει το άθροισμα διαστήματος μεταξύ χαρακτήρων, σε πόντους. Μόνο για ανάγνωση Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Επιστρέφει τον τύπο διαγράμμισης ενός κειμένου. Μόνο για ανάγνωση [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Επιστρέφει τις πληροφορίες συμβολικής γραμματοσειράς. Μόνο για ανάγνωση [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Επιστρέφει τον τύπο κεφαλαίων κειμένου. Μόνο για ανάγνωση [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Μόνο για ανάγνωση [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Μόνο για ανάγνωση [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->