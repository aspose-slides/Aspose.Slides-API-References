---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Provides methods to license the component.
type: docs
url: /sv/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Tillhandahåller metoder för att licensiera komponenten.

--------------------

> ```
> I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic
>  i mappen som innehåller komponenten, i mappen som innehåller den anropande assemblyn,
>  i mappen för startassemblyn och sedan i de inbäddade resurserna i den anropande assemblyn.
>  
  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
| [resetLicense()](#resetLicense--) | Återställer licensen |
| [isLicensed()](#isLicensed--) | Kontrollerar om licensen har tillämpats på komponenten |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | java.lang.String | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge.

--------------------

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen för komponentens assembly.

3. Mappen för klientens anropande assembly.

4. Mappen för startassemblyn.

5. En inbäddad resurs i klientens anropande assembly. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En ström som innehåller licensen.

--------------------

Använd den här metoden för att läsa in en licens från en ström. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Återställer licensen

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


Kontrollerar om licensen har tillämpats på komponenten

**Returnerar:**
boolean - true if component is licensed, otherwise false