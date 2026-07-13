---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Provides methods to license the component.
type: docs
url: /pl/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Udostępnia metody licencjonowania komponentu.

--------------------

> ```
> W tym przykładzie zostanie podjęta próba znalezienia pliku licencji o nazwie MyLicense.lic
>  w folderze zawierającym komponent, w folderze zawierającym zestaw wywołujący,
>  w folderze zestawu wejściowego, a następnie w zasobach osadzonych w zestawie wywołującym.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
```
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
| licenseName | java.lang.String | Może być pełną lub krótką nazwą pliku albo nazwą zasobu osadzonego. Użyj pustego ciągu, aby przełączyć w tryb oceny.

--------------------

Próbuje znaleźć licencję w następujących lokalizacjach:

1. Ścieżka jawna.
2. Folder zestawu komponentu.
3. Folder zestawu wywołującego klienta.
4. Folder zestawu wejściowego.
5. Zasób osadzony w zestawie wywołującego klienta. |

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
| stream | java.io.InputStream | Strumień zawierający licencję.

--------------------

Użyj tej metody, aby wczytać licencję ze strumienia. |

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
boolean - true jeśli komponent jest licencjonowany, w przeciwnym razie false