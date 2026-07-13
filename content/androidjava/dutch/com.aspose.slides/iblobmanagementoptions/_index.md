---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Een Binary Large Object (BLOB) is binaire data die als één entiteit wordt opgeslagen - d.w.z.
type: docs
url: /nl/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Een Binary Large Object (BLOB) is binaire data die als één entiteit wordt opgeslagen - d.w.z. BLOB kan een audio, video of de presentatie zelf zijn. Een aantal technieken worden gebruikt om het geheugenverbruik te optimaliseren bij het werken met BLOBs – die al in de presentatie zijn opgeslagen of later programmatisch worden toegevoegd. Met [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) kunt u verschillende gedragselementen met betrekking tot BLOB-verwerking voor de levensduur van de [IPresentation](../../com.aspose.slides/ipresentation)-instantie aanpassen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOBs, wat het geheugenverbruik sterk vermindert maar machtigingen vereist om bestanden te maken. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOBs, wat het geheugenverbruik sterk vermindert maar machtigingen vereist om bestanden te maken. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Het rootpad waar tijdelijke bestanden zullen worden aangemaakt. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Het rootpad waar tijdelijke bestanden zullen worden aangemaakt. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. Als de instantie een eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOBs, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie. Dit is een voorbeeld:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException wordt gegooid omdat pres.pptx vergrendeld is voor de levensduur van een Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // nadat het Presentation-object is afgevoerd, is het bestand ontgrendeld en kan het worden verwijderd
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Retour:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron – bestand of stream gedurende de levensduur van de instantie. Als de instantie een eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOBs, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie. Dit is een voorbeeld:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException wordt gegooid omdat pres.pptx vergrendeld is voor de levensduur van een Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // nadat het Presentation-object is afgevoerd, is het bestand ontgrendeld en kan het worden verwijderd
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

Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOBs, wat het geheugenverbruik sterk vermindert maar machtigingen vereist om bestanden te maken.

--------------------

Alle bestanden worden verwijderd nadat het werk met de presentatie is voltooid.

**Retour:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOBs, wat het geheugenverbruik sterk vermindert maar machtigingen vereist om bestanden te maken.

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

Het rootpad waar tijdelijke bestanden zullen worden aangemaakt. Standaard zal de tijdelijke directory van het systeem worden gebruikt. Het hostproces moet machtigingen hebben om daar bestanden en mappen aan te maken.

**Retour:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Het rootpad waar tijdelijke bestanden zullen worden aangemaakt. Standaard zal de tijdelijke directory van het systeem worden gebruikt. Het hostproces moet machtigingen hebben om daar bestanden en mappen aan te maken.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. Standaard worden alle BLOBs in het geheugen geladen; alleen wanneer deze limiet wordt bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. BLOBs in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of vereisten.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) op false staat, aangezien geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

--------------------

De standaardwaarde is 629.145.600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul instellen, maar er zal nog steeds een kleine minimale hoeveelheid geheugen gereserveerd worden.

**Retour:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. Standaard worden alle BLOBs in het geheugen geladen; alleen wanneer deze limiet wordt bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. BLOBs in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of vereisten.

--------------------

Deze eigenschap wordt genegeerd als \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) op false staat, aangezien geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

--------------------

De standaardwaarde is 629.145.600 bytes (600 MB).

--------------------

U kunt deze eigenschap op nul instellen, maar er zal nog steeds een kleine minimale hoeveelheid geheugen gereserveerd worden.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |