---
title: License
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Proporciona métodos para licenciar el componente.
type: docs
url: /es/com.aspose.slides/license/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Proporciona métodos para licenciar el componente.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) | Inicializa una nueva instancia de esta clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licencia el componente. |
| [getVersion()](#getVersion--) | Devuelve la versión de Aspose.Slides for Android mediante Java. |
| [resetLicense()](#resetLicense--) | Restablece la licencia. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Inicializa una nueva instancia de esta clase.

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


Licencia el componente.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un flujo que contiene la licencia. Use null para cambiar al modo de evaluación. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licencia el componente.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namePath | java.lang.String | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Devuelve la versión de Aspose.Slides for Android mediante Java.

**Devuelve:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Restablece la licencia. Use este método para restablecer la licencia en el componente.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Comprueba si la licencia está aplicada al componente

**Devuelve:**
boolean