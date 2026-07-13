---
title: BlobManagementOptions
second_title: Aspose.Slides för Android via Java API-referens
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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Skapar nya standardalternativ för blob-hantering. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källan – fil eller ström under instansens livstid. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källan – fil eller ström under instansens livstid. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Denna egenskap definierar om tillfälliga filer kan skapas medan man arbetar med BLOBs, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Denna egenskap definierar om tillfälliga filer kan skapas medan man arbetar med BLOBs, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Rotkatalogen där tillfälliga filer kommer att skapas. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Rotkatalogen där tillfälliga filer kommer att skapas. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Skapar nya standardalternativ för blob-hantering.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källan – fil eller ström under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper till att förbättra minnesförbrukning och prestanda vid arbete med BLOBs, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid.

**Returnerar:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källan – fil eller ström under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper till att förbättra minnesförbrukning och prestanda vid arbete med BLOBs, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Denna egenskap definierar om tillfälliga filer kan skapas medan man arbetar med BLOBs, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas efter att arbetet med presentationen är slutfört.

**Returnerar:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Denna egenskap definierar om tillfälliga filer kan skapas medan man arbetar med BLOBs, vilket kraftigt minskar minnesförbrukningen men kräver behörighet att skapa filer.

--------------------

Alla filer kommer att raderas efter att arbetet med presentationen är slutfört.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Rotkatalogen där tillfälliga filer kommer att skapas. Systemets temporära katalog kommer att användas som standard. Värdprocessen bör ha behörighet att skapa filer och mappar där.

**Returnerar:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Rotkatalogen där tillfälliga filer kommer att skapas. Systemets temporära katalog kommer att användas som standard. Värdprocessen bör ha behörighet att skapa filer och mappar där.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (som tillfälliga filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimalt minnesutrymme kommer fortfarande att reserveras.

**Returnerar:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (som tillfälliga filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

--------------------

Denna egenskap ignoreras om \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) är satt till false, eftersom minnet då är den enda lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

--------------------

Standardvärdet är 629 145 600 byte (600 MB).

--------------------

Du kan sätta denna egenskap till noll, men ett litet minimalt minnesutrymme kommer fortfarande att reserveras.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |