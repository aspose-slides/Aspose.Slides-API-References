---
title: BlobManagementOptions
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Optionen dar, die zur Verwaltung von BLOB-Verarbeitungsregeln und anderen BLOB-Einstellungen verwendet werden können.
type: docs
url: /de/com.aspose.slides/blobmanagementoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Repräsentiert Optionen, die zur Verwaltung von BLOB-Verarbeitungsregeln und anderen BLOB-Einstellungen verwendet werden können.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Erstellt neue Standard-Blob-Verwaltungsoptionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelldatei oder des Streams während der Lebensdauer der Instanz sein kann. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelldatei oder des Streams während der Lebensdauer der Instanz sein kann. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Diese Eigenschaft definiert, ob temporäre Dateien erstellt werden können, während mit BLOBs gearbeitet wird, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Diese Eigenschaft definiert, ob temporäre Dateien erstellt werden können, während mit BLOBs gearbeitet wird, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definiert die maximale Gesamtspeichergröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definiert die maximale Gesamtspeichergröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


Erstellt neue Standard-Blob-Verwaltungsoptionen.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelldatei oder des Streams während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Presentation-Instanz nicht geändert werden.

**Rückgabewert:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelldatei oder des Streams während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Presentation-Instanz nicht geändert werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


Diese Eigenschaft definiert, ob temporäre Dateien erstellt werden können, während mit BLOBs gearbeitet wird, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert.

--------------------

Alle Dateien werden nach Abschluss der Arbeit mit der Präsentation gelöscht.

**Rückgabewert:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


Diese Eigenschaft definiert, ob temporäre Dateien erstellt werden können, während mit BLOBs gearbeitet wird, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert.

--------------------

Alle Dateien werden nach Abschluss der Arbeit mit der Präsentation gelöscht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. Standardmäßig wird das System-Temp-Verzeichnis verwendet. Der hostende Prozess muss Berechtigungen zum Erstellen von Dateien und Ordnern dort besitzen.

**Rückgabewert:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. Standardmäßig wird das System-Temp-Verzeichnis verwendet. Der hostende Prozess muss Berechtigungen zum Erstellen von Dateien und Ordnern dort besitzen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


Definiert die maximale Gesamtspeichergröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

--------------------

Diese Eigenschaft wird ignoriert, wenn \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) auf false gesetzt ist, da dann der Speicher der einzige verfügbare Speicherort ist und eine Begrenzung der in-Memory-BLOB-Nutzung keine Wirkung hat.

--------------------

Der Standardwert beträgt 629.145.600 Bytes (600 MB).

--------------------

Sie können diese Eigenschaft auf null setzen, aber ein kleiner Mindest-Speicherbedarf bleibt reserviert.

**Rückgabewert:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


Definiert die maximale Gesamtspeichergröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

--------------------

Diese Eigenschaft wird ignoriert, wenn \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) auf false gesetzt ist, da dann der Speicher der einzige verfügbare Speicherort ist und eine Begrenzung der in-Memory-BLOB-Nutzung keine Wirkung hat.

--------------------

Der Standardwert beträgt 629.145.600 Bytes (600 MB).

--------------------

Sie können diese Eigenschaft auf null setzen, aber ein kleiner Mindest-Speicherbedarf bleibt reserviert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |