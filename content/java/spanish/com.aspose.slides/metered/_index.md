---
title: Metered
second_title: Referencia de la API de Aspose.Slides para Java
description: Proporciona métodos para establecer la clave medida.
type: docs
url: /es/com.aspose.slides/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Proporciona métodos para establecer la clave medida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Metered()](#Metered--) | Inicializa una nueva instancia de esta clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Establece la clave pública y privada medida. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtiene el tamaño del archivo de consumo |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtiene el crédito de consumo |
| [isMeteredLicensed()](#isMeteredLicensed--) | Comprueba si la licencia medida está activada |
### Metered() {#Metered--}
```
public Metered()
```

Inicializa una nueva instancia de esta clase.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Establece la clave pública y privada medida. Si adquieres una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la subida de datos de consumo y supera las 24 horas, la licencia pasará a estado de evaluación; para evitar este caso, deberías comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | java.lang.String | clave pública |
| privateKey | java.lang.String | clave privada |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Obtiene el tamaño del archivo de consumo

**Devuelve:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Obtiene el crédito de consumo

**Devuelve:**
double - cantidad de consumo
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Comprueba si la licencia medida está activada

**Devuelve:**
boolean - Verdadero o falso