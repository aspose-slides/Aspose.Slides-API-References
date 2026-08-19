---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API-referens
description: En binär stor objekt (BLOB) är binär data lagrad som en enda entitet - t.ex.
type: docs
url: /sv/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Ett binärt stort objekt (BLOB) är binär data lagrad som en enda entitet – t.ex. kan BLOB vara ett ljud, video eller själva presentationen. Ett antal tekniker används för att optimera minnesanvändning när man arbetar med BLOB-objekt – som redan lagrats i presentationen eller läggs till senare programmässigt. Med [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) kan du ändra olika beteendeaspekter för hantering av BLOB-objekt för [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Denna egenskap definierar om en instans av klassen Presentation kan vara ägare till källan – fil eller ström under instansens livstid. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Denna egenskap definierar om en instans av klassen Presentation kan vara ägare till källan – fil eller ström under instansens livstid. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Denna egenskap definierar om temporära filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Denna egenskap definierar om temporära filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Rotvägen där temporära filer kommer att skapas. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Rotvägen där temporära filer kommer att skapas. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```


Denna egenskap definierar om en instans av klassen Presentation kan vara ägare till källan – fil eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper till att förbättra minnesförbrukningen och prestanda när man arbetar med BLOB-objekt, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid. Detta är ett exempel:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kommer att kastas eftersom pres.pptx är låst för en Presentation under hela livstiden
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // efter att Presentation-objektet har frigjorts, är filen olåst och kan raderas
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
>  ```


**Returnerar:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```


Denna egenskap definierar om en instans av klassen Presentation kan vara ägare till källan – fil eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper till att förbättra minnesförbrukningen och prestanda när man arbetar med BLOB-objekt, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid. Detta är ett exempel:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kommer att kastas eftersom pres.pptx är låst för en Presentation under hela livstiden
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // efter att Presentation-objektet har frigjorts, är filen olåst och kan raderas
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```


Denna egenskap definierar om temporära filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas efter att arbetet med presentationen är färdigt.

**Returnerar:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```


Denna egenskap definierar om temporära filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas efter att arbetet med presentationen är färdigt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```


Rotvägen där temporära filer kommer att skapas. Systemets temporära katalog används som standard. Värdprocessen bör ha behörighet att skapa filer och mappar där.

**Returnerar:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```


Rotvägen där temporära filer kommer att skapas. Systemets temporära katalog används som standard. Värdprocessen bör ha behörighet att skapa filer och mappar där.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```


Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om #isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen tillgänglig och begränsning av BLOB-användning i minnet inte har någon effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimalt minnesutrymme kommer fortfarande att reserveras.

**Returnerar:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```


Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om #isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen tillgänglig och begränsning av BLOB-användning i minnet inte har någon effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimalt minnesutrymme kommer fortfarande att reserveras.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |