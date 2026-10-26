---
title: License
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt methoden om het component te licenseren.
type: docs
url: /nl/com.aspose.slides/license/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Biedt methoden om het component te licenseren.

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

## Constructors

| Constructor | Omschrijving |
| --- | --- |
| [License()](#License--) | Initialises a new instance of this class. |
## Methods

| Methode | Omschrijving |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [getVersion()](#getVersion--) | Returns version of Aspose.Slides for Android via Java. |
| [resetLicense()](#resetLicense--) | Reset the license. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Initialiseert een nieuwe instantie van deze klasse.

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


Licentieert het component.

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


**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een stream die de licentie bevat. Gebruik null om over te schakelen naar evaluatiemodus. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licentieert het component.

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


**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| namePath | java.lang.String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde bron zijn. Gebruik een lege string om over te schakelen naar evaluatiemodus. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Retourneert de versie van Aspose.Slides voor Android via Java.

**Retourneert:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Reset de licentie. Gebruik deze methode om de licentie in het component te resetten.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Controleer of licentie is toegepast op het component

**Retourneert:**
boolean