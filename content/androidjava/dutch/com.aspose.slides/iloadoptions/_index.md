---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe extra opties op te geven, zoals formaat of standaardlettertype, bij het laden van een presentatie.
type: docs
url: /nl/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Staat toe extra opties (zoals formaat of standaardlettertype) op te geven bij het laden van een presentatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Retourneert of stelt het formaat van een te laden presentatie in. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Retourneert of stelt het formaat van een te laden presentatie in. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Retourneert of stelt het reguliere lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Retourneert of stelt het reguliere lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Retourneert of stelt het symboollettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Retourneert of stelt het symboollettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [getPassword()](#getPassword--) | Haalt of stelt het wachtwoord in. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Haalt of stelt het wachtwoord in. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Deze eigenschap heeft zin als het presentatie-bestand met een wachtwoord beveiligd is. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Deze eigenschap heeft zin als het presentatie-bestand met een wachtwoord beveiligd is. |
| [getWarningCallback()](#getWarningCallback--) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag bij het verwerken van Binary Large Objects (BLOB’s) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag bij het verwerken van Binary Large Objects (BLOB’s) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Bepaalt bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Bepaalt bronnen voor externe lettertypen die door de presentatie worden gebruikt. |
| [getInterruptionToken()](#getInterruptionToken--) | Het token om te monitoren op onderbrekingsverzoeken. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Het token om te monitoren op onderbrekingsverzoeken. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Vertegenwoordigt opties die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Vertegenwoordigt opties die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Retourneert of stelt de standaardtaal voor presentatietekst in. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Retourneert of stelt de standaardtaal voor presentatietekst in. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Retourneert of stelt het formaat van een te laden presentatie in. Lezen/schrijven [LoadFormat](../../com.aspose.slides/loadformat).

**Retour:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Retourneert of stelt het formaat van een te laden presentatie in. Lezen/schrijven [LoadFormat](../../com.aspose.slides/loadformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Retourneert of stelt het reguliere lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Retourneert of stelt het reguliere lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Retourneert of stelt het symboollettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Retourneert of stelt het symboollettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Retour:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Retourneert of stelt het Aziatische lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Haalt of stelt het wachtwoord in. Lezen/schrijven String.

Value: Het wachtwoord.

**Retour:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Haalt of stelt het wachtwoord in. Lezen/schrijven String.

Value: Het wachtwoord.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Deze eigenschap heeft zin als het presentatie-bestand met een wachtwoord beveiligd is. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld bestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschap altijd genegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschap true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Lezen/schrijven boolean.

**Retour:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Deze eigenschap heeft zin als het presentatie-bestand met een wachtwoord beveiligd is. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld bestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschap altijd genegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschap true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retour:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag bij het verwerken van Binary Large Objects (BLOB’s) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste performance/geheugengebruik-verhouding voor een bepaalde omgeving of vereiste in te stellen.

--------------------

Een Binary Large Object (BLOB) is binaire data die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio-, video- of de presentatie zelf zijn.

**Retour:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Vertegenwoordigt de opties die kunnen worden gebruikt om het gedrag bij het verwerken van Binary Large Objects (BLOB’s) te beheren, zoals het gebruik van tijdelijke bestanden of maximale BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste performance/geheugengebruik-verhouding voor een bepaalde omgeving of vereiste in te stellen.

--------------------

Een Binary Large Object (BLOB) is binaire data die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio-, video- of de presentatie zelf zijn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Bepaalt bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties.

**Retour:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Bepaalt bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Het token om te monitoren op onderbrekingsverzoeken.

--------------------

Dit token beheert de volledige [IPresentation](../../com.aspose.slides/ipresentation)-instantielevensduur. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-methode van de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Retour:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Het token om te monitoren op onderbrekingsverzoeken.

--------------------

Dit token beheert de volledige [IPresentation](../../com.aspose.slides/ipresentation)-instantielevensduur. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-methode van de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. Lezen/schrijven [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Retour:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Retourneert of stelt de callback-interface in die het laden van externe bronnen beheert. Lezen/schrijven [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Vertegenwoordigt opties die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren.

**Retour:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Vertegenwoordigt opties die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Retourneert of stelt de standaardtaal voor presentatietekst in. Lezen/schrijven String.

--------------------

> ```
> Example:
>   
>  // Gebruik laadinopties om de standaardtekstcultuur te definiëren
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

Retourneert of stelt de standaardtaal voor presentatietekst in. Lezen/schrijven String.

--------------------

> ```
> Example:
>   
>  // Gebruik laadinopties om de standaardtekstcultuur te definiëren
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

Lezen/schrijven boolean.

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

Standaard is **false**.

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

Lezen/schrijven boolean.

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

Standaard is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |