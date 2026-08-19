---
title: BlobManagementOptions
second_title: Aspose.Slides för Java API-referens
description: Representerar alternativ som kan användas för att hantera BLOB-hanteringsregler och andra BLOB-inställningar.
type: docs
url: /sv/com.aspose.slides/blobmanagementoptions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Representerar alternativ som kan användas för att hantera BLOB-hanteringsregler och andra BLOB-inställningar.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Skapar nya standardalternativ för BLOB-hantering. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källfilen eller strömmen under instansens livstid. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källfilen eller strömmen under instansens livstid. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Denna egenskap definierar om tillfälliga filer kan skapas under arbete med BLOB-objekt, vilket kraftigt minskar minnesanvändningen men kräver behörighet att skapa filer. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Denna egenskap definierar om tillfälliga filer kan skapas under arbete med BLOB-objekt, vilket kraftigt minskar minnesanvändningen men kräver behörighet att skapa filer. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Rotvägen där tillfälliga filer kommer att skapas. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Rotvägen där tillfälliga filer kommer att skapas. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


Skapar nya standardalternativ för BLOB-hantering.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källfilen eller strömmen under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper till att förbättra minnesanvändning och prestanda vid arbete med BLOB-objekt, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid.

**Returnerar:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källfilen eller strömmen under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper till att förbättra minnesanvändning och prestanda vid arbete med BLOB-objekt, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


Denna egenskap definierar om tillfälliga filer kan skapas under arbete med BLOB-objekt, vilket kraftigt minskar minnesanvändningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas när arbetet med presentationen är slutfört.

**Returnerar:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


Denna egenskap definierar om tillfälliga filer kan skapas under arbete med BLOB-objekt, vilket kraftigt minskar minnesanvändningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas när arbetet med presentationen är slutfört.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


Rotvägen där tillfälliga filer kommer att skapas. Systemets temporära katalog används som standard. Gästprocessen måste ha behörighet att skapa filer och mappar där.

**Returnerar:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


Rotvägen där tillfälliga filer kommer att skapas. Systemets temporära katalog används som standard. Gästprocessen måste ha behörighet att skapa filer och mappar där.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt in i minnet; först när denna gräns nås används alternativa mekanismer (såsom tillfälliga filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimum av minne kommer fortfarande att reserveras.

**Returnerar:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt in i minnet; först när denna gräns nås används alternativa mekanismer (såsom tillfälliga filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimum av minne kommer fortfarande att reserveras.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |