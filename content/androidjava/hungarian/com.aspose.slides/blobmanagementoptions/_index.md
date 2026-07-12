---
title: BlobManagementOptions
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: Azok az opciók, amelyeket a BLOB kezelési szabályok és egyéb BLOB beállítások kezelésére használhatók.
type: docs
url: /hu/com.aspose.slides/blobmanagementoptions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Az opciókat képviseli, amelyeket a BLOB kezelési szabályok és egyéb BLOB beállítások kezelésére lehet használni.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Új alapértelmezett blob-kezelési beállításokat hoz létre. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Ez a tulajdonság határozza meg, hogy a Presentation osztály egy példánya lehet-e a forrás — fájl vagy adatfolyam tulajdonosa az instance életciklusa során. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Ez a tulajdonság határozza meg, hogy a Presentation osztály egy példánya lehet-e a forrás — fájl vagy adatfolyam tulajdonosa az instance életciklusa során. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Ez a tulajdonság határozza meg, hogy ideiglenes fájlok hozhatók-e létre a BLOB-ok használata közben, ami jelentősen csökkenti a memóriahasználatot, de fájlok létrehozásához jogosultságot igényel. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Ez a tulajdonság határozza meg, hogy ideiglenes fájlok hozhatók-e létre a BLOB-ok használata közben, ami jelentősen csökkenti a memóriahasználatot, de fájlok létrehozásához jogosultságot igényel. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Az az alap útvonal, ahol az ideiglenes fájlok létrejönnek. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Az az alap útvonal, ahol az ideiglenes fájlok létrejönnek. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Meghatározza a maximális összes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Meghatározza a maximális összes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Új alapértelmezett blob-kezelési beállításokat hoz létre.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Ez a tulajdonság határozza meg, hogy a Presentation osztály egy példánya lehet-e a forrás — fájl vagy adatfolyam tulajdonosa az instance életciklusa során. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és javítja a teljesítményt BLOB-ok használata közben, de a forrás (adatfolyam vagy fájl) nem módosítható a Presentation példány életciklusa alatt.

**Visszatérési érték:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Ez a tulajdonság határozza meg, hogy a Presentation osztály egy példánya lehet-e a forrás — fájl vagy adatfolyam tulajdonosa az instance életciklusa során. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és javítja a teljesítményt BLOB-ok használata közben, de a forrás (adatfolyam vagy fájl) nem módosítható a Presentation példány életciklusa alatt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Ez a tulajdonság határozza meg, hogy ideiglenes fájlok hozhatók-e létre a BLOB-ok használata közben, ami jelentősen csökkenti a memóriahasználatot, de fájlok létrehozásához jogosultságot igényel.

--------------------

Minden fájl törlésre kerül a prezentációval végzett munka befejezése után.

**Visszatérési érték:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Ez a tulajdonság határozza meg, hogy ideiglenes fájlok hozhatók-e létre a BLOB-ok használata közben, ami jelentősen csökkenti a memóriahasználatot, de fájlok létrehozásához jogosultságot igényel.

--------------------

Minden fájl törlésre kerül a prezentációval végzett munka befejezése után.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Az az alap útvonal, ahol az ideiglenes fájlok létrejönnek. Alapértelmezés szerint a rendszer ideiglenes könyvtárát használja. A hosztoló folyamatnak jogosultsággal kell rendelkeznie a fájlok és mappák létrehozásához ezen a helyen.

**Visszatérési érték:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Az az alap útvonal, ahol az ideiglenes fájlok létrejönnek. Alapértelmezés szerint a rendszer ideiglenes könyvtárát használja. A hosztoló folyamatnak jogosultsággal kell rendelkeznie a fájlok és mappák létrehozásához ezen a helyen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Meghatározza a maximális összes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak amikor ez a határ elérődik, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez igazításához.

--------------------

Ez a tulajdonság figyelmen kívül marad, ha \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) hamisra van állítva, mivel ekkor a memória az egyetlen rendelkezésre álló tárolási hely, és a memóriában lévő BLOB használat korlátozása nem jár hatással.

--------------------

Az alapértelmezett érték 629 145 600 bájt (600 MB).

--------------------

Beállíthatja ezt a tulajdonságot nullára, de a memória egy kis minimális mennyisége továbbra is lefoglalásra kerül.

**Visszatérési érték:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Meghatározza a maximális összes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak amikor ez a határ elérődik, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez igazításához.

--------------------

Ez a tulajdonság figyelmen kívül marad, ha \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) hamisra van állítva, mivel ekkor a memória az egyetlen rendelkezésre álló tárolási hely, és a memóriában lévő BLOB használat korlátozása nem jár hatással.

--------------------

Az alapértelmezett érték 629 145 600 bájt (600 MB).

--------------------

Beállíthatja ezt a tulajdonságot nullára, de a memória egy kis minimális mennyisége továbbra is lefoglalásra kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |