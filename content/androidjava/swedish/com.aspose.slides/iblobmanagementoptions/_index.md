---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: En binär stor objekt (BLOB) är binära data lagrade som en enda enhet - d.v.s. ett BLOB kan vara ett ljud, video eller själva presentationen.
type: docs
url: /sv/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Ett binärt stort objekt (BLOB) är binära data lagrade som en enda enhet – d.v.s. ett BLOB kan vara ett ljud, video eller själva presentationen. Ett antal tekniker används för att optimera minnesanvändningen när man arbetar med BLOB-objekt – som redan lagrats i presentationen eller som kan läggas till senare programmässigt. Med hjälp av [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) kan du ändra olika beteendeaspekter för hantering av BLOB-objekt för [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid.

## Metoder

| Method | Description |
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

Denna egenskap anger om en instans av Presentation-klassen kan vara ägare till källan – fil eller ström – under instansens livstid. Om instansen är ägare låses källan. Detta hjälper till att förbättra minnesanvändning och prestanda när man arbetar med BLOB-objekt, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid. Detta är ett exempel:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kommer att kastas eftersom pres.pptx är låst under Presentationens livstid
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // efter att Presentation-objektet har frigjorts, är filen olåst och kan raderas
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Returns:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Denna egenskap anger om en instans av Presentation-klassen kan vara ägare till källan – fil eller ström – under instansens livstid. Om instansen är ägare låses källan. Detta hjälper till att förbättra minnesanvändning och prestanda när man arbetar med BLOB-objekt, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid. Detta är ett exempel:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kommer att kastas eftersom pres.pptx är låst under Presentationens livstid
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // efter att Presentation-objektet har frigjorts, är filen olåst och kan raderas
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Denna egenskap anger om tillfälliga filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt minskar minnesanvändningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas när arbetet med presentationen är avklarat.

**Returns:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Denna egenskap anger om tillfälliga filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt minskar minnesanvändningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas när arbetet med presentationen är avklarat.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Rotvägen där tillfälliga filer kommer att skapas. Systemets temporära katalog används som standard. Värdprocessen bör ha behörighet att skapa filer och mappar där.

**Returns:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Rotvägen där tillfälliga filer kommer att skapas. Systemets temporära katalog används som standard. Värdprocessen bör ha behörighet att skapa filer och mappar där.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt in i minnet; först när denna gräns nås används alternativa mekanismer (t.ex. tillfälliga filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimummängd minne kommer fortfarande att reserveras.

**Returns:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt in i minnet; först när denna gräns nås används alternativa mekanismer (t.ex. tillfälliga filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimummängd minne kommer fortfarande att reserveras.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |