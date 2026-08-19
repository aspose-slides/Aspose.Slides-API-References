---
title: BlobManagementOptions
second_title: Aspose.Slides voor Java API-referentie
description: Stelt opties voor die gebruikt kunnen worden om BLOB-beheerregels en andere BLOB-instellingen te beheren.
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
| [BlobManagementOptions()](#BlobManagementOptions--) | Maakt nieuwe standaard blob-beheeropties aan. |

## Methods

| Methode | Beschrijving |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik sterk vermindert maar wel toestemming vereist om bestanden aan te maken. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik sterk vermindert maar wel toestemming vereist om bestanden aan te maken. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Het hoofdpad waar tijdelijke bestanden worden aangemaakt. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Het hoofdpad waar tijdelijke bestanden worden aangemaakt. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Maakt nieuwe standaard blob-beheeropties aan.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOB's, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie.

**Retour:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOB's, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik sterk vermindert maar wel toestemming vereist om bestanden aan te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is voltooid.

**Retour:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik sterk vermindert maar wel toestemming vereist om bestanden aan te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is voltooid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Het hoofdpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeem-tijdelijke map gebruikt. Het host-proces moet hier toestemming hebben om bestanden en mappen aan te maken.

**Retour:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Het hoofdpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeem-tijdelijke map gebruikt. Het host-proces moet hier toestemming hebben om bestanden en mappen aan te maken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanisms (zoals tijdelijke bestanden) ingezet. Het in-memory houden van BLOB's maximaliseert de prestaties, maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of eisen.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) is ingesteld op false, omdat het geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

--------------------

De standaardwaarde is 629,145,600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd.

**Retour:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanisms (zoals tijdelijke bestanden) ingezet. Het in-memory houden van BLOB's maximaliseert de prestaties, maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of eisen.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) is ingesteld op false, omdat het geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

--------------------

De standaardwaarde is 629,145,600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |