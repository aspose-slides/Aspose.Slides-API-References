---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Poskytuje metody pro licencování komponenty.
type: docs
url: /cs/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Poskytuje metody k licencování komponenty.

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

| Metoda | Popis |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencuje komponentu. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencuje komponentu. |
| [resetLicense()](#resetLicense--) | Resetuje licenci |
| [isLicensed()](#isLicensed--) | Kontroluje, zda je licence aplikována na komponentu |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licencuje komponentu.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| licenseName | java.lang.String | Může být úplným nebo zkráceným názvem souboru nebo názvem vloženého prostředku. Použijte prázdný řetězec pro přepnutí do režimu hodnocení. |

--------------------

Pokouší se najít licenci na následujících místech:

1. Explicitní cesta.
2. Složka sestavení komponenty.
3. Složka volající sestavy klienta.
4. Složka vstupní sestavy.
5. Vložený prostředek ve volající sestavě klienta. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licencuje komponentu.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Proud, který obsahuje licenci. |

--------------------

Tuto metodu použijte k načtení licence ze streamu. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Resetuje licenci

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Tuto metodu použijte k resetování licence v komponentě

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Kontroluje, zda je licence aplikována na komponentu

**Vrací:**
boolean - true pokud je komponenta licencována, jinak false