---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /it/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Fornisce metodi per licenziare il componente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenzia il componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenzia il componente. |
| [resetLicense()](#resetLicense--) | Reimposta la licenza |
| [isLicensed()](#isLicensed--) | Verifica se la licenza è applicata al componente |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licenzia il componente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | java.lang.String | Può essere un nome file completo o abbreviato o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione.

--------------------

Cerca di trovare la licenza nelle seguenti posizioni:

1. Percorso esplicito.
2. La cartella dell'assembly del componente.
3. La cartella dell'assembly chiamante del client.
4. La cartella dell'assembly di ingresso.
5. Una risorsa incorporata nell'assembly chiamante del client. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licenzia il componente.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Un flusso che contiene la licenza.

--------------------

Usa questo metodo per caricare una licenza da un flusso. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Reimposta la licenza

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


--------------------

Usa questo metodo per reimpostare la licenza nel componente

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Verifica se la licenza è applicata al componente

**Restituisce:**
boolean - true se il componente è licenziato, altrimenti false