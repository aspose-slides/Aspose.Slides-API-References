---
title: ILicense
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Poskytuje metody pro licencování komponenty.
type: docs
url: /cs/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Poskytuje metody pro licencování komponenty.

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
| [isLicensed()](#isLicensed--) | Zkontroluje, zda je licence aplikována na komponentu |
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
| licenseName | java.lang.String | Může být úplný nebo zkrácený název souboru nebo název vloženého prostředku. Použijte prázdný řetězec pro přepnutí do evaluačního režimu. |

--------------------

Zkouší najít licenci v následujících umístěních:

1. Explicitní cesta.

2. Složka sestavení komponenty.

3. Složka volajícího sestavení klienta.

4. Složka vstupního sestavení.

5. Vložený prostředek v sestavení volajícího klienta. |

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

Použijte tuto metodu pro načtení licence ze streamu. |

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

Použijte tuto metodu pro resetování licence v komponentě

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Zkontroluje, zda je licence aplikována na komponentu

**Vrací:**
boolean - true pokud je komponenta licencována, jinak false