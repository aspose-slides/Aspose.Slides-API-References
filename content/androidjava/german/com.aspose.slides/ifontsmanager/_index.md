---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /de/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Verwaltet Schriftarten in der gesamten Präsentation.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Schriftartersetzungen, die beim Rendern verwendet werden, Lesen/Schreiben [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Schriftartersetzungen, die beim Rendern verwendet werden, Lesen/Schreiben [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, um Sammlungen von Schriftarten für korrekte Ersetzungen durch Fallback-Funktionalität zu verwalten, Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, um Sammlungen von Schriftarten für korrekte Ersetzungen durch Fallback-Funktionalität zu verwalten, Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Gibt die in der Präsentation verwendeten Schriftarten zurück |
| [getSubstitutions()](#getSubstitutions--) | Erhält die Informationen über Schriftarten, die beim Rendern der Präsentation ersetzt werden. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Erhält die Informationen über Schriftarten, die beim Rendern der angegebenen Folien ersetzt werden. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Gibt die in der Präsentation eingebetteten Schriftarten zurück |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Entfernt die eingebettete Schriftart |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Fügt die eingebettete Schriftart hinzu. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Fügt die eingebettete Schriftart hinzu |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersetzt die Schriftart in der Präsentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersetzt die Schriftart in der Präsentation mithilfe von Informationen, die in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellt werden |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersetzt die Schriftart in der Präsentation mithilfe von Informationen, die in der Sammlung von [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellt werden |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestimmt das Einbettungslevel einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Schriftartersetzungen, die beim Rendern verwendet werden, Lesen/Schreiben [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Rückgabewert:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Schriftartersetzungen, die beim Rendern verwendet werden, Lesen/Schreiben [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |
### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, um Sammlungen von Schriftarten für korrekte Ersetzungen durch Fallback-Funktionalität zu verwalten, Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // initialization of new instance of rules collection
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // and replacing of existing collection by the new one in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Stellt die Sammlung von FontFallBack-Regeln eines Benutzers dar, um Sammlungen von Schriftarten für korrekte Ersetzungen durch Fallback-Funktionalität zu verwalten, Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // initialization of new instance of rules collection
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // and replacing of existing collection by the new one in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |
### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Gibt die in der Präsentation verwendeten Schriftarten zurück

**Rückgabewert:**
com.aspose.slides.IFontData[] - Ein Array von Schriftarten
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Erhält die Informationen über Schriftarten, die beim Rendern der Präsentation ersetzt werden.

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

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sammlung aller Schriftartersetzungen [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Erhält die Informationen über Schriftarten, die beim Rendern der angegebenen Folien ersetzt werden.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slides | int[] | Ein Array von Folienindizes, für die die Schriftartersetzungsinformationen abgerufen werden sollen, beginnend bei 1. |

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Eine Sammlung aller Schriftartersetzungen ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) für die angegebenen Folien.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Gibt die in der Präsentation eingebetteten Schriftarten zurück

**Rückgabewert:**
com.aspose.slides.IFontData[] - Eingebettete Schriftarten IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Entfernt die eingebettete Schriftart

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Fontdaten-Objekt [IFontData](../../com.aspose.slides/ifontdata) |
### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Fügt die eingebettete Schriftart hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Fontdaten-Objekt [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Regel für eingebettete Schriftart [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Beachten Sie, dass die meisten Schriftarten urheberrechtlich geschützt sind, wenn Sie Schriftarten kopieren. Ermitteln Sie zunächst die Lizenz einer Schriftart und prüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Fügt die eingebettete Schriftart hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | byte[] | Schriftartdaten  byte[] |
| embedFontRule | int | Regel für eingebettete Schriftart [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Beachten Sie, dass die meisten Schriftarten urheberrechtlich geschützt sind, wenn Sie Schriftarten hinzufügen. Ermitteln Sie zunächst die Lizenz einer Schriftart und prüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersetzt die Schriftart in der Präsentation

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Quellschriftart |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Zielsschriftart |
### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Ersetzt die Schriftart in der Präsentation mithilfe von Informationen, die in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellt werden

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Information zur Schriftartersetzung |
### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Ersetzt die Schriftart in der Präsentation mithilfe von Informationen, die in der Sammlung von [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellt werden

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Sammlung von Informationen zur Schriftartersetzung |
### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Alle in der Präsentation verwendeten Schriftarten abrufen
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Das Byte-Array abrufen, das den regulären Stil der ersten Schriftart in der Präsentation darstellt
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Das Fontdaten-Objekt, das die Informationen über die Schriftart [IFontData](../../com.aspose.slides/ifontdata) enthält. |
| fontStyle | int | Der Stil der Schriftart, für den die Daten abgerufen werden sollen [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Rückgabewert:**
byte[] - Ein Byte-Array, das die Schriftartdaten für den angegebenen Schriftstil enthält. Falls die Schriftartdaten oder der Stil nicht gefunden werden, wird null zurückgegeben.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestimmt das Einbettungslevel einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Alle in der Präsentation verwendeten Schriftarten abrufen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Das Byte-Array abrufen, das den regulären Stil der ersten Schriftart in der Präsentation darstellt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Bestimmt das Einbettungslevel der Schriftart
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontBytes | byte[] | Das Byte-Array, das die Schriftartdaten enthält. |
| fontName | java.lang.String | Der Name der Schriftart. |

**Rückgabewert:**
int - Der Einbettungsgrad der angegebenen Schriftart.