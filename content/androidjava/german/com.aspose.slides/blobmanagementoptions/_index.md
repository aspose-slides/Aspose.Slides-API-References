---
title: BlobManagementOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Optionen dar, die verwendet werden können, um BLOB-Verarbeitungsregeln und andere BLOB-Einstellungen zu verwalten.
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

Stellt Optionen dar, die verwendet werden können, um BLOB-Verarbeitungsregeln und andere BLOB-Einstellungen zu verwalten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Erstellt neue Standard-Blob-Verwaltungsoptionen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Diese Eigenschaft definiert, ob eine Instanz der Presentation Klasse Eigentümer der Quell-Datei oder des Streams während der Lebensdauer der Instanz sein kann. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Diese Eigenschaft definiert, ob eine Instanz der Presentation Klasse Eigentümer der Quell-Datei oder des Streams während der Lebensdauer der Instanz sein kann. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Diese Eigenschaft definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark verringert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Diese Eigenschaft definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark verringert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definiert die maximale Gesamtsumme (in Bytes), die alle BLOBs im Speicher belegen dürfen. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definiert die maximale Gesamtsumme (in Bytes), die alle BLOBs im Speicher belegen dürfen. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Erstellt neue Standard-Blob-Verwaltungsoptionen.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Diese Eigenschaft definiert, ob eine Instanz der Presentation Klasse Eigentümer der Quell-Datei oder des Streams während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, wird die Quelle gesperrt. Dies hilft, den Speicherverbrauch und die Leistung bei der Arbeit mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Presentation-Instanz nicht geändert werden.

**Rückgabe:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Diese Eigenschaft definiert, ob eine Instanz der Presentation Klasse Eigentümer der Quell-Datei oder des Streams während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, wird die Quelle gesperrt. Dies hilft, den Speicherverbrauch und die Leistung bei der Arbeit mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Presentation-Instanz nicht geändert werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Diese Eigenschaft definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark verringert, aber Berechtigungen zum Erstellen von Dateien erfordert.

--------------------

Alle Dateien werden nach Abschluss der Arbeit mit der Präsentation gelöscht.

**Rückgabe:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Diese Eigenschaft definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark verringert, aber Berechtigungen zum Erstellen von Dateien erfordert.

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

Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. System-Temporärverzeichnis wird standardmäßig verwendet. Der Host-Prozess sollte dort über Berechtigungen zum Erstellen von Dateien und Ordnern verfügen.

**Rückgabe:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. System-Temporärverzeichnis wird standardmäßig verwendet. Der Host-Prozess sollte dort über Berechtigungen zum Erstellen von Dateien und Ordnern verfügen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Definiert die maximale Gesamtsumme (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) verwendet. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

--------------------

This property is ignored if \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect.

--------------------

Der Standardwert ist 629,145,600 Bytes (600 MB).

--------------------

Sie können diese Eigenschaft auf Null setzen, aber ein kleiner Mindestwert an Speicher wird weiterhin reserviert.

**Rückgabe:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Definiert die maximale Gesamtsumme (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) verwendet. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

--------------------

This property is ignored if \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect.

--------------------

Der Standardwert ist 629,145,600 Bytes (600 MB).

--------------------

Sie können diese Eigenschaft auf Null setzen, aber ein kleiner Mindestwert an Speicher wird weiterhin reserviert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |