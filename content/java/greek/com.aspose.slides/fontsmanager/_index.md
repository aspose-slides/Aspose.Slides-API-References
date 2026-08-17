---
title: FontsManager
second_title: Aspose.Slides για Java API Αναφορά
description: Διαχειρίζεται γραμματοσειρές σε όλη την παρουσίαση.
type: docs
url: /el/com.aspose.slides/fontsmanager/
---
**Κληρονομικότητα:**  
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)  
```
public class FontsManager implements IFontsManager
```

Διαχειρίζεται γραμματοσειρές σε όλη την παρουσίαση.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Φόρτωση παρουσίασης
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Φόρτωση γραμματοσειράς προέλευσης προς αντικατάσταση
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Αποθήκευση παρουσίασης
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Υποκατάστατες γραμματοσειρών για χρήση κατά τη απόδοση. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Υποκατάστατες γραμματοσειρών για χρήση κατά τη απόδοση. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Αναπαριστά τη συλλογή ενός χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές υποκαταστάσεις μέσω λειτουργίας fallback. Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Αναπαριστά τη συλλογή ενός χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές υποκαταστάσεις μέσω λειτουργίας fallback. Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |
| [getSubstitutions()](#getSubstitutions--) | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά τη διάρκεια της απόδοσης των καθορισμένων διαφανειών. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Επιστρέφει τις ενσωματωμένες γραμματοσειρές στην παρουσίαση |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Καταργεί την ενσωματωμένη γραμματοσειρά |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Προσθέτει την ενσωματωμένη γραμματοσειρά |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Προσθέτει την ενσωματωμένη γραμματοσειρά |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Ανακτά το πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα byte και το όνομα γραμματοσειράς. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Υποκατάστατες γραμματοσειρών για χρήση κατά τη απόδοση. Ανάγνωση/εγγραφή [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Επιστρέφει:**  
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Υποκατάστατες γραμματοσειρών για χρήση κατά τη απόδοση. Ανάγνωση/εγγραφή [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Αναπαριστά τη συλλογή ενός χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές υποκαταστάσεις μέσω λειτουργίας fallback. Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // προσθήκη κανόνων στη συλλογή
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ή 
>      // αρχικοποίηση νέας παρουσίασης της συλλογής κανόνων
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
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Αναπαριστά τη συλλογή ενός χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές υποκαταστάσεις μέσω λειτουργίας fallback. Ανάγνωση/εγγραφή [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // προσθήκη κανόνων στη συλλογή
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ή 
>      // αρχικοποίηση νέας παρουσίασης της συλλογής κανόνων
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
public final IFontData[] getFonts()
```

Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση

**Επιστρέφει:**  
com.aspose.slides.IFontData[] - Πίνακας γραμματοσειρών

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Συλλογή όλων των υποκαταστάσεων γραμματοσειρών [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά τη διάρκεια της απόδοσης των καθορισμένων διαφανειών.

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
| slides | int[] | Πίνακας δεικτών διαφανειών για τους οποίους θα ανακτηθεί η πληροφορία υποκατάστασης γραμματοσειράς, ξεκινώντας από το 1. |

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Συλλογή όλων των υποκαταστάσεων γραμματοσειρών ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) για τις καθορισμένες διαφάνειες.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Επιστρέφει τις ενσωματωμένες γραμματοσειρές στην παρουσίαση

**Επιστρέφει:**  
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Καταργεί την ενσωματωμένη γραμματοσειρά

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Προσθέτει την ενσωματωμένη γραμματοσειρά

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Προσθέτει την ενσωματωμένη γραμματοσειρά

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Αντικαθιστά τη γραμματοσειρά στην παρουσίαση

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Πηγή γραμματοσειράς |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Προορισμός γραμματοσειράς |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Πληροφορίες υποκατάστασης γραμματοσειράς |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στη συλλογή του [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Συλλογή κανόνων υποκατάστασης γραμματοσειράς |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Ανακτά το πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς.

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
| fontStyle | int | Το στυλ της γραμματοσειράς για το οποίο θα ανακτηθούν τα δεδομένα [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Επιστρέφει:**  
byte[] - Πίνακας byte που περιέχει τα δεδομένα γραμματοσειράς για το καθορισμένο στυλ. Αν τα δεδομένα ή το στυλ δεν βρεθούν, επιστρέφει null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα byte και το όνομα γραμματοσειράς.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Ανάκτηση όλων των γραμματοσειρών που χρησιμοποιούνται στην παρουσίαση
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Λήψη του πίνακα byte που αντιπροσωπεύει το κανονικό στυλ της πρώτης γραμματοσειράς στην παρουσίαση
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Προσδιορισμός του επιπέδου ενσωμάτωσης της γραμματοσειράς
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