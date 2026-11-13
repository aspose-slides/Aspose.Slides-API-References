---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Gestisce i caratteri in tutta la presentazione.
type: docs
url: /it/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Gestisce i caratteri in tutta la presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Sostituzioni di caratteri da usare durante il rendering Lettura/scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Sostituzioni di caratteri da usare durante il rendering Lettura/scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di caratteri per le sostituzioni corrette tramite funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di caratteri per le sostituzioni corrette tramite funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Restituisce i caratteri usati nella presentazione |
| [getSubstitutions()](#getSubstitutions--) | Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering della presentazione. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering delle diapositive specificate. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Restituisce i caratteri incorporati nella presentazione |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Rimuove il carattere incorporato |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Aggiunge il carattere incorporato. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Aggiunge il carattere incorporato |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sostituisce il carattere nella presentazione |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Sostituisce il carattere nella presentazione usando le informazioni fornite in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Sostituisce il carattere nella presentazione usando le informazioni fornite nella collezione di [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera l'array di byte che rappresenta i dati del carattere per uno stile di carattere specificato. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina il livello di incorporamento di un carattere dall'array di byte e dal nome forniti. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Specifica se i caratteri registrati devono avere la precedenza sui caratteri incorporati con lo stesso nome e stile. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Specifica se i caratteri registrati devono avere la precedenza sui caratteri incorporati con lo stesso nome e stile. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Sostituzioni di caratteri da usare durante il rendering Lettura/scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Restituisce:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Sostituzioni di caratteri da usare durante il rendering Lettura/scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di caratteri per le sostituzioni corrette tramite funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // aggiunta di regole alla collezione
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oppure
>      // inizializzazione di una nuova istanza della collezione di regole
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // aggiunta di regole alla collezione
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e sostituzione della collezione esistente con quella nuova in FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione di collezioni di caratteri per le sostituzioni corrette tramite funzionalità di fallback Lettura/scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // aggiunta di regole alla collezione
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oppure 
>      // inizializzazione di una nuova istanza della collezione di regole
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // aggiunta di regole alla collezione
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e sostituzione della collezione esistente con quella nuova in FontsManager 
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
public abstract IFontData[] getFonts()
```


Restituisce i caratteri usati nella presentazione

**Restituisce:**
com.aspose.slides.IFontData[] - Un array di caratteri
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering della presentazione.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collezione di tutte le sostituzioni di caratteri [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering delle diapositive specificate.

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
| slides | int[] | Un array di indici delle diapositive per le quali recuperare le informazioni di sostituzione dei caratteri, a partire da 1. |

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Una collezione di tutte le sostituzioni di caratteri ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) per le diapositive specificate.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Restituisce i caratteri incorporati nella presentazione

**Restituisce:**
com.aspose.slides.IFontData[] - Caratteri incorporati IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


Rimuove il carattere incorporato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Oggetto dati del carattere [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Aggiunge il carattere incorporato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Oggetto dati del carattere [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Regola di incorporamento del carattere [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tieni presente, quando copi qualsiasi carattere, la maggior parte dei caratteri è protetta da copyright. Individua prima la licenza del carattere e verifica che possa essere trasferita liberamente a un altro computer. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Aggiunge il carattere incorporato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | byte[] | Dati del carattere  byte[]  |
| embedFontRule | int | Regola di incorporamento del carattere [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tieni presente, quando aggiungi qualsiasi carattere, la maggior parte dei caratteri è protetta da copyright. Individua prima la licenza del carattere e verifica che possa essere trasferita liberamente a un altro computer. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


Sostituisce il carattere nella presentazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Carattere sorgente |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Carattere di destinazione |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


Sostituisce il carattere nella presentazione usando le informazioni fornite in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informazioni sulla sostituzione del carattere |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


Sostituisce il carattere nella presentazione usando le informazioni fornite nella collezione di [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collezione di informazioni sulla sostituzione del carattere |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Recupera l'array di byte che rappresenta i dati del carattere per lo stile di carattere specificato.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Recupera tutti i caratteri usati nella presentazione
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Ottieni l'array di byte che rappresenta lo stile regolare del primo carattere nella presentazione
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | L'oggetto dati del carattere contenente le informazioni sul carattere [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Lo stile del carattere per il quale recuperare i dati [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Restituisce:**
byte[] - Un array di byte contenente i dati del carattere per lo stile specificato. Se i dati o lo stile non sono trovati, restituisce null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Determina il livello di incorporamento di un carattere dall'array di byte e dal nome forniti.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Recupera tutti i caratteri usati nella presentazione
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Ottieni l'array di byte che rappresenta lo stile regolare del primo carattere nella presentazione
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Determina il livello di incorporamento del carattere
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontBytes | byte[] | L'array di byte contenente i dati del carattere. |
| fontName | java.lang.String | Il nome del carattere. |

**Restituisce:**
int - Il livello di incorporamento del carattere specificato.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```


Specifică se i caratteri registrati devono avere la precedenza sui caratteri incorporati con lo stesso nome e stile. Quando abilitato, i caratteri incorporati corrispondenti sono temporaneamente sostituiti con i caratteri registrati corrispondenti durante l'esportazione.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Il valore predefinito è **false** .

**Restituisce:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```


Specifică se i caratteri registrati devono avere la precedenza sui caratteri incorporati con lo stesso nome e stile. Quando abilitato, i caratteri incorporati corrispondenti sono temporaneamente sostituiti con i caratteri registrati corrispondenti durante l'esportazione.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Il valore predefinito è **false** .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |