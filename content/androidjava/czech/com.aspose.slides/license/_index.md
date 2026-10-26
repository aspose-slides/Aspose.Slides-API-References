---
title: License
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Poskytuje metody pro licencování komponenty.
type: docs
url: /cs/com.aspose.slides/license/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Poskytuje metody k licencování komponenty.

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

## Konstruktory

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Inicializuje novou instanci této třídy. |
## Metody

| Method | Description |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencuje komponentu. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licencuje komponentu. |
| [getVersion()](#getVersion--) | Vrací verzi Aspose.Slides pro Android přes Java. |
| [resetLicense()](#resetLicense--) | Resetuje licenci. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

Inicializuje novou instanci této třídy.

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

Licencuje komponentu.

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


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, který obsahuje licenci. Použijte null pro přepnutí do evaluačního režimu. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Licencuje komponentu.

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


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| namePath | java.lang.String | Může být úplný nebo zkrácený název souboru nebo název vloženého zdroje. Použijte prázdný řetězec pro přepnutí do evaluačního režimu. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Vrací verzi Aspose.Slides pro Android přes Java.

**Vrací:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

Resetuje licenci. Použijte tuto metodu k resetování licence v komponentě.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

Zkontroluje, zda je licence aplikována na komponentu

**Vrací:**
boolean