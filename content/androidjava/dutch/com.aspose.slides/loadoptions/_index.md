---
title: LoadOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe om extra opties op te geven, zoals formaat of standaardlettertype bij het laden van een presentatie.
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

Maakt het mogelijk om extra opties op te geven (zoals formaat of standaardlettertype) bij het laden van een presentatie.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Maakt nieuwe standaard laadopties aan. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Maakt nieuwe laadopties aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Retourneert of stelt het formaat van een te laden presentatie in. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Retourneert of stelt het formaat van een te laden presentatie in. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Retourneert of stelt het reguliere lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Retourneert of stelt het reguliere lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Retourneert of stelt het symboollettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Retourneert of stelt het symboollettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [getPassword()](#getPassword--) | Haalt het wachtwoord op of stelt het in. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Haalt het wachtwoord op of stelt het in. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Deze eigenschap heeft zin als het presentatiebestand met een wachtwoord is beveiligd. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Deze eigenschap heeft zin als het presentatiebestand met een wachtwoord is beveiligd. |
| [getWarningCallback()](#getWarningCallback--) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Stelt de opties voor die gebruikt kunnen worden om het gedrag bij het verwerken van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Stelt de opties voor die gebruikt kunnen worden om het gedrag bij het verwerken van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [getInterruptionToken()](#getInterruptionToken--) | Het token om onderbrekingsverzoeken te controleren. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Het token om onderbrekingsverzoeken te controleren. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Haalt opties op voor spreadsheets. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Haalt opties op voor spreadsheets. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Retourneert of stelt de standaardtaal voor presentatietekst in. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Retourneert of stelt de standaardtaal voor presentatietekst in. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Maakt nieuwe standaard laadopties aan.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Maakt nieuwe laadopties aan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadFormat | int | Formaat van een te laden presentatie. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Retourneert of stelt het formaat van een te laden presentatie in. Lezen/schrijven [LoadFormat](../../com.aspose.slides/loadformat).

**Retour:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Retourneert of stelt het formaat van een te laden presentatie in. Lezen/schrijven [LoadFormat](../../com.aspose.slides/loadformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Retourneert of stelt het reguliere lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

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
>      // Genereer dia-miniatuur
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Genereer PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Genereer XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Retourneert of stelt het reguliere lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

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
>      // Genereer dia-miniatuur
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Retourneert of stelt het symboollettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Retourneert of stelt het symboollettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Haalt het wachtwoord op of stelt het in. Lezen/schrijven String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // werk met ontsleutelde presentatie
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Waarde: Het wachtwoord.

**Retour:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Haalt het wachtwoord op of stelt het in. Lezen/schrijven String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // werk met ontsleutelde presentatie
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Waarde: Het wachtwoord.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Deze eigenschap heeft zin als het presentatiebestand met een wachtwoord is beveiligd. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Lezen/schrijven boolean.

**Retour:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Deze eigenschap heeft zin als het presentatiebestand met een wachtwoord is beveiligd. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retour:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Stelt de opties voor die gebruikt kunnen worden om het gedrag bij het verwerken van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste prestatie-/geheugengebruikverhouding in te stellen voor een specifieke omgeving of vereisten.

--------------------

Een Binary Large Object (BLOB) is een binaire data die als één entiteit wordt opgeslagen - d.w.z. een BLOB kan een audio, video of de presentatie zelf zijn.

**Retour:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Stelt de opties voor die gebruikt kunnen worden om het gedrag bij het verwerken van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste prestatie-/geheugengebruikverhouding in te stellen voor een specifieke omgeving of vereisten.

--------------------

Een Binary Large Object (BLOB) is een binaire data die als één entiteit wordt opgeslagen - d.w.z. een BLOB kan een audio, video of de presentatie zelf zijn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe je aangepaste lettertypen opgeeft die worden gebruikt met PowerPoint-presentatie.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // werk met de presentatie
>  //CustomFont1, CustomFont2 evenals lettertypen uit assets\fonts & global\fonts mappen en hun submappen zijn beschikbaar voor de presentatie
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retour:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe je aangepaste lettertypen opgeeft die gebruikt worden met een PowerPoint-presentatie.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // werk met de presentatie
>  //CustomFont1, CustomFont2 evenals lettertypen uit assets\fonts & global\fonts mappen en hun submappen zijn beschikbaar voor de presentatie
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Het token om onderbrekingsverzoeken te monitoren.

--------------------

Dit token beheert de volledige levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-methode van de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Retour:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Het token om onderbrekingsverzoeken te monitoren.

--------------------

Dit token beheert de volledige levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-methode van de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. Lezen/schrijven [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Retour:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. Lezen/schrijven [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Haalt opties op voor spreadsheets. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor diagrammen.

**Retour:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Haalt opties op voor spreadsheets. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor diagrammen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Retourneert of stelt de standaardtaal voor presentatietekst in. Lezen/schrijven String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Retourneert of stelt de standaardtaal voor presentatietekst in. Lezen/schrijven String.

--------------------

> ```
> Example:
>   
>  // Gebruik laadopties om de standaardtekscultuur te definiëren
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Voeg een nieuwe rechthoekvorm toe met tekst
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Controleer de taal van het eerste gedeelte
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

De typen van de ingebedde binaire objecten:

Lezen/schrijven boolean .

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

**Retour:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

De typen van de ingebedde binaire objecten:

Lezen/schrijven boolean .

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |