---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /sv/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Tillhandahåller metoder för att licensiera komponenten.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Metoder

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
| [resetLicense()](#resetLicense--) | Återställ licensen |
| [isLicensed()](#isLicensed--) | Kontrollera om licensen har tillämpats på komponenten |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licensierar komponenten.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Kan vara ett fullständigt eller kort filnamn eller namnet på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge.

--------------------

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen för komponentens sammansättning.

3. Mappen för klientens anropande sammansättning.

4. Mappen för start-sammansättningen.

5. En inbäddad resurs i klientens anropande sammansättning. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licensierar komponenten.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | En ström som innehåller licensen.

--------------------

Använd den här metoden för att läsa in en licens från en ström. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Återställ licensen

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Använd den här metoden för att återställa licensen i komponenten

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Kontrollera om licensen har tillämpats på komponenten

**Returnerar:**
boolean - true om komponenten är licensierad, annars false