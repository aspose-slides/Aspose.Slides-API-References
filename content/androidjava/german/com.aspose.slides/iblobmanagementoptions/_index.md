---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Ein Binary Large Object (BLOB) ist ein binärer Datensatz, der als einzelne Entität gespeichert wird – d. h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein.
type: docs
url: /de/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Ein Binary Large Object (BLOB) ist ein binärer Datensatz, der als einzelne Entität gespeichert wird – d. h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein. Eine Reihe von Techniken wird verwendet, um den Speicherverbrauch beim Arbeiten mit BLOBs zu optimieren – die bereits in der Präsentation gespeichert sind oder später programmatisch hinzugefügt werden können. Verwenden Sie [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) können Sie verschiedene Verhaltensaspekte im Umgang mit BLOBs für die Lebensdauer der [IPresentation](../../com.aspose.slides/ipresentation)-Instanz ändern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelle – Datei oder Stream – während der Lebensdauer der Instanz sein kann. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelle – Datei oder Stream – während der Lebensdauer der Instanz sein kann. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Diese Eigenschaft definiert, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Diese Eigenschaft definiert, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelle – Datei oder Stream – während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, wird die Quelle gesperrt. Das hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Presentation-Instanz nicht geändert werden. Dies ist ein Beispiel:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException wird ausgelöst, weil pres.pptx für die Lebensdauer einer Presentation gesperrt ist
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // nachdem das Presentation-Objekt freigegeben wurde, ist die Datei entsperrt und kann gelöscht werden
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Rückgabewert:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelle – Datei oder Stream – während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, wird die Quelle gesperrt. Das hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Presentation-Instanz nicht geändert werden. Dies ist ein Beispiel:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException wird ausgelöst, weil pres.pptx für die Lebensdauer einer Presentation gesperrt ist
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // nachdem das Presentation-Objekt freigegeben wurde, ist die Datei entsperrt und kann gelöscht werden
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Diese Eigenschaft definiert, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert.

--------------------

Alle Dateien werden nach Abschluss der Arbeit mit der Präsentation gelöscht.

**Rückgabewert:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Diese Eigenschaft definiert, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert.

--------------------

Alle Dateien werden nach Abschluss der Arbeit mit der Präsentation gelöscht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. Das System-Temporärverzeichnis wird standardmäßig verwendet. Der Hostprozess sollte über Berechtigungen zum Erstellen von Dateien und Ordnern dort verfügen.

**Rückgabewert:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. Das System-Temporärverzeichnis wird standardmäßig verwendet. Der Hostprozess sollte über Berechtigungen zum Erstellen von Dateien und Ordnern dort verfügen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, kommen alternative Mechanismen (wie temporäre Dateien) zum Einsatz. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

--------------------

Diese Eigenschaft wird ignoriert, wenn \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) auf false gesetzt ist, da dann der Speicher der einzige verfügbare Speicherort ist und eine Begrenzung der im Speicher befindlichen BLOB-Nutzung keine Wirkung hat.

--------------------

Der Standardwert beträgt 629.145.600 Bytes (600 MB).

--------------------

Sie können diese Eigenschaft auf null setzen, aber ein kleiner Mindestspeicherbetrag wird weiterhin reserviert.

**Rückgabewert:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, kommen alternative Mechanismen (wie temporäre Dateien) zum Einsatz. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

--------------------

Diese Eigenschaft wird ignoriert, wenn \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) auf false gesetzt ist, da dann der Speicher der einzige verfügbare Speicherort ist und eine Begrenzung der im Speicher befindlichen BLOB-Nutzung keine Wirkung hat.

--------------------

Der Standardwert beträgt 629.145.600 Bytes (600 MB).

--------------------

Sie können diese Eigenschaft auf null setzen, aber ein kleiner Mindestspeicherbetrag wird weiterhin reserviert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |