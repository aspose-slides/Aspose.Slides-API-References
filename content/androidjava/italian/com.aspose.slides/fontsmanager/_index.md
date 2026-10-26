---
title: FontsManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Gestisce i font nella presentazione.
type: docs
url: /it/com.aspose.slides/fontsmanager/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Gestisce i font nella presentazione.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Carica la presentazione
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Carica il font sorgente da sostituire
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
>      // Salva la presentazione
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Sostituzioni di font da utilizzare durante il rendering. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Sostituzioni di font da utilizzare durante il rendering. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di font per corrette sostituzioni tramite la funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di font per corrette sostituzioni tramite la funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Restituisce i font utilizzati nella presentazione |
| [getSubstitutions()](#getSubstitutions--) | Ottiene le informazioni sui font che saranno sostituiti durante il rendering della presentazione. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Ottiene le informazioni sui font che saranno sostituiti durante il rendering delle diapositive specificate. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Restituisce i font incorporati nella presentazione |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Rimuove il font incorporato |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Aggiunge il font incorporato |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Aggiunge il font incorporato |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sostituisce il font nella presentazione |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Sostituisce il font nella presentazione usando le informazioni fornite in [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Sostituisce il font nella presentazione usando le informazioni fornite nella collezione di [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera l'array di byte che rappresenta i dati del font per uno stile di font specificato e dati del font. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina il livello di incorporamento di un font dal byte array fornito e dal nome del font. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Sostituzioni di font da utilizzare durante il rendering. Lettura/scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Restituisce:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Sostituzioni di font da utilizzare durante il rendering. Lettura/scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di font per corrette sostituzioni tramite la funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Recupero della raccolta di regole vuota o preinizializzata da FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // aggiunta di regole alla raccolta
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oppure 
>      // inizializzazione di una nuova istanza della raccolta di regole
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // aggiunta di regole alla raccolta
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e sostituzione della raccolta esistente con quella nuova in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di font per corrette sostituzioni tramite la funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ottenimento della raccolta di regole vuota o pre-inizializzata da FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // aggiunta di regole alla raccolta
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oppure 
>      // inizializzazione di una nuova istanza della raccolta di regole
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // aggiunta di regole alla raccolta
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e sostituzione della raccolta esistente con quella nuova in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Restituisce i font utilizzati nella presentazione

**Restituisce:**
com.aspose.slides.IFontData[] - Un array di font
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Ottiene le informazioni sui font che saranno sostituiti durante il rendering della presentazione.

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


**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collezione di tutte le sostituzioni di font [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Ottiene le informazioni sui font che saranno sostituiti durante il rendering delle diapositive specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slides | int[] | Un array di indici di diapositive per le quali recuperare le informazioni di sostituzione del font, a partire da 1. |

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Una collezione di tutte le sostituzioni di font ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) per le diapositive specificate.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Restituisce i font incorporati nella presentazione

**Restituisce:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Rimuove il font incorporato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Aggiunge il font incorporato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Aggiunge il font incorporato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Sostituisce il font nella presentazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di origine |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di destinazione |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Sostituisce il font nella presentazione usando le informazioni fornite in [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informazioni sulla sostituzione del font |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Sostituisce il font nella presentazione usando le informazioni fornite nella collezione di [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collezione di regole di sostituzione del font |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Recupera l'array di byte che rappresenta i dati del font per uno stile di font specificato e dati del font.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Recupera tutti i font utilizzati nella presentazione
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Ottieni l'array di byte che rappresenta lo stile regolare del primo font nella presentazione
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | L'oggetto dati del font contenente le informazioni sul font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Lo stile del font per il quale i dati devono essere recuperati [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Restituisce:**
byte[] - Un array di byte contenente i dati del font per lo stile specificato. Se i dati o lo stile del font non vengono trovati, restituisce null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Determina il livello di incorporamento di un font dal byte array fornito e dal nome del font.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Recupera tutti i font utilizzati nella presentazione
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Ottieni l'array di byte che rappresenta lo stile regolare del primo font nella presentazione
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Determina il livello di incorporamento del font
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontBytes | byte[] | L'array di byte contenente i dati del font. |
| fontName | java.lang.String | Il nome del font. |

**Restituisce:**
int - Il livello di incorporamento del font specificato.