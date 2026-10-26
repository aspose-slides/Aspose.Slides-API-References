---
title: Metered
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Proporciona métodos para establecer la clave medida.
type: docs
url: /es/com.aspose.slides/metered/
---
**Herencia:**
java.lang.Object
```
public class Metered
```

Proporciona métodos para establecer la clave medida.
## Constructores

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Inicializa una nueva instancia de esta clase. |
## Métodos

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Establece la clave pública y privada medida. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtiene el tamaño del archivo de consumo |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtiene el crédito de consumo |
| [isMeteredLicensed()](#isMeteredLicensed--) | Verifica si la licencia medida está habilitada |
### Metered() {#Metered--}
```
public Metered()
```

Inicializa una nueva instancia de esta clase.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Establece la clave pública y privada medida. Si usted adquiere una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y se supera el límite de 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, volver a llamar a esta API.

**Parámetros:**
| Parameter | Type | Description |
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

Verifica si la licencia medida está habilitada

**Devuelve:**
boolean - verdadero o falso