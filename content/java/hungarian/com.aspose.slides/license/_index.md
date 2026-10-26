---
title: License
second_title: Aspose.Slides for Java API hivatkozás
description: Módszereket biztosít az összetevő licenceléséhez.
type: docs
url: /hu/com.aspose.slides/license/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Módszereket biztosít az összetevő licenceléséhez.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [License()](#License--) | Új példányt hoz létre ebből az osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenceli az összetevőt. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licenceli az összetevőt. |
| [getVersion()](#getVersion--) | Visszaadja az Aspose.Slides for Java verzióját. |
| [resetLicense()](#resetLicense--) | Visszaállítja a licencet. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Új példányt hoz létre ebből az osztályból.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licenceli az összetevőt.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | A licencet tartalmazó adatfolyam. Használja a null értéket a kiértékelési módhoz való váltáshoz. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licenceli az összetevőt.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| namePath | java.lang.String | Lehet teljes vagy rövid fájlnév vagy beágyazott erőforrás neve. Használja az üres karakterláncot a kiértékelési módhoz való váltáshoz. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Visszaadja az Aspose.Slides for Java verzióját.

**Visszatérési érték:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Visszaállítja a licencet. Használja ezt a metódust a licenc visszaállításához az összetevőben.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Ellenőrzi, hogy a licenc alkalmazva van-e az összetevőn

**Visszatérési érték:**
boolean