---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /nl/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Biedt methoden om het component te licentiëren.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licentieert het component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licentieert het component. |
| [resetLicense()](#resetLicense--) | Reset de licentie |
| [isLicensed()](#isLicensed--) | Controleert of de licentie is toegepast op het component |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Licentieert het component.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | java.lang.String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege tekenreeks om over te schakelen naar evaluatiemodus.

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.
2. De map van de componentassembly.
3. De map van de aanroepende assembly van de client.
4. De map van de entry-assembly.
5. Een ingebedde resource in de aanroepende assembly van de client. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

Licentieert het component.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een stream die de licentie bevat.

Gebruik deze methode om een licentie te laden vanuit een stream. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

Reset de licentie

--------------------

```
> License license = new License();
>  license.resetLicense();
> ```

Gebruik deze methode om de licentie in het component te resetten

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

Controleert of de licentie is toegepast op het component

**Retour:**
boolean - true als het component gelicentieerd is, anders false