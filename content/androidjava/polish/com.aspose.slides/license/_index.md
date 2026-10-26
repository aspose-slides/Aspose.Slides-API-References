---
title: License
second_title: Referencja API Aspose.Slides for Android za pośrednictwem Java
description: Udostępnia metody licencjonowania komponentu.
type: docs
url: /pl/com.aspose.slides/license/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Udostępnia metody do licencjonowania komponentu.

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

## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [License()](#License--) | Inicjalizuje nową instancję tej klasy. |
## Metody

| Metoda | Opis |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencjonuje komponent. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licencjonuje komponent. |
| [getVersion()](#getVersion--) | Zwraca wersję Aspose.Slides dla Androida poprzez Java. |
| [resetLicense()](#resetLicense--) | Resetuje licencję. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Inicjalizuje nową instancję tej klasy.

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


Licencjonuje komponent.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień zawierający licencję. Użyj null, aby przełączyć się w tryb ewaluacji. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licencjonuje komponent.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| namePath | java.lang.String | Może być pełną lub krótką nazwą pliku lub nazwą wbudowanego zasobu. Użyj pustego łańcucha, aby przełączyć się w tryb ewaluacji. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Zwraca wersję Aspose.Slides dla Androida poprzez Java.

**Zwraca:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Resetuje licencję. Użyj tej metody, aby zresetować licencję w komponencie.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Sprawdza, czy licencja jest zastosowana do komponentu

**Zwraca:**
boolean