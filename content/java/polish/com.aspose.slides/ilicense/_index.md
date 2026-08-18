---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Udostępnia metody licencjonowania komponentu.
type: docs
url: /pl/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Udostępnia metody licencjonowania komponentu.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencjonuje komponent. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencjonuje komponent. |
| [resetLicense()](#resetLicense--) | Resetuje licencję |
| [isLicensed()](#isLicensed--) | Sprawdza, czy licencja jest zastosowana do komponentu |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licencjonuje komponent.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| licenseName | java.lang.String | Może być pełną lub krótką nazwą pliku lub nazwą zasobu osadzonego. Użyj pustego ciągu znaków, aby przełączyć w tryb ewaluacji. |

--------------------

Próbuje znaleźć licencję w następujących lokalizacjach:

1. Ścieżka jawna.

2. Folder zestawu komponentu.

3. Folder zestawu wywołującego klienta.

4. Folder zestawu wejściowego.

5. Zasób osadzony w zestawie wywołującym klienta. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licencjonuje komponent.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień zawierający licencję. |

--------------------

Użyj tej metody, aby załadować licencję ze strumienia. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Resetuje licencję

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

Użyj tej metody, aby zresetować licencję w komponencie

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Sprawdza, czy licencja jest zastosowana do komponentu

**Zwraca:**
boolean - true, jeśli komponent jest licencjonowany, w przeciwnym razie false