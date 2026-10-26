---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Gestisce i font nella presentazione.
type: docs
url: /it/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Gestisce i font nella presentazione.
## Metodi

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Sostituzioni di font da utilizzare durante il rendering Lettura/Scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Sostituzioni di font da utilizzare durante il rendering Lettura/Scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Rappresenta la collezione dell'utente di regole FontFallBack per gestire collezioni di font per corrette sostituzioni tramite funzionalità di fallback Lettura/Scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Rappresenta la collezione dell'utente di regole FontFallBack per gestire collezioni di font per corrette sostituzioni tramite funzionalità di fallback Lettura/Scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Restituisce i font utilizzati nella presentazione |
| [getSubstitutions()](#getSubstitutions--) | Ottiene le informazioni sui font che saranno sostituiti durante il rendering della presentazione. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Ottiene le informazioni sui font che saranno sostituiti durante il rendering delle diapositive specificate. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Restituisce i font incorporati nella presentazione |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Rimuove il font incorporato |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Aggiunge il font incorporato. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Aggiunge il font incorporato |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sostituisce il font nella presentazione |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Sostituisce il font nella presentazione utilizzando le informazioni fornite in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Sostituisce il font nella presentazione utilizzando le informazioni fornite nella collezione di [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera l'array di byte che rappresenta i dati del font per uno stile di font specificato e i dati del font. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina il livello di incorporamento di un font dal byte array fornito e dal nome del font. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Sostituzioni di font da utilizzare durante il rendering Lettura/Scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Restituisce:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Sostituzioni di font da utilizzare durante il rendering Lettura/Scrittura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Rappresenta la collezione dell'utente di regole FontFallBack per gestire collezioni di font per corrette sostituzioni tramite funzionalità di fallback Lettura/Scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ottenimento di una collezione di regole vuota o preinizializzata da FontsManager
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

Rappresenta la collezione dell'utente di regole FontFallBack per gestire collezioni di font per corrette sostituzioni tramite funzionalità di fallback Lettura/Scrittura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ottenimento di una collezione di regole vuota o preinizializzata da FontsManager
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Restituisce i font utilizzati nella presentazione

**Restituisce:**
com.aspose.slides.IFontData[] - Un array di font
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
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
| Parameter | Type | Description |
| --- | --- | --- |
| slides | int[] | Un array di indici di diapositive per le quali recuperare le informazioni di sostituzione del font, a partire da 1. |

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Una collezione di tutte le sostituzioni di font ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) per le diapositive specificate.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Restituisce i font incorporati nella presentazione

**Restituisce:**
com.aspose.slides.IFontData[] - Font incorporati IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Rimuove il font incorporato

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Oggetto dati del font [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Aggiunge il font incorporato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Oggetto dati del font [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Regola di incorporamento del font [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tieni presente che, copiando i font, la maggior parte di essi è protetta da copyright. Individua prima la licenza del font e verifica che possa essere trasferita liberamente su un altro computer. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Aggiunge il font incorporato

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | byte[] | Dati del font  byte[]  |
| embedFontRule | int | Regola di incorporamento del font [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tieni presente che, aggiungendo i font, la maggior parte di essi è protetta da copyright. Individua prima la licenza del font e verifica che possa essere trasferita liberamente su un altro computer. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Sostituisce il font nella presentazione

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di origine |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di destinazione |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Sostituisce il font nella presentazione utilizzando le informazioni fornite in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informazioni sulla sostituzione del font |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Sostituisce il font nella presentazione utilizzando le informazioni fornite nella collezione di [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collezione di informazioni sulla sostituzione del font |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Recupera l'array di byte che rappresenta i dati del font per uno stile di font specificato e i dati del font.

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
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | L'oggetto dati del font contenente le informazioni sul font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Lo stile del font per il quale recuperare i dati [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Restituisce:**
byte[] - Un array di byte contenente i dati del font per lo stile specificato. Se i dati o lo stile del font non vengono trovati, restituisce null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Determina il livello di incorporamento di un font dal byte array fornito e dal nome del font.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Recupera tutti i font utilizzati nella presentazione
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Ottieni l'array di byte che rappresenta lo stile regolare del primo font nella presentazione
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Determina il livello di incorporamento del font
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | Il byte array contenente i dati del font. |
| fontName | java.lang.String | Il nome del font. |

**Restituisce:**
int - Il livello di incorporamento del font specificato.