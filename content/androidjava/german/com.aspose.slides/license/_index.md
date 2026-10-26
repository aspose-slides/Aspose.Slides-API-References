---
title: License
second_title: Aspose.Slides für Android via Java API-Referenz
description: Stellt Methoden zum Lizenzieren der Komponente bereit.
type: docs
url: /de/com.aspose.slides/license/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Stellt Methoden zum Lizenzieren der Komponente bereit.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) | Initialisiert eine neue Instanz dieser Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
| [getVersion()](#getVersion--) | Gibt die Version von Aspose.Slides für Android über Java zurück. |
| [resetLicense()](#resetLicense--) | Setzt die Lizenz zurück. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Initialisiert eine neue Instanz dieser Klasse.

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


Lizenziert die Komponente.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein Stream, der die Lizenz enthält. Verwenden Sie null, um in den Evaluierungsmodus zu wechseln. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Lizenziert die Komponente.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namePath | java.lang.String | Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie einen leeren String, um in den Evaluierungsmodus zu wechseln. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Gibt die Version von Aspose.Slides für Android über Java zurück.

**Rückgabewert:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Setzt die Lizenz zurück. Verwenden Sie diese Methode, um die Lizenz in der Komponente zurückzusetzen.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Überprüft, ob die Lizenz auf die Komponente angewendet wurde.

**Rückgabewert:**
boolean