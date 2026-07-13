---
title: License
second_title: Riferimento API di Aspose.Slides per Android tramite Java
description: Fornisce metodi per licenziare il componente.
type: docs
url: /it/com.aspose.slides/license/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Fornisce metodi per licenziare il componente.

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenzia il componente. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licenzia il componente. |
| [getVersion()](#getVersion--) | Restituisce la versione di Aspose.Slides per Android tramite Java. |
| [resetLicense()](#resetLicense--) | Reimposta la licenza. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

Inizializza una nuova istanza di questa classe.

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

Licenzia il componente.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Un flusso che contiene la licenza. Usa null per passare alla modalità di valutazione. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Licenzia il componente.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namePath | java.lang.String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Restituisce la versione di Aspose.Slides per Android tramite Java.

**Restituisce:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

Reimposta la licenza. Usa questo metodo per reimpostare la licenza nel componente.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

Verifica se la licenza è applicata al componente

**Restituisce:**
boolean