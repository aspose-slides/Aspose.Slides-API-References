---
title: ILoadOptions
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe om extra opties op te geven, zoals formaat of standaardlettertype, bij het laden van een presentatie.
type: docs
url: /nl/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Staat toe om extra opties (zoals formaat of standaardlettertype) op te geven bij het laden van een presentatie.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Geeft het formaat van een presentatie terug of stelt het in bij het laden. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Geeft het formaat van een presentatie terug of stelt het in bij het laden. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Geeft het reguliere lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Geeft het reguliere lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Geeft het symboollettertype terug of stelt het in als de bronlettertype niet wordt gevonden. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Geeft het symboollettertype terug of stelt het in als de bronlettertype niet wordt gevonden. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Geeft het Aziatische lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Geeft het Aziatische lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. |
| [getPassword()](#getPassword--) | Haalt het wachtwoord op of stelt het in. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Haalt het wachtwoord op of stelt het in. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Deze eigenschap is relevant als het presentatiebestand met wachtwoord is beveiligd. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Deze eigenschap is relevant als het presentatiebestand met wachtwoord is beveiligd. |
| [getWarningCallback()](#getWarningCallback--) | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Stelt de opties voor die gebruikt kunnen worden om het gedrag van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Stelt de opties voor die gebruikt kunnen worden om het gedrag van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [getInterruptionToken()](#getInterruptionToken--) | Het token om onderbrekingsverzoeken te monitoren. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Het token om onderbrekingsverzoeken te monitoren. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Geeft de callback-interface terug of stelt deze in die het laden van externe bronnen beheert. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Geeft de callback-interface terug of stelt deze in die het laden van externe bronnen beheert. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Stelt opties voor die gebruikt kunnen worden om extra spreadsheet-gedrag te specificeren. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Stelt opties voor die gebruikt kunnen worden om extra spreadsheet-gedrag te specificeren. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Geeft de standaardtaal voor presentatietekst terug of stelt deze in. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Geeft de standaardtaal voor presentatietekst terug of stelt deze in. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


Geeft het formaat van een presentatie terug of stelt het in bij het laden. Lezen/schrijven [LoadFormat](../../com.aspose.slides/loadformat).

**Retour:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```


Geeft het formaat van een presentatie terug of stelt het in bij het laden. Lezen/schrijven [LoadFormat](../../com.aspose.slides/loadformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Geeft het reguliere lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Geeft het reguliere lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```


Geeft het symboollettertype terug of stelt het in als de bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```


Geeft het symboollettertype terug of stelt het in als de bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```


Geeft het Aziatische lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```


Geeft het Aziatische lettertype terug of stelt het in als de bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Haalt het wachtwoord op of stelt het in. Lezen/schrijven String.

Waarde: Het wachtwoord.

**Retour:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


Haalt het wachtwoord op of stelt het in. Lezen/schrijven String.

Waarde: Het wachtwoord.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```


Deze eigenschap is relevant als het presentatiebestand met wachtwoord is beveiligd. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering geworpen. Lezen/schrijven boolean.

**Retour:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```


Deze eigenschap is relevant als het presentatiebestand met wachtwoord is beveiligd. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering geworpen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retour:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```


Stelt de opties voor die gebruikt kunnen worden om het gedrag van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste prestatie-/geheugengebruikverhouding voor een specifieke omgeving of vereisten in te stellen.

--------------------

Een Binary Large Object (BLOB) is een binaire gegevensopslag als één entiteit – d.w.z. een BLOB kan een audio, video of de presentatie zelf zijn.

**Retour:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```


Stelt de opties voor die gebruikt kunnen worden om het gedrag van Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste prestatie-/geheugengebruikverhouding voor een specifieke omgeving of vereisten in te stellen.

--------------------

Een Binary Large Object (BLOB) is een binaire gegevensopslag als één entiteit – d.w.z. een BLOB kan een audio, video of de presentatie zelf zijn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```


Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties

**Retour:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```


Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```


Het token om onderbrekingsverzoeken te monitoren.

--------------------

Dit token beheert de gehele levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken via het aanroepen van de [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-methode van de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Retour:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```


Het token om onderbrekingsverzoeken te monitoren.

--------------------

Dit token beheert de gehele levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken via het aanroepen van de [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-methode van de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```


Geeft de callback-interface terug of stelt deze in die het laden van externe bronnen beheert. Lezen/schrijven [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Retour:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Geeft de callback-interface terug of stelt deze in die het laden van externe bronnen beheert. Lezen/schrijven [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```


Stelt opties voor die gebruikt kunnen worden om extra spreadsheet-gedrag te specificeren.

**Retour:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Stelt opties voor die gebruikt kunnen worden om extra spreadsheet-gedrag te specificeren.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```


Geeft de standaardtaal voor presentatietekst terug of stelt deze in. Lezen/schrijven String.

--------------------

> ```
> Example:
>   
>  // Gebruik load options om de standaardtekstcultuur te definiëren
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Voeg een nieuwe rechthoekige vorm toe met tekst
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Controleer de taal van het eerste gedeelte
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```


Geeft de standaardtaal voor presentatietekst terug of stelt deze in. Lezen/schrijven String.

--------------------

> ```
> Example:
>   
>  // Gebruik load options om de standaardtekstcultuur te definiëren
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Voeg een nieuwe rechthoekige vorm toe met tekst
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```


Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

De typen van de ingebedde binaire objecten:

 *  
 *  
 *  

Lezen/schrijven  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Standaard is  **false** .

**Retour:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```


Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie.

De typen van de ingebedde binaire objecten:

 *  
 *  
 *  

Lezen/schrijven  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Standaard is  **false** .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |