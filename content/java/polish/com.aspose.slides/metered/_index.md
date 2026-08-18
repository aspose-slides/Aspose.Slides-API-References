---
title: Metered
second_title: Aspose.Slides dla Java – odniesienie API
description: Udostępnia metody do ustawiania klucza metrowanego.
type: docs
url: /pl/com.aspose.slides/metered/
---
**Dziedziczenie:**
java.lang.Object
```
public class Metered
```

Udostępnia metody do ustawiania klucza metrowanego.
## Konstruktorzy

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Inicjalizuje nową instancję tej klasy. |
## Metody

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ustawia publiczny i prywatny klucz metrowany. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Pobiera rozmiar pliku zużycia |
| [getConsumptionCredit()](#getConsumptionCredit--) | Pobiera kredyt zużycia |
| [isMeteredLicensed()](#isMeteredLicensed--) | Sprawdza, czy metrowany jest licencjonowany |
### Metered() {#Metered--}
```
public Metered()
```


Inicjalizuje nową instancję tej klasy.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ustawia publiczny i prywatny klucz metrowany. Jeśli zakupisz licencję metrową, przy uruchamianiu aplikacji należy wywołać to API; zazwyczaj jest to wystarczające. Jednakże, jeśli zawsze nie udaje się przesłać danych zużycia i minie 24 godziny, licencja zostanie ustawiona w statusie ewaluacji; aby uniknąć takiej sytuacji, należy regularnie sprawdzać status licencji i jeśli jest w statusie ewaluacji, ponownie wywołać to API.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | klucz publiczny |
| privateKey | java.lang.String | klucz prywatny |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Pobiera rozmiar pliku zużycia

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Pobiera kredyt zużycia

**Returns:**
double - ilość zużycia
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Sprawdza, czy metrowany jest licencjonowany

**Returns:**
boolean - Prawda lub fałsz