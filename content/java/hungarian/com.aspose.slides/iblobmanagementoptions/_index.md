---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: A Binary Large Object BLOB egy bináris adat, amely egyetlen egységként van tárolva - i.e.
type: docs
url: /hu/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – BLOB lehet audio, video vagy maga a prezentáció. Számos technikát alkalmaznak a memóriafogyasztás optimalizálására BLOB-ok kezelésekor – legyenek azok már a prezentációban tároltak vagy később programozottan hozzáadottak. A [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) használatával módosíthatja a BLOB-ok kezelésének különböző viselkedési aspektusait a [IPresentation](../../com.aspose.slides/ipresentation) példány élettartama alatt.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás – fájl vagy adatfolyam – tulajdonosa a példány élettartama alatt. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás – fájl vagy adatfolyam – tulajdonosa a példány élettartama alatt. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami jelentősen csökkenti a memóriafogyasztást, de fájlok létrehozásához szükséges engedélyeket igényel. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami jelentősen csökkenti a memóriafogyasztást, de fájlok létrehozásához szükséges engedélyeket igényel. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Az az alapút, ahol az ideiglenes fájlok létre lesznek hozva. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Az az alapút, ahol az ideiglenes fájlok létre lesznek hozva. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Meghatározza a memóriahelyen a BLOB-ok által elfoglalható maximális összméretet (byte-ban). |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Meghatározza a memóriahelyen a BLOB-ok által elfoglalható maximális összméretet (byte-ban). |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás – fájl vagy adatfolyam – tulajdonosa a példány élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít a memóriafogyasztás és a teljesítmény javításában a BLOB-ok kezelésekor, de a forrás (adatfolyam vagy fájl) nem módosítható a Presentation példány élettartama alatt. Ez egy példa:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException kivétel keletkezik, mert a pres.pptx egy Presentation élettartamára zárolva van
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // a Presentation objektum felszabadítása után a fájl feloldódik, és törölhető
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Visszatérési érték:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás – fájl vagy adatfolyam – tulajdonosa a példány élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít a memóriafogyasztás és a teljesítmény javításában a BLOB-ok kezelésekor, de a forrás (adatfolyam vagy fájl) nem módosítható a Presentation példány élettartama alatt. Ez egy példa:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException lesz dobva, mert a pres.pptx egy Presentation élettartamára zárolva van
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

Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami jelentősen csökkenti a memóriafogyasztást, de fájlok létrehozásához szükséges engedélyeket igényel.

--------------------

Az összes fájl törlésre kerül, miután a prezentációval végzett munka befejeződött.

**Visszatérési érték:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami jelentősen csökkenti a memóriafogyasztást, de fájlok létrehozásához szükséges engedélyeket igényel.

--------------------

Az összes fájl törlésre kerül, miután a prezentációval végzett munka befejeződött.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Az az alapút, ahol az ideiglenes fájlok létre lesznek hozva. Alapértelmezés szerint a rendszer ideiglenes könyvtára lesz használva. A kiszolgáló folyamatnak engedélyekkel kell rendelkeznie a fájlok és mappák létrehozásához.

**Visszatérési érték:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Az az alapút, ahol az ideiglenes fájlok létre lesznek hozva. Alapértelmezés szerint a rendszer ideiglenes könyvtára lesz használva. A kiszolgáló folyamatnak engedélyekkel kell rendelkeznie a fájlok és mappák létrehozásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Meghatározza a memóriahelyen a BLOB-ok által elfoglalható maximális összméretet (byte-ban). Alapértelmezés szerint az összes BLOB memóriába kerül; csak amikor ez a határ eléri, alkalmaznak alternatív mechanizmusokat (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez igazításához.

--------------------

Ez a tulajdonság figyelmen kívül van hagyva, ha a \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) hamis értékre van állítva, mivel ekkor a memória az egyetlen rendelkezésre álló tárolási hely, és a memóriahelyi BLOB-használat korlátozása nem lesz hatással.

--------------------

Az alapértelmezett érték 629 145 600 byte (600 MB).

--------------------

Beállíthatja ezt a tulajdonságot nullára, de még így is egy kis minimális memóriafoglalás megtartásra kerül.

**Visszatérési érték:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Meghatározza a memóriahelyen a BLOB-ok által elfoglalható maximális összméretet (byte-ban). Alapértelmezés szerint az összes BLOB memóriába kerül; csak amikor ez a határ eléri, alkalmaznak alternatív mechanizmusokat (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez igazításához.

--------------------

Ez a tulajdonság figyelmen kívül van hagyva, ha a \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) hamis értékre van állítva, mivel ekkor a memória az egyetlen rendelkezésre álló tárolási hely, és a memóriahelyi BLOB-használat korlátozása nem lesz hatással.

--------------------

Az alapértelmezett érték 629 145 600 byte (600 MB).

--------------------

Beállíthatja ezt a tulajdonságot nullára, de még így is egy kis minimális memóriafoglalás megtartásra kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |