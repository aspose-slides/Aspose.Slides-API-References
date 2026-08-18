---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Verwaltet Schriftarten in der gesamten Präsentation.
type: docs
url: /de/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Verwaltet Schriftarten in der gesamten Präsentation.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Schriftart-Substitutionen, die beim Rendern im Lese-/Schreibmodus [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) verwendet werden. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Schriftart-Substitutionen, die beim Rendern im Lese-/Schreibmodus [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) verwendet werden. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Stellt die Sammlung von FontFallBack-Regeln des Benutzers zum Verwalten von Schriftartensammlungen für korrekte Substitutionen durch Fallback-Funktionalität im Lese-/Schreibmodus [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) dar. |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Stellt die Sammlung von FontFallBack-Regeln des Benutzers zum Verwalten von Schriftartensammlungen für korrekte Substitutionen durch Fallback-Funktionalität im Lese-/Schreibmodus [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) dar. |
| [getFonts()](#getFonts--) | Gibt die in der Präsentation verwendeten Schriftarten zurück |
| [getSubstitutions()](#getSubstitutions--) | Ruft Informationen über Schriftarten ab, die bei der Wiedergabe der Präsentation ersetzt werden. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Ruft Informationen über Schriftarten ab, die bei der Wiedergabe der angegebenen Folien ersetzt werden. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Gibt die in der Präsentation eingebetteten Schriftarten zurück |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Entfernt die eingebettete Schriftart |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Fügt die eingebettete Schriftart hinzu. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Fügt die eingebettete Schriftart hinzu |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersetzt die Schriftart in der Präsentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersetzt die Schriftart in der Präsentation mithilfe der in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellten Informationen |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersetzt die Schriftart in der Präsentation mithilfe der in der Sammlung von [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellten Informationen |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftart enthält. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestimmt die Einbettungsstufe einer Schriftart anhand des übergebenen Byte-Arrays und des Schriftartnamens. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Schriftart-Substitutionen, die beim Rendern im Lese-/Schreibmodus [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) verwendet werden.

**Rückgabe:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Schriftart-Substitutionen, die beim Rendern im Lese-/Schreibmodus [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) verwendet werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |
### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Stellt die Sammlung von FontFallBack-Regeln des Benutzers zum Verwalten von Schriftartensammlungen für korrekte Substitutionen durch Fallback-Funktionalität im Lese-/Schreibmodus [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) dar.

--------------------

> ```markdown
> Presentation pres = new Presentation();
>  try
>  {
>      // Abrufen einer leeren oder vorinitialisierten Regelsammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oder 
>      // Initialisierung einer neuen Instanz der Regelsammlung
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // und Ersetzen der vorhandenen Sammlung durch die neue in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Stellt die Sammlung von FontFallBack-Regeln des Benutzers zum Verwalten von Schriftartensammlungen für korrekte Substitutionen durch Fallback-Funktionalität im Lese-/Schreibmodus [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) dar.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Abrufen einer leeren oder vorinitialisierten Regelsammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oder 
>      // Initialisierung einer neuen Instanz der Regelsammlung
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // und Ersetzen der vorhandenen Sammlung durch die neue in FontsManager 
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

**Rückgabe:**
com.aspose.slides.IFontData[] - Ein Array von Schriftarten
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Ruft Informationen über Schriftarten ab, die bei der Wiedergabe der Präsentation ersetzt werden.

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


**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sammlung aller Schriftart-Substitutionen [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Ruft Informationen über Schriftarten ab, die bei der Wiedergabe der angegebenen Folien ersetzt werden.

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
| slides | int[] | Ein Array von Folienindizes, für die Schriftart-Substitutions-Informationen abgerufen werden sollen, beginnend bei 1. |

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Eine Sammlung aller Schriftart-Substitutionen ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) für die angegebenen Folien.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Gibt die in der Präsentation eingebetteten Schriftarten zurück

**Rückgabe:**
com.aspose.slides.IFontData[] - Eingebettete Schriftarten IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Entfernt die eingebettete Schriftart

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Schriftart-Datenobjekt [IFontData](../../com.aspose.slides/ifontdata) |
### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Fügt die eingebettete Schriftart hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Schriftart-Datenobjekt [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Eingebettete-Schriftart-Regel [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Beachten Sie beim Kopieren von Schriftarten, dass die meisten Schriftarten urheberrechtlich geschützt sind. Ermitteln Sie zunächst die Lizenz einer Schriftart und prüfen Sie, ob sie frei auf eine andere Maschine übertragen werden kann. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Fügt die eingebettete Schriftart hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | byte[] | Schriftartdaten byte[] |
| embedFontRule | int | Eingebettete-Schriftart-Regel [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Beachten Sie beim Hinzufügen von Schriftarten, dass die meisten Schriftarten urheberrechtlich geschützt sind. Ermitteln Sie zunächst die Lizenz einer Schriftart und prüfen Sie, ob sie frei auf eine andere Maschine übertragen werden kann. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersetzt die Schriftart in der Präsentation

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Quellschriftart |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Zielschriftart |
### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Ersetzt die Schriftart in der Präsentation mithilfe der in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellten Informationen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Schriftart-Substitutions-Info |
### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Ersetzt die Schriftart in der Präsentation mithilfe der in der Sammlung von [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) bereitgestellten Informationen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Sammlung von Schriftart-Substitutions-Infos |
### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftart enthält.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Abrufen aller in der Präsentation verwendeten Schriftarten
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Abrufen des Byte-Arrays, das den normalen Stil der ersten Schriftart in der Präsentation darstellt
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Das Schriftart-Datenobjekt, das Informationen über die Schriftart [IFontData](../../com.aspose.slides/ifontdata) enthält. |
| fontStyle | int | Der Stil der Schriftart, für die die Daten abgerufen werden sollen [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Rückgabe:**
byte[] - Ein Byte-Array, das die Schriftartdaten für den angegebenen Schriftstil enthält. Wenn die Schriftartdaten oder der Stil nicht gefunden werden, wird null zurückgegeben.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestimmt die Einbettungsstufe einer Schriftart anhand des übergebenen Byte-Arrays und des Schriftartnamens.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Abrufen aller in der Präsentation verwendeten Schriftarten
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Abrufen des Byte-Arrays, das den normalen Stil der ersten Schriftart in der Präsentation darstellt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Bestimmen der Einbettungsstufe der Schriftart
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

**Rückgabe:**
int - Die Einbettungsstufe der angegebenen Schriftart.