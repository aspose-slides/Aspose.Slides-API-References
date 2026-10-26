---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: Een Binary Large Object BLOB is een binaire gegevens die als één entiteit is opgeslagen - dwz
type: docs
url: /nl/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Een Binary Large Object (BLOB) is een binaire gegevens die als één entiteit is opgeslagen - dwz kan een BLOB een audio, video of de presentatie zelf zijn. Er worden verschillende technieken gebruikt om het geheugenverbruik te optimaliseren tijdens het werken met BLOB's - die al in de presentatie zijn opgeslagen of later programmeermatig kunnen worden toegevoegd. Met [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) kunt u verschillende gedragsaspecten met betrekking tot het omgaan met BLOB's wijzigen voor de levensduur van de [IPresentation](../../com.aspose.slides/ipresentation) instantie.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```


Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream – gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOB's, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie. Dit is een voorbeeld:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Er wordt een IOException gegooid omdat pres.pptx vergrendeld is voor de levensduur van een Presentation.
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // nadat het Presentation-object is vrijgegeven, is het bestand ontgrendeld en kan het worden verwijderd.
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Retour:**  
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```


Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream – gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOB's, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie. Dit is een voorbeeld:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException wordt gegooid omdat pres.pptx vergrendeld is voor de levensduur van een Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // nadien is het Presentation object vrijgegeven, bestand is ontgrendeld en kan worden verwijderd
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```


Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik sterk vermindert maar wel permissies vereist om bestanden aan te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is voltooid.

**Retour:**  
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```


Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik sterk vermindert maar wel permissies vereist om bestanden aan te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is voltooid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```


Het rootpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeemtijdelijke map gebruikt. Het hostproces moet hier toestemming hebben om bestanden en mappen aan te maken.

**Retour:**  
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```


Het rootpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeemtijdelijke map gebruikt. Het hostproces moet hier toestemming hebben om bestanden en mappen aan te maken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```


Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. BLOB's in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) op false is ingesteld, aangezien het geheugen dan de enige beschikbare opslaglocatie is en het beperken van BLOB's in het geheugen geen effect heeft.

--------------------

De standaardwaarde is 629.145.600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd.

**Retour:**  
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```


Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. BLOB's in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) op false is ingesteld, aangezien het geheugen dan de enige beschikbare opslaglocatie is en het beperken van BLOB's in het geheugen geen effect heeft.

--------------------

De standaardwaarde is 629.145.600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |