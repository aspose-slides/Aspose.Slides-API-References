---
title: ILicense
second_title: Aspose.Slides per Android tramite Java API Reference
description: Fornisce metodi per licenziare il componente.
type: docs
url: /it/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Fornisce metodi per licenziare il componente.

--------------------

> ```
> In questo esempio, si cercherà di trovare un file di licenza chiamato MyLicense.lic
>  nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante,
>  nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
```
## Metodi

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenza il componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenza il componente. |
| [resetLicense()](#resetLicense--) | Reimposta la licenza |
| [isLicensed()](#isLicensed--) | Verifica se la licenza è applicata al componente |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Licenza il componente.

--------------------

> ```
> In questo esempio, si cercherà di trovare un file di licenza chiamato MyLicense.lic
>  nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante,
>  nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | java.lang.String | Può essere un nome di file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

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

Licenza il componente.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Uno stream che contiene la licenza. |

--------------------

Usa questo metodo per caricare una licenza da uno stream. |

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