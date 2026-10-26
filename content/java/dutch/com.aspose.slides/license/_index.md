---
title: License
second_title: Aspose.Slides voor Java API-referentie
description: Biedt methoden om de component te licentiëren.
type: docs
url: /nl/com.aspose.slides/license/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Biedt methoden om de component te licentiëren.

```
In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden.
 in de map die de component bevat, in de map die de aanroepende assembly bevat,
 in de map van de entry-assembly en daarna in de ingesloten bronnen van de aanroepende assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licentieert de component. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licentieert de component. |
| [getVersion()](#getVersion--) | Retourneert versie van Aspose.Slides voor Java. |
| [resetLicense()](#resetLicense--) | Reset de licentie. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Initialiseert een nieuw exemplaar van deze klasse.

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


Licentieert de component.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een stream die de licentie bevat. Gebruik null om over te schakelen naar de evaluatiemodus. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licentieert de component.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| namePath | java.lang.String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde bron zijn. Gebruik een lege string om over te schakelen naar de evaluatiemodus. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Retourneert versie van Aspose.Slides voor Java.

**Retourneert:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Reset de licentie. Gebruik deze methode om de licentie in de component te resetten.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Controleer of de licentie is toegepast op de component

**Retourneert:**
boolean