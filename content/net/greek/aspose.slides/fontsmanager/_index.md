---
title: FontsManager
second_title: Aspose.Sildes για .NET API Αναφορά
description: Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.
type: docs
weight: 4960
url: /el/aspose.slides/fontsmanager/
---
## FontsManager κλάση

Διαχειρίζεται γραμματοσειρές σε όλη την παρουσίαση.

```csharp
public class FontsManager : IFontsManager
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Αναπαριστά τη συλλογή ενός χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Ανάγνωση/Εγγραφή [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Αντικαταστάσεις γραμματοσειρών που χρησιμοποιούνται κατά την απόδοση. Ανάγνωση/Εγγραφή [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |
| [PreferRegisteredFontsOverEmbedded](../../aspose.slides/fontsmanager/preferregisteredfontsoverembedded) { get; set; } | Καθορίζει αν οι καταγεγραμμένες γραμματοσειρές πρέπει να προτιμώνται αντί των ενσωματωμένων γραμματοσειρών με το ίδιο όνομα και στυλ. Όταν είναι ενεργοποιημένο, οι αντίστοιχες ενσωματωμένες γραμματοσειρές αντικαθίστανται προσωρινά με τις καταγεγραμμένες γραμματοσειρές κατά την εξαγωγή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά. Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι κατοχυρωμένες. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο μηχάνημα. Μπορεί να εξαπολυθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι null ή η γραμματοσειρά είναι ήδη ενσωματωμένη. |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Προσθέτει την ενσωματωμένη γραμματοσειρά. Λάβετε υπόψη ότι όταν αντιγράφετε οποιεσδήποτε γραμματοσειρές, οι περισσότερες είναι κατοχυρωμένες. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο μηχάνημα. Μπορεί να εξαπολυθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι null ή η γραμματοσειρά είναι ήδη ενσωματωμένη. |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Επιστρέφει τις γραμματοσειρές που είναι ενσωματωμένες στην παρουσίαση. |
| [GetFontBytes](../../aspose.slides/fontsmanager/getfontbytes)(IFontData, FontStyleType) | Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα συγκεκριμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [GetFontEmbeddingLevel](../../aspose.slides/fontsmanager/getfontembeddinglevel)(byte[], string) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δοσμένο πίνακα byte και το όνομα της γραμματοσειράς. |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions)() | Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions_1)(int[]) | Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των συγκεκριμένων διαφανειών. |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Αφαιρεί την ενσωματωμένη γραμματοσειρά. |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [`FontSubstRule`](../fontsubstrule). |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [`FontSubstRule`](../fontsubstrule). |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont)(IFontData, IFontData) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ενσωματωμένες γραμματοσειρές στην Παρουσίαση PowerPoint.

```csharp
[C#]
// Φόρτωση παρουσίασης
using (Presentation presentation = new Presentation("Fonts.pptx"))
{
	// Φόρτωση πηγής γραμματοσειράς προς αντικατάσταση
	IFontData sourceFont = new FontData("Arial");
	IFontData[] allFonts = presentation.FontsManager.GetFonts();
	IFontData[] embeddedFonts = presentation.FontsManager.GetEmbeddedFonts();
	foreach (IFontData font in allFonts)
	{
		if (!embeddedFonts.Contains(font))
		{
			presentation.FontsManager.AddEmbeddedFont(font, EmbedFontCharacters.All);
		}
	}
	// Αποθήκευση της παρουσίασης
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διασύνδεση [IFontsManager](../ifontsmanager)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* σύστημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->