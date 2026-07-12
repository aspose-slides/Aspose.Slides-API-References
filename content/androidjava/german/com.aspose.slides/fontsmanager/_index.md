---
title: FontsManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Verwaltet Schriften in der gesamten Präsentation.
type: docs
url: /de/com.aspose.slides/fontsmanager/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Verwaltet Schriften in der gesamten Präsentation.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Präsentation laden
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Quellschrift laden, die ersetzt werden soll
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
>      // Präsentation speichern
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Schriftersatz, der beim Rendern verwendet wird. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Schriftersatz, der beim Rendern verwendet wird. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Stellt eine Benutzersammlung von FontFallBack-Regeln zur Verwaltung von Schriftenkollektionen für korrekte Ersetzungen durch Fallback-Funktionalität bereit. Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Stellt eine Benutzersammlung von FontFallBack-Regeln zur Verwaltung von Schriftenkollektionen für korrekte Ersetzungen durch Fallback-Funktionalität bereit. Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Gibt die in der Präsentation verwendeten Schriften zurück |
| [getSubstitutions()](#getSubstitutions--) | Ruft die Informationen zu den Schriften ab, die bei der Renderung der Präsentation ersetzt werden. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Ruft die Informationen zu den Schriften ab, die beim Rendern der angegebenen Folien ersetzt werden. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Gibt die in der Präsentation eingebetteten Schriften zurück. |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Entfernt die eingebettete Schrift. |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Fügt die eingebettete Schrift hinzu. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Fügt die eingebettete Schrift hinzu. |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersetzt die Schrift in der Präsentation. |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersetzt die Schrift in der Präsentation unter Verwendung der in [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen. |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersetzt die Schrift in der Präsentation unter Verwendung der in der Sammlung von [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen. |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Ruft das Byte-Array ab, das die Font-Daten für einen angegebenen Schriftstil und Font-Daten darstellt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestimmt das Einbettungsniveau einer Schrift anhand des gegebenen Byte-Arrays und des Schriftnamens. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Schriftersatz, der beim Rendern verwendet wird. Lesen/Schreiben [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Rückgabe:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Schriftersatz, der beim Rendern verwendet wird. Lesen/Schreiben [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Stellt eine Benutzersammlung von FontFallBack-Regeln zur Verwaltung von Schriftenkollektionen für korrekte Ersetzungen durch Fallback-Funktionalität bereit. Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Abrufen einer leeren oder vorinitialisierten Regelersammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oder 
>      // Initialisierung einer neuen Instanz der Regelersammlung
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // und Ersetzen der bestehenden Sammlung durch die neue im FontsManager 
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
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Stellt eine Benutzersammlung von FontFallBack-Regeln zur Verwaltung von Schriftenkollektionen für korrekte Ersetzungen durch Fallback-Funktionalität bereit. Lesen/Schreiben [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Abrufen einer leeren oder vorinitialisierten Regelersammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oder
>      // Initialisierung einer neuen Instanz der Regelersammlung
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Hinzufügen von Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // und Ersetzen der bestehenden Sammlung durch die neue im FontsManager
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
public final IFontData[] getFonts()
```

Gibt die in der Präsentation verwendeten Schriften zurück

**Rückgabe:**
com.aspose.slides.IFontData[] - Ein Array von Schriften
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Ruft die Informationen zu den Schriften ab, die bei der Renderung der Präsentation ersetzt werden.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sammlung aller Schriftersatzungen [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Ruft die Informationen zu den Schriften ab, die beim Rendern der angegebenen Folien ersetzt werden.

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
| slides | int[] | Ein Array von Folienindizes, für die die Schriftersatzinformationen abgerufen werden sollen, beginnend bei 1. |

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Eine Sammlung aller Schriftersätze ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) für die angegebenen Folien.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Gibt die in der Präsentation eingebetteten Schriften zurück

**Rückgabe:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Entfernt die eingebettete Schrift

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Fügt die eingebettete Schrift hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Fügt die eingebettete Schrift hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersetzt die Schrift in der Präsentation

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Quellschrift |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Zielschrift |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Ersetzt die Schrift in der Präsentation unter Verwendung der in [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Info zur Schriftersatz |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Ersetzt die Schrift in der Präsentation mittels der in der Sammlung von [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Sammlung von Schriftersatzregeln |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Ruft das Byte-Array ab, das die Font-Daten für einen angegebenen Schriftstil und Font-Daten darstellt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Alle in der Präsentation verwendeten Schriften abrufen
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Das Byte-Array erhalten, das den regulären Stil der ersten Schrift in der Präsentation darstellt
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Das Font-Datenobjekt, das die Informationen zur Schrift [IFontData](../../com.aspose.slides/ifontdata) enthält. |
| fontStyle | int | Der Stil der Schrift, für den die Daten abgerufen werden sollen [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Rückgabe:**
byte[] - Ein Byte-Array, das die Font-Daten für den angegebenen Schriftstil enthält. Wenn die Font-Daten oder der Stil nicht gefunden werden, wird null zurückgegeben.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestimmt das Einbettungsniveau einer Schrift anhand des gegebenen Byte-Arrays und des Schriftnamens.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Alle in der Präsentation verwendeten Schriften abrufen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Das Byte-Array erhalten, das den regulären Stil der ersten Schrift in der Präsentation darstellt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Bestimme das Einbettungsniveau der Schrift
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontBytes | byte[] | Das Byte-Array, das die Font-Daten enthält. |
| fontName | java.lang.String | Der Name der Schrift. |

**Rückgabe:**
int - Das Einbettungsniveau der angegebenen Schrift.