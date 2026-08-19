---
title: LoadOptions
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe extra opties, zoals formaat of standaardlettertype, op te geven bij het laden van een presentatie.
type: docs
url: /nl/com.aspose.slides/loadoptions/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Staat toe om aanvullende opties (zoals formaat of standaardlettertype) op te geven bij het laden van een presentatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Maakt nieuwe standaard laadopties. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Maakt nieuwe laadopties. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Geeft het formaat van een te laden presentatie terug of stelt het in. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Geeft het formaat van een te laden presentatie terug of stelt het in. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Geeft het reguliere lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Geeft het reguliere lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Geeft het symboollettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Geeft het symboollettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Geeft het Aziatische lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Geeft het Aziatische lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. |
| [getPassword()](#getPassword--) | Haalt het wachtwoord op of stelt het in. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Haalt het wachtwoord op of stelt het in. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Deze eigenschap heeft betekenis als het presentatie-bestand met wachtwoord beschermd is. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Deze eigenschap heeft betekenis als het presentatie-bestand met wachtwoord beschermd is. |
| [getWarningCallback()](#getWarningCallback--) | Geeft een object terug dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Geeft een object terug dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag van Binary Large Objects (BLOBs) te beheren, zoals het gebruik van tijdelijke bestanden of maximaal BLOB-bytes in het geheugen. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag van Binary Large Objects (BLOBs) te beheren, zoals het gebruik van tijdelijke bestanden of maximaal BLOB-bytes in het geheugen. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [getInterruptionToken()](#getInterruptionToken--) | Het token om onderbrekingsverzoeken te monitoren. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Het token om onderbrekingsverzoeken te monitoren. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Geeft een callback-interface terug die het laden van externe resources beheert. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Geeft een callback-interface terug die het laden van externe resources beheert. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Haalt opties voor spreadsheets op. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Haalt opties voor spreadsheets op. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Geeft de standaardtaal voor presentatietekst terug of stelt deze in. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Geeft de standaardtaal voor presentatietekst terug of stelt deze in. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Maakt nieuwe standaard laadopties.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Maakt nieuwe laadopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loadFormat | int | Formaat van een te laden presentatie. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Geeft het formaat van een te laden presentatie terug of stelt het in. Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Geeft het formaat van een te laden presentatie terug of stelt het in. Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Geeft het reguliere lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Gebruik laadopties om de standaard reguliere en Aziatische lettertypen te definiëren
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Laad de presentatie
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Genereer miniatuur van dia
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Genereer PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Genereer XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Geeft het reguliere lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Gebruik laadopties om de standaard reguliere en Aziatische lettertypen te definiëren
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Laad de presentatie
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Genereer miniatuur van dia
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Genereer PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Genereer XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Geeft het symboollettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. Read/write String.

**Returns:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Geeft het symboollettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. Read/write String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Geeft het Aziatische lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. Read/write String.

**Returns:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Geeft het Aziatische lettertype terug dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden, of stelt het in. Read/write String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Haalt het wachtwoord op of stelt het in. Read/write String.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe een met wachtwoord beveiligde PowerPoint-presentatie te openen.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // werk met de ontsleutelde presentatie
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Waarde: Het wachtwoord.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Stelt het wachtwoord in of haalt het op. Read/write String.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe een met wachtwoord beveiligde PowerPoint-presentatie te openen.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // werk met de ontsleutelde presentatie
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Waarde: Het wachtwoord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Deze eigenschap heeft betekenis als het presentatie-bestand met wachtwoord beschermd is. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld bestand en het wachtwoord wordt genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapgenegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschap true is, kunnen de eigenschappen niet worden geladen en wordt er een uitzondering gegooid. Read/write boolean.

**Returns:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Deze eigenschap heeft betekenis als het presentatie-bestand met wachtwoord beschermd is. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld bestand en het wachtwoord wordt genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapgenegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschap true is, kunnen de eigenschappen niet worden geladen en wordt er een uitzondering gegooid. Read/write boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Geeft een object terug dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag van Binary Large Objects (BLOBs) te beheren, zoals het gebruik van tijdelijke bestanden of maximaal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugengebruik voor een specifieke omgeving of vereiste in te stellen.

--------------------

Een Binary Large Object (BLOB) is een binaire data die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio-, video- of presentatie-bestand zijn.

**Returns:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag van Binary Large Objects (BLOBs) te beheren, zoals het gebruik van tijdelijke bestanden of maximaal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugengebruik voor een specifieke omgeving of vereiste in te stellen.

--------------------

Een Binary Large Object (BLOB) is een binaire data die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio-, video- of presentatie-bestand zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe aangepaste lettertypen voor een PowerPoint-presentatie kunnen worden gespecificeerd.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //werk met de presentatie
>  //CustomFont1, CustomFont2 evenals lettertypen uit de mappen assets\fonts & global\fonts en hun submappen zijn beschikbaar voor de presentatie
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returns:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe aangepaste lettertypen voor een PowerPoint-presentatie kunnen worden gespecificeerd.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //werk met de presentatie
>  //CustomFont1, CustomFont2 evenals lettertypen uit de mappen assets\fonts & global\fonts en hun submappen zijn beschikbaar voor de presentatie
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Het token om onderbrekingsverzoeken te monitoren.

--------------------

Dit token beheert de volledige levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-methode van de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returns:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Het token om onderbrekingsverzoeken te monitoren.

--------------------

Dit token beheert de volledige levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-methode van de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Geeft een callback-interface terug die het laden van externe resources beheert. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returns:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Stelt een callback-interface in die het laden van externe resources beheert. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Haalt opties voor spreadsheets op. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor grafieken.

**Returns:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Stelt opties voor spreadsheets in. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor grafieken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Geeft de standaardtaal voor presentatietekst terug of stelt deze in. Read/write String.

--------------------

> ```
> Example:
>   
>  // Gebruik laadopties om de standaardtekstaal te definiëren
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Voeg een nieuw rechthoekig vormelement met tekst toe
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Controleer de taal van het eerste gedeelte
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Stelt de standaardtaal voor presentatietekst in of haalt deze op. Read/write String.

--------------------

> ```
> Example:
>   
>  // Gebruik laadopties om de standaardtekstaal te definiëren
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Voeg een nieuw rechthoekig vormelement met tekst toe
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Controleer de taal van het eerste gedeelte
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

De typen van de ingebedde binaire objecten:

Read/write boolean.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe de presentatie te laden zonder enige ingebedde binaire objecten.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Standaard is **false**.

**Returns:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

De typen van de ingebedde binaire objecten:

Read/write boolean.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe de presentatie te laden zonder enige ingebedde binaire objecten.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |