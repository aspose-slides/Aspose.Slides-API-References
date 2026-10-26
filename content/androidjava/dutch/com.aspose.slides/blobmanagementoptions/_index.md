---
title: BlobManagementOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt opties voor die kunnen worden gebruikt om BLOB-behandelingsregels en andere BLOB-instellingen te beheren.
type: docs
url: /nl/com.aspose.slides/blobmanagementoptions/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Stelt opties voor die gebruikt kunnen worden om BLOB-behandelingsregels en andere BLOB-instellingen te beheren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Maakt nieuwe standaard blob-beheeropties. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Deze eigenschap definieert of een instantie van de Presentation-klasse eigenaar kan zijn van de bron-bestand of -stroom gedurende de levensduur van de instantie. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Deze eigenschap definieert of een instantie van de Presentation-klasse eigenaar kan zijn van de bron-bestand of -stroom gedurende de levensduur van de instantie. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Deze eigenschap definieert of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB’s, wat het geheugenverbruik sterk vermindert maar waarvoor toestemming nodig is om bestanden te maken. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Deze eigenschap definieert of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB’s, wat het geheugenverbruik sterk vermindert maar waarvoor toestemming nodig is om bestanden te maken. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Het hoofdpad waar tijdelijke bestanden worden aangemaakt. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Het hoofdpad waar tijdelijke bestanden worden aangemaakt. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definieert de maximale totale grootte (in bytes) die alle BLOB’s in het geheugen mogen innemen. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definieert de maximale totale grootte (in bytes) die alle BLOB’s in het geheugen mogen innemen. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


Maakt nieuwe standaard blob-beheeropties.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


Deze eigenschap definieert of een instantie van de Presentation-klasse eigenaar kan zijn van de bron-bestand of -stroom gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit verbetert het geheugenverbruik en de prestaties bij het werken met BLOB’s, maar de bron (stroom of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie.

**Returns:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


Deze eigenschap definieert of een instantie van de Presentation-klasse eigenaar kan zijn van de bron-bestand of -stroom gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit verbetert het geheugenverbruik en de prestaties bij het werken met BLOB’s, maar de bron (stroom of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


Deze eigenschap definieert of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB’s, wat het geheugenverbruik sterk vermindert maar waarvoor toestemming nodig is om bestanden te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is afgerond.

**Returns:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


Deze eigenschap definieert of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB’s, wat het geheugenverbruik sterk vermindert maar waarvoor toestemming nodig is om bestanden te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is afgerond.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


Het hoofdpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeem-tijdelijke map gebruikt. Het host-proces moet permissies hebben om daar bestanden en mappen aan te maken.

**Returns:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


Het hoofdpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeem-tijdelijke map gebruikt. Het host-proces moet permissies hebben om daar bestanden en mappen aan te maken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


Definieert de maximale totale grootte (in bytes) die alle BLOB’s in het geheugen mogen innemen. Standaard worden alle BLOB’s in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) ingezet. BLOB’s in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of eisen.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) op false is ingesteld, aangezien geheugen dan de enige opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

--------------------

De standaardwaarde is 629 145 600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul zetten, maar er wordt nog steeds een klein minimum aan geheugen gereserveerd.

**Returns:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


Definieert de maximale totale grootte (in bytes) die alle BLOB’s in het geheugen mogen innemen. Standaard worden alle BLOB’s in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) ingezet. BLOB’s in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of eisen.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) op false is ingesteld, aangezien geheugen dan de enige opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

--------------------

De standaardwaarde is 629 145 600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul zetten, maar er wordt nog steeds een klein minimum aan geheugen gereserveerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |