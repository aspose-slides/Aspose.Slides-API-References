---
title: License
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller metoder för att licensiera komponenten.
type: docs
url: /sv/com.aspose.slides/license/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Tillhandahåller metoder för att licensiera komponenten.

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

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License--) | Initierar en ny instans av den här klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [getVersion()](#getVersion--) | Returnerar versionen av Aspose.Slides för Android via Java. |
| [resetLicense()](#resetLicense--) | Återställ licensen. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Initierar en ny instans av den här klassen.

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


Licensierar komponenten.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En ström som innehåller licensen. Använd null för att växla till utvärderingsläge. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licensierar komponenten.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namePath | java.lang.String | Kan vara ett fullt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Returnerar versionen av Aspose.Slides för Android via Java.

**Returnerar:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Återställ licensen. Använd den här metoden för att återställa licensen i komponenten.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Kontrollera om licensen har tillämpats på komponenten

**Returnerar:**
boolean