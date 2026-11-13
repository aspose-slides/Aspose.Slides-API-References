---
title: FontsManager
second_title: Aspose.Slides für Java API Referenz
description: Verwaltet Schriftarten in der gesamten Präsentation.
type: docs
url: /de/com.aspose.slides/fontsmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Verwaltet Schriftarten in der gesamten Präsentation.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Präsentation laden
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Quellschriftart laden, die ersetzt werden soll
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
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Schriftart-Ersetzungen, die beim Rendern verwendet werden. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Schriftart-Ersetzungen, die beim Rendern verwendet werden. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Stellt die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch Fallback-Funktionalität dar. Lese/Schreib [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Stellt die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch Fallback-Funktionalität dar. Lese/Schreib [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Gibt die in der Präsentation verwendeten Schriftarten zurück |
| [getSubstitutions()](#getSubstitutions--) | Ermittelt die Informationen über Schriftarten, die beim Rendern der Präsentation ersetzt werden. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Ermittelt die Informationen über Schriftarten, die beim Rendern der angegebenen Folien ersetzt werden. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Legt fest, ob registrierte Schriftarten bevorzugt werden sollen gegenüber eingebetteten Schriftarten mit demselben Schriftartnamen und -stil. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Legt fest, ob registrierte Schriftarten bevorzugt werden sollen gegenüber eingebetteten Schriftarten mit demselben Schriftartnamen und -stil. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Gibt die in der Präsentation eingebetteten Schriftarten zurück |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Entfernt die eingebettete Schriftart |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Fügt die eingebettete Schriftart hinzu |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Fügt die eingebettete Schriftart hinzu |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersetzt die Schriftart in der Präsentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersetzt die Schriftart in der Präsentation mithilfe der in [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersetzt die Schriftart in der Präsentation mithilfe der in einer Sammlung von [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestimmt das Einbettungsniveau einer Schriftart anhand des angegebenen Byte-Arrays und des Schriftartnamens. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Schriftart-Ersetzungen, die beim Rendern verwendet werden. Lese/Schreib [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Rückgabe:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Schriftart-Ersetzungen, die beim Rendern verwendet werden. Lese/Schreib [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |
### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Stellt die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch Fallback-Funktionalität dar. Lese/Schreib [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Abrufen der leeren oder vorinitialisierten Regelensammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Regeln zur Sammlung hinzufügen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oder 
>      // Initialisierung einer neuen Instanz der Regelensammlung
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Regeln zur Sammlung hinzufügen
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
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Stellt die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch Fallback-Funktionalität dar. Lese/Schreib [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Abrufen der leeren oder vorinitialisierten Regelensammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Regeln zur Sammlung hinzufügen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oder 
>      // Initialisierung einer neuen Instanz der Regelensammlung
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Regeln zur Sammlung hinzufügen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // und Ersetzen der bestehenden Sammlung durch die neue in FontsManager 
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

Gibt die in der Präsentation verwendeten Schriftarten zurück

**Rückgabe:**
com.aspose.slides.IFontData[] - Ein Array von Schriftarten
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Ermittelt die Informationen über Schriftarten, die beim Rendern der Präsentation ersetzt werden.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sammlung aller Schriftart-Ersetzungen [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Ermittelt die Informationen über Schriftarten, die beim Rendern der angegebenen Folien ersetzt werden.

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
| slides | int[] | Ein Array von Folienindizes, für die Schriftart-Ersetzungsinformationen abgerufen werden sollen, beginnend bei 1. |
**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Eine Sammlung aller Schriftart-Ersetzungen ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) für die angegebenen Folien.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

Legt fest, ob registrierte Schriftarten bevorzugt werden sollen gegenüber eingebetteten Schriftarten mit demselben Schriftartnamen und -stil. Wenn aktiviert, werden passende eingebettete Schriftarten während des Exports vorübergehend durch die entsprechenden registrierten Schriftarten ersetzt.

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

Standard ist **false**.

**Rückgabe:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Legt fest, ob registrierte Schriftarten bevorzugt werden sollen gegenüber eingebetteten Schriftarten mit demselben Schriftartnamen und -stil. Wenn aktiviert, werden passende eingebettete Schriftarten während des Exports vorübergehend durch die entsprechenden registrierten Schriftarten ersetzt.

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

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Gibt die in der Präsentation eingebetteten Schriftarten zurück

**Rückgabe:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Entfernt die eingebettete Schriftart

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Fügt die eingebettete Schriftart hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Fügt die eingebettete Schriftart hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersetzt die Schriftart in der Präsentation

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Quellschriftart |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Zielschriftart |
### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Ersetzt die Schriftart in der Präsentation mithilfe der in [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Schriftart-Ersetzungsinformation |
### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Ersetzt die Schriftart in der Präsentation mithilfe der in einer Sammlung von [FontSubstRule](../../com.aspose.slides/fontsubstrule) bereitgestellten Informationen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Sammlung von Schriftart-Ersetzungsregeln |
### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Alle in der Präsentation verwendeten Schriftarten abrufen
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Das Byte-Array erhalten, das den regulären Stil der ersten Schriftart in der Präsentation darstellt
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Das Schriftartdatenobjekt, das Informationen über die Schriftart [IFontData](../../com.aspose.slides/ifontdata) enthält. |
| fontStyle | int | Der Stil der Schriftart, für den die Daten abgerufen werden sollen [FontStyleType](../../com.aspose.slides/fontstyletype). |
**Rückgabe:**
byte[] - Ein Byte-Array, das die Schriftartdaten für den angegebenen Schriftstil enthält. Wenn die Schriftartdaten oder der Stil nicht gefunden werden, wird null zurückgegeben.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestimmt das Einbettungsniveau einer Schriftart anhand des angegebenen Byte-Arrays und des Schriftartnamens.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Alle in der Präsentation verwendeten Schriftarten abrufen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Das Byte-Array erhalten, das den regulären Stil der ersten Schriftart in der Präsentation darstellt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Das Einbettungsniveau der Schriftart bestimmen
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
int - Das Einbettungsniveau der angegebenen Schriftart.