---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Bináris Nagy Objektum (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – azaz.
type: docs
url: /hu/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

A Bináris Nagy Objektum (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – azaz a BLOB lehet hang, videó vagy maga a bemutató. Számos technikát használnak a memóriafogyasztás optimalizálására a BLOB-ok kezelése közben – legyen az már a bemutatóban tárolt vagy később programozottan hozzáadott. A [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) használatával megváltoztathatja a BLOB-ok kezelésével kapcsolatos különböző viselkedési szempontokat a [IPresentation](../../com.aspose.slides/ipresentation) példány élettartama alatt.

## Módszerek

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás - fájl vagy adatfolyam - tulajdonosa a példány élettartama alatt. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás - fájl vagy adatfolyam - tulajdonosa a példány élettartama alatt. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami nagymértékben csökkenti a memóriafogyasztást, de fájlok létrehozásához engedélyre van szükség. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami nagymértékben csökkenti a memóriafogyasztást, de fájlok létrehozásához engedélyre van szükség. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Az az alapút, ahol az ideiglenes fájlok létrejönnek. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Az az alapút, ahol az ideiglenes fájlok létrejönnek. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás - fájl vagy adatfolyam - tulajdonosa a példány élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít javítani a memóriafogyasztást és a teljesítményt a BLOB-ok kezelése közben, de a forrás (adatfolyam vagy fájl) nem változtatható meg a Presentation példány élettartama alatt. Ez egy példa:

--------------------
> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kivétel lesz dobva, mert a pres.pptx egy Presentation élettartama alatt zárolva van
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // a Presentation objektum felszabadítása után a fájl feloldódik és törölhető
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Visszatér:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás - fájl vagy adatfolyam - tulajdonosa a példány élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít javítani a memóriafogyasztást és a teljesítményt a BLOB-ok kezelése közben, de a forrás (adatfolyam vagy fájl) nem változtatható meg a Presentation példány élettartama alatt. Ez egy példa:

--------------------
> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kivétel kerül dobásra, mert a pres.pptx egy Presentation élettartama alatt zárolva van
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // a Presentation objektum felszabadítása után a fájl feloldódik és törölhető
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami nagymértékben csökkenti a memóriafogyasztást, de fájlok létrehozásához engedélyre van szükség.

--------------------
Minden fájl törlésre kerül a bemutatóval végzett munka befejezése után.

**Visszatér:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami nagymértékben csökkenti a memóriafogyasztást, de fájlok létrehozásához engedélyre van szükség.

--------------------
Minden fájl törlésre kerül a bemutatóval végzett munka befejezése után.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Az az alapút, ahol az ideiglenes fájlok létrejönnek. Alapértelmezés szerint a rendszer ideiglenes könyvtára lesz használva. A futtató folyamatnak rendelkeznie kell engedéllyel a fájlok és mappák létrehozásához ott.

**Visszatér:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Az az alapút, ahol az ideiglenes fájlok létrejönnek. Alapértelmezés szerint a rendszer ideiglenes könyvtára lesz használva. A futtató folyamatnak rendelkeznie kell engedéllyel a fájlok és mappák létrehozásához ott.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak amikor ez a határ elérésekor kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása a legjobb teljesítményt biztosítja, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezetéhez vagy követelményeihez való igazításra.

--------------------
Ez a tulajdonság figyelmen kívül marad, ha \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) hamisra van állítva, mivel ilyenkor a memória az egyetlen rendelkezésre álló tárolási hely, és az in-memory BLOB használat korlátozása nincs hatással.

--------------------
Az alapértelmezett érték 629 145 600 bájt (600 MB).

--------------------
Beállíthatja ezt a tulajdonságot nullára, de egy kis minimális memória mennyiség továbbra is fenntartásra kerül.

**Visszatér:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak amikor ez a határ elérésekor kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása a legjobb teljesítményt biztosítja, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezetéhez vagy követelményeihez való igazításra.

--------------------
Ez a tulajdonság figyelmen kívül marad, ha \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) hamisra van állítva, mivel ilyenkor a memória az egyetlen rendelkezésre álló tárolási hely, és az in-memory BLOB használat korlátozása nincs hatással.

--------------------
Az alapértelmezett érték 629 145 600 bájt (600 MB).

--------------------
Beállíthatja ezt a tulajdonságot nullára, de egy kis minimális memória mennyiség továbbra is fenntartásra kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |