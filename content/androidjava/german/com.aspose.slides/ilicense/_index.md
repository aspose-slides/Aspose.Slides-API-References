---
title: ILicense
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Methoden zum Lizenzieren der Komponente bereit.
type: docs
url: /de/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Stellt Methoden zum Lizenzieren der Komponente bereit.

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

| Methode | Beschreibung |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
| [resetLicense()](#resetLicense--) | Setzt die Lizenz zurück |
| [isLicensed()](#isLicensed--) | Prüft, ob die Lizenz auf die Komponente angewendet wurde |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Lizenziert die Komponente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | java.lang.String | Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenkette, um in den Evaluierungsmodus zu wechseln. |

--------------------

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner der Komponenten-Assembly.

3. Der Ordner der aufrufenden Assembly des Clients.

4. Der Ordner der Einstieg-Assembly.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients. |
### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Lizenziert die Komponente.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein Stream, der die Lizenz enthält. |

--------------------

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden. |
### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Setzt die Lizenz zurück

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Verwenden Sie diese Methode, um die Lizenz in der Komponente zurückzusetzen

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Prüft, ob die Lizenz auf die Komponente angewendet wurde

**Rückgabe:**
boolean – true, wenn die Komponente lizenziert ist, sonst false