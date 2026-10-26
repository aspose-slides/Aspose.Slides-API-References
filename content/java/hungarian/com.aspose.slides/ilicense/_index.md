---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Metódusokat biztosít a komponens licenceléséhez.
type: docs
url: /hu/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Metódusokat biztosít a komponens licenceléséhez.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Módszerek

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenceli a komponenst. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenceli a komponenst. |
| [resetLicense()](#resetLicense--) | A licenc visszaállítása |
| [isLicensed()](#isLicensed--) | Ellenőrzi, hogy a licenc alkalmazva van-e a komponensre |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Licenceli a komponenst.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Lehet teljes vagy rövid fájlnév, vagy egy beágyazott erőforrás neve. Üres karakterlánc használatával értékelő módba lép.

--------------------

Megpróbálja megtalálni a licencet a következő helyeken:

1. Kifejezett útvonal.
2. A komponens összeállításának mappája.
3. A kliens hívó összeállításának mappája.
4. A belépő összeállítás mappája.
5. Beágyazott erőforrás a kliens hívó összeállításában. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

Licenceli a komponenst.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Egy folyam, amely a licencet tartalmazza.

--------------------

Használja ezt a módszert licenc betöltéséhez egy folyamról. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

A licenc visszaállítása

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Használja ezt a módszert a licenc visszaállításához a komponensben

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

Ellenőrzi, hogy a licenc alkalmazva van-e a komponensre

**Visszatérési érték:**
boolean - igaz, ha a komponens licencelt, egyébként hamis