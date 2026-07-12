---
title: ILicense
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Proporciona métodos para licenciar el componente.
type: docs
url: /es/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Proporciona métodos para licenciar el componente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencia el componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
| [resetLicense()](#resetLicense--) | Restablece la licencia |
| [isLicensed()](#isLicensed--) | Comprueba si la licencia se aplica al componente |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licencia el componente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | java.lang.String | Puede ser un nombre de archivo completo o abreviado o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación.

--------------------

Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta del ensamblado del componente.

3. La carpeta del ensamblado que llama el cliente.

4. La carpeta del ensamblado de entrada.

5. Un recurso incrustado en el ensamblado que llama el cliente. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licencia el componente.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un flujo que contiene la licencia.

--------------------

Utilice este método para cargar una licencia desde un flujo. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Restablece la licencia

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Utilice este método para restablecer la licencia en el componente

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Comprueba si la licencia se aplica al componente

**Devuelve:**
boolean - true si el componente está licenciado, de lo contrario false