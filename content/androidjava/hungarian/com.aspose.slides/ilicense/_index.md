---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Provides methods to license the component.
type: docs
url: /hu/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Metódusokat biztosít az összetevő licenceléséhez.

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

| Metódus | Leírás |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenceli az összetevőt. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenceli az összetevőt. |
| [resetLicense()](#resetLicense--) | A licenc visszaállítása |
| [isLicensed()](#isLicensed--) | Ellenőrzi, hogy a licenc alkalmazva van-e az összetevőn |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licenceli az összetevőt.

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| licenseName | java.lang.String | Lehet teljes vagy rövid fájlnév, vagy beágyazott erőforrás neve. Üres karakterláncot használva átvált értékelő módra. |

--------------------

Megpróbálja megtalálni a licencet a következő helyeken:

1. Kifejezett útvonal.
2. Az összetevő összeállításának mappája.
3. Az ügyfél hívó összeállításának mappája.
4. A belépő összeállítás mappája.
5. Beágyazott erőforrás az ügyfél hívó összeállításában.

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licenceli az összetevőt.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Az engedélyt tartalmazó adatfolyam.

--------------------

Ezt a metódust licenc betöltésére használja adatfolyamból.

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

Ezt a metódust a komponens licencének visszaállításához használja

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Ellenőrzi, hogy a licenc alkalmazva van-e az összetevőn

**Visszatér:**
boolean - igaz, ha az összetevő licencelt, egyébként hamis