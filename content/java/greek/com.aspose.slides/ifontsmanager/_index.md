---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Διαχειρίζεται γραμματοσειρές σε ολόκληρη την παρουσίαση.
type: docs
url: /el/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Διαχειρίζεται γραμματοσειρές σε ολόκληρη την παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Αντικαταστάσεις γραμματοσειρών που χρησιμοποιούνται κατά την απόδοση Ανάγνωση/εγγραφή [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Αντικαταστάσεις γραμματοσειρών που χρησιμοποιούνται κατά την απόδοση Ανάγνωση/εγγραφή [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack του χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack του χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| [getSubstitutions()](#getSubstitutions--) | Λαμβάνει πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Λαμβάνει πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των συγκεκριμένων διαφανειών. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Επιστρέφει τις γραμματοσειρές ενσωματωμένες στην παρουσίαση |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Αφαίρεση της ενσωματωμένης γραμματοσειράς |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Προσθήκη της ενσωματωμένης γραμματοσειράς. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Προσθέτει την ενσωματωμένη γραμματοσειρά |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Αντικατάσταση γραμματοσειράς στην παρουσίαση |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα της γραμματοσειράς για συγκεκριμένο στυλ και δεδομένα γραμματοσειράς. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δοσμένο πίνακα byte και το όνομα της γραμματοσειράς. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Αντικαταστάσεις γραμματοσειρών που χρησιμοποιούνται κατά την απόδοση Ανάγνωση/εγγραφή [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Επιστρέφει:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Αντικαταστάσεις γραμματοσειρών που χρησιμοποιούνται κατά την απόδοση Ανάγνωση/εγγραφή [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack του χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // προσθήκη κανόνων στη συλλογή
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ή
>      // αρχικοποίηση νέου αντικειμένου της συλλογής κανόνων
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // προσθήκη κανόνων στη συλλογή
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // και αντικατάσταση της υπάρχουσας συλλογής με τη νέα στο FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack του χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // προσθήκη κανόνων στη συλλογή
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ή 
>      // αρχικοποίηση νέου αντικειμένου της συλλογής κανόνων
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // προσθήκη κανόνων στη συλλογή
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // και αντικατάσταση της υπάρχουσας συλλογής με τη νέα στο FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```


Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση

**Επιστρέφει:**
com.aspose.slides.IFontData[] - Ένα σύνολο γραμματοσειρών
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Λαμβάνει πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν στην απόδοση της παρουσίασης.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Συλλογή όλων των αντικαταστάσεων γραμματοσειρών [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Λαμβάνει πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των συγκεκριμένων διαφανειών.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slides | int[] | Πίνακας δεικτών διαφανειών για τις οποίες θα ανακτηθούν πληροφορίες αντικατάστασης γραμματοσειρών, ξεκινώντας από το 1. |

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Μια συλλογή όλων των αντικαταστάσεων γραμματοσειρών ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) για τις συγκεκριμένες διαφάνειες.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Επιστρέφει τις γραμματοσειρές ενσωματωμένες στην παρουσίαση

**Επιστρέφει:**
com.aspose.slides.IFontData[] - Ενσωματωμένες γραμματοσειρές IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


Αφαιρεί την ενσωματωμένη γραμματοσειρά

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Αντικείμενο δεδομένων γραμματοσειράς [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Προσθέτει την ενσωματωμένη γραμματοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Αντικείμενο δεδομένων γραμματοσειράς [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Κανόνας ενσωμάτωσης γραμματοσειράς [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Να έχετε υπόψη ότι όταν αντιγράφετε γραμματοσειρές, οι περισσότεροι τύποι είναι προστατευόμενοι από πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια χρήσης μιας γραμματοσειράς και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο μηχάνημα. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Προσθέτει την ενσωματωμένη γραμματοσειρά

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | byte[] | Δεδομένα γραμματοσειράς  byte[]  |
| embedFontRule | int | Κανόνας ενσωμάτωσης γραμματοσειράς [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Να έχετε υπόψη ότι όταν προσθέτετε γραμματοσειρές, οι περισσότεροι τύποι είναι προστατευόμενοι από πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια χρήσης μιας γραμματοσειράς και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλο μηχάνημα. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


Αντικατάσταση γραμματοσειράς στην παρουσίαση

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Πηγή γραμματοσειράς |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Προορισμός γραμματοσειράς |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Πληροφορίες αντικατάστασης γραμματοσειράς |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


Αντικατάσταση γραμματοσειράς στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Συλλογή πληροφοριών αντικατάστασης γραμματοσειράς |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα της γραμματοσειράς για συγκεκριμένο στυλ και δεδομένα γραμματοσειράς.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Ανάκτηση όλων των γραμματοσειρών που χρησιμοποιούνται στην παρουσίαση
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Λήψη του πίνακα byte που αντιπροσωπεύει το κανονικό στυλ της πρώτης γραμματοσειράς στην παρουσίαση
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Το αντικείμενο δεδομένων γραμματοσειράς που περιέχει τις πληροφορίες για τη γραμματοσειρά [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Το στυλ της γραμματοσειράς για το οποίο ζητούνται τα δεδομένα [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Επιστρέφει:**
byte[] - Πίνακας byte που περιέχει τα δεδομένα της γραμματοσειράς για το καθορισμένο στυλ. Αν τα δεδομένα ή το στυλ δεν βρεθούν, επιστρέφει null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δοσμένο πίνακα byte και το όνομα της γραμματοσειράς.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Ανάκτηση όλων των γραμματοσειρών που χρησιμοποιούνται στην παρουσίαση
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Λήψη του πίνακα byte που αντιπροσωπεύει το κανονικό στυλ της πρώτης γραμματοσειράς στην παρουσίαση
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Καθορισμός του επιπέδου ενσωμάτωσης της γραμματοσειράς
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontBytes | byte[] | Ο πίνακας byte που περιέχει τα δεδομένα της γραμματοσειράς. |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς. |

**Επιστρέφει:**
int - Το επίπεδο ενσωμάτωσης της καθορισμένης γραμματοσειράς.